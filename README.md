# Samsung Wireless Audio Multiroom API 

Samsung Wireless Audio Multiroom Control API Documentation

## Page contents 

* Motivation
* Basic structure
* API Methods

Useful links:
* [More details on Samsung Wireless Audio Multiroom (WAM) Research - moosy](https://sites.google.com/view/samsungwirelessaudiomultiroom/) 
* [Samsung Multiroom Console Client - fhatz](https://gist.github.com/fhatz/f5645682f3f1d73583035980a921f59b)
 
* * *

## Motivation

I recently bought a R1 speaker (WAM1500) I liked it so much I bought a second. They are great for my use case but:
* it "refuses" to play with other devides 
* the companion software is terrible ( Android app ) ( and now I can guess that it will be always terrible, and it is not the Androids team fault). 

I want to be able to:
* control it without a phone (done)
* start to play a playlist only with *one* push of a button or event (done)
* send a URL with an audio stream to listen on the speaker (in future)

   
At first glace the firmware has implemented the standards in this area, yet refuses to play width other devices. 
After much diging in the wrong dirtections, I "accidentaly" found how the speacker is controlled. 
Every control comand is done with only a HTTP GET request (excluding Spotify ). 
This is for getting and setting data. 
Apparently, without **any security** check. 






## Basic structure 
_(based on R1 WAM1500 fw: 31112.5)_
 

The speaker is controlled by **HTTP GET** request at 
> http://ip_speaker:55001

This is either for getting information or to set configurations.

The url path can be:
* /CPM
* /UCI 

_(I don't know the difference)_



Both of them accept a query string, with a field name "cmd" and its value is a xml string with the method you want to call (which it is url encoded).


XML method can have the following elements :
```  
<name>_API_method_name_</name>
<p type="dec" name="_var_name_" val="_integer_" />
<p type="str" name="_var_name_" val="_string_" />
<p type="cdata" name="_var_name_" val="empty">
    <![CDATA[ _string_  ]]>
</p>
```

#### Example: 
Useful links: 
* [Online URL encoder/decoder](http://meyerweb.com/eric/tools/dencoder/) 
 

Xml string URL Decoded:
``` 
<name>
    GetMusicInfo
</name>
```

Xml string URL Encoded:

	%3Cname%3EGetMusicInfo%3C/name%3E



Now we can do a http get request test:

	curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetMusicInfo%3C/name%3E'
	
and we get:
 ``` 
<?xml version="1.0" encoding="UTF-8"?>
<UIC><method>MusicInfo</method>
<version>1.0</version>
<speakerip>ip_speaker</speakerip>
<user_identifier>public</user_identifier>
<response result="ok">
    <device_udn>uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx</device_udn>
    <playertype>myphone</playertype>
    <playbacktype>playlist</playbacktype>
    <sourcename><![CDATA[phone]]></sourcename>
    <parentid>1$4</parentid>
    <parentid2></parentid2>
    <playindex>0</playindex>
    <objectid><![CDATA[1$4$0]]></objectid>
    <title><![CDATA[music_name]]></title>
    <artist><![CDATA[]]></artist>
    <album><![CDATA[]]></album>
    <thumbnail><![CDATA[music_cover.png]]></thumbnail>
    <timelength>0:52:29.688</timelength>
    <playtime>2170944</playtime>
    <seek>enable</seek>
    <pause>enable</pause>
</response>
</UIC>
```


****
## API Methods

This list is incomplete and missing some details and methods.  [link](API_Methods.md)



baclpt 2017/04/09
