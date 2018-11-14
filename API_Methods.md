
****
## API Methods

This list is incomplete and missing some details and methods.


### 1 - AddSongsToMultiQueue
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EAddSongsToMultiQueue%3C/name%3E%3Cp%20type=%22dec%22%20name=%22count%22%20val=%227%22/%3E%3Cp%20type=%22dec%22%20name=%22totalcount%22%20val=%227%22/%3E%3Cp%20type=%22str%22%20name=%22position%22%20val=%22last%22/%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$0%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[musicName]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$6%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Pulse8_Best%20of%20Chillstep%20Mix%20-%20April%202017%20[1%20Hour%20of%20Chillstep%20Music]]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$7%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Pulse8_Journey%20Within%20-%20A%20Chillstep%20Dubstep%20Mix]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$1%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Fusion%20Alchemist]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[Samaya]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$2%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Samaya%20-%20On%20Tribe%20Mixtape]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[Samaya]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$3%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Shivelight_Bassline%20Drift%20-%20Nature%20(Anchor%20Hill%20Remix)]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$4%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Ukiyo%20-%20Calling]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E' 
```  
 Xml string decoded: 
```  
<name>AddSongsToMultiQueue</name>
<p type="dec" name="count" val="7"/>
<p type="dec" name="totalcount" val="7"/>
<p type="str" name="position" val="last"/>
<p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/>
<p type="str" name="objectid" val="1$4$0"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[musicName]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
<p type="str" name="objectid" val="1$4$6"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Pulse8_Best of Chillstep Mix - April 2017 [1 Hour of Chillstep Music]]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[]]></p><p type="str" name="objectid" val="1$4$7"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Pulse8_Journey Within - A Chillstep Dubstep Mix]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
<p type="str" name="objectid" val="1$4$1"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Fusion Alchemist]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[Samaya]]></p>
<p type="str" name="objectid" val="1$4$2"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Samaya - On Tribe Mixtape]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[Samaya]]></p>
<p type="str" name="objectid" val="1$4$3"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Shivelight_Bassline Drift - Nature (Anchor Hill Remix)]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
<p type="str" name="objectid" val="1$4$4"/>
<p type="cdata" name="songtitle" val="empty"><![CDATA[Ukiyo - Calling]]></p>
<p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p>
<p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
```  

Response:  

```  
--- 
``` 

****

### 2 - DelAlarm
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EDelAlarm%3C/name%3E%3Cp%20type=%22dec%22%20name=%22totaldelnum%22%20val=%221%22/%3E%3Cp%20type=%22dec%22%20name=%22index%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22index%22%20val=%22-1%22/%3E%3Cp%20type=%22dec%22%20name=%22index%22%20val=%22-1%22/%3E' 
```  
 Xml string decoded: 
```  
<name>DelAlarm</name>
<p type="dec" name="totaldelnum" val="1"/>
<p type="dec" name="index" val="0"/>
<p type="dec" name="index" val="-1"/>
<p type="dec" name="index" val="-1"/>
```  

Response:  

```  
--- 
``` 

****

### 3 - GetAcmMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAcmMode%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAcmMode</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AcmMode</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <acmmode>aasync</acmmode>
        <audiosourcemacaddr>00:00:00:00:00:00</audiosourcemacaddr>
        <audiosourcename><![CDATA[]]></audiosourcename>
        <audiosourcetype>none</audiosourcetype>
    </response>
</UIC>
``` 

****

### 4 - GetAlarmInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAlarmInfo%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAlarmInfo</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AllAlarmInfo</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <totalindexcount>0</totalindexcount>
        <alarmList></alarmList>
    </response>
</UIC> 
``` 

****

### 5 - GetAlarmSoundList
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAlarmSoundList%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAlarmSoundList</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AlarmSoundList</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <listcount>4</listcount>
        <alarmlist>
            <alarmsound index="0">
                <alarsoundindex>0</alarsoundindex>
                <alarmsoundname>Active Morning</alarmsoundname>
            </alarmsound>
            <alarmsound index="1">
                <alarsoundindex>1</alarsoundindex>
                <alarmsoundname>Disco</alarmsoundname>
            </alarmsound>
            <alarmsound index="2">
                <alarsoundindex>2</alarsoundindex>
                <alarmsoundname>Vintage</alarmsoundname>
            </alarmsound>
            <alarmsound index="3">
                <alarsoundindex>3</alarsoundindex>
                <alarmsoundname>Waltz</alarmsoundname>
            </alarmsound>
        </alarmlist>
    </response>
</UIC>
``` 

****

### 6 - GetApInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetApInfo%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetApInfo</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>ApInfo</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <ssid>
            <![CDATA[your name]]>
        </ssid>
        <mac>your mac</mac>
        <rssi>4</rssi>
        <ch>136</ch>
        <wifidirectssid>
            <![CDATA[]]>
        </wifidirectssid>
        <wifidirectrssi></wifidirectrssi>
        <wifidirectch></wifidirectch>
        <connectiontype>wireless</connectiontype>
    </response>
</UIC>
``` 

****

### 7 - GetAudioUI
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAudioUI%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAudioUI</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AudioUI</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <audioui>on</audioui>
    </response>
</UIC> 
``` 

****

### 8 - GetAutoUpdate
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAutoUpdate%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAutoUpdate</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AutoUpdate</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <autoupdate>on</autoupdate>
    </response>
</UIC> 
``` 

****

### 9 - GetAvSourceAll
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetAvSourceAll%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetAvSourceAll</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>AvSourceAll</method>
    <version>1.0</version>
    <speakerip>ip_speaker</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <listcount>0</listcount>
        <avsourcelist></avsourcelist>
    </response>
</UIC> 
``` 

****

### 10 - GetCpInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3EGetCpInfo%3C/name%3E%3Cp%20type=%22str%22%20name=%22cpname%22%20val=%22Spotify%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCpInfo</name><p type="str" name="cpname" val="Spotify"/>
```  

Response:  

```  
--- 
``` 

****

### 11 - GetCpList
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3EGetCpList%3C/name%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCpList</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="20"/>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?><CPM><method>CpList</method><version>0.1</version><speakerip>ip_speaker</speakerip><user_identifier>public</user_identifier><response result="ok">
    <listtotalcount>23</listtotalcount>
    <liststartindex>0</liststartindex>
    <listcount>23</listcount>
    <cplist>
        <cp>
            
            <cpid>0</cpid>
            <cpname>Pandora</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>1</cpid>
            <cpname>Spotify</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>2</cpid>
            <cpname>Deezer</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>3</cpid>
            <cpname>Napster</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>4</cpid>
            <cpname>8tracks</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>5</cpid>
            <cpname>iHeartRadio</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>7</cpid>
            <cpname>BugsMusic</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>8</cpid>
            <cpname>JUKE</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>9</cpid>
            <cpname>7digital</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>10</cpid>
            <cpname>Murfie</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>11</cpid>
            <cpname>JB HI-FI Now</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>12</cpid>
            <cpname>Rhapsody</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>13</cpid>
            <cpname>Qobuz</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>15</cpid>
            <cpname>Stitcher</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>16</cpid>
            <cpname>MTV Music</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>19</cpid>
            <cpname>MelOn</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>21</cpid>
            <cpname>Tidal HiFi</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>22</cpid>
            <cpname>SiriusXM</cpname>
            <signinstatus>0</signinstatus>
        </cp>
        <cp>
            
            <cpid>23</cpid>
            <cpname>Anghami</cpname>
            <signinstatus>0</signinstatus>
            <istrial_user>1</istrial_user>
        </cp>
    </cplist>
</response>
</CPM>
``` 

****

### 12 - GetCurrentMultiQueuelist
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetCurrentMultiQueuelist%3C/name%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%221%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCurrentMultiQueuelist</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="1"/>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>GetMultiQueueListResult</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier>public</user_identifier>
    <response result="ng">
        <errCode>Index Error</errCode>
    </response>
</UIC> 
``` 

****

### 13 - GetCurrentMultiQueuelist
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetCurrentMultiQueuelist%3C/name%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2210%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCurrentMultiQueuelist</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="10"/>
```  

Response:  

```  
--- 
``` 

****

### 14 - GetCurrentMultiQueuelist
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetCurrentMultiQueuelist%3C/name%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2265536%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCurrentMultiQueuelist</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="65536"/>
```  

Response:  

```  
--- 
``` 

****

### 15 - GetCurrentPlaylist
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetCurrentPlaylist%3C/name%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetCurrentPlaylist</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 16 - GetCurrentPlayTime
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetCurrentPlayTime%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetCurrentPlayTime</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>MusicPlayTime</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier>public</user_identifier>
    <response result="ok">
        <timelength>0</timelength>
        <playtime>8122</playtime>
    </response>
</UIC> 
``` 

****

### 17 - GetFunc
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetFunc%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetFunc</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>CurrentFunc</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <function>wifi</function>
        <submode>cp</submode>
        <connection></connection>
        <devicename>
            <![CDATA[]]>
        </devicename>
    </response>
</UIC> 
``` 

****

### 18 - GetIcon
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetIcon%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetIcon</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SpkIcon</method>
    <version>1.0</version>
    <speakerip>192.168.178.16</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <icon>0</icon>
    </response>
</UIC> 
``` 

****

### 19 - GetLed
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetLed%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetLed</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>LedStatus</method>
    <version>1.0</version>
    <speakerip>192.168.178.16</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <led>on</led>
    </response>
</UIC> 
``` 

****

### 20 - GetMainInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetMainInfo%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetMainInfo</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>RequestDeviceInfo</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier>public</user_identifier>
    <response result="ok"></response>
</UIC> 
``` 

****

### 21 - GetMusicInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetMusicInfo%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetMusicInfo</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>MusicInfo</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ng">
        <errCode>Wifi Sub Mode is CP</errCode>
    </response>
</UIC> 
``` 

****

### 22 - GetMute
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetMute%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetMute</name>
```  

Response:  

```  
--- 
``` 

****

### 23 - GetPlayStatus
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetPlayStatus%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetPlayStatus</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>PlayStatus</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <function>wifi</function>
        <submode>cp</submode>
    </response>
</UIC> 
``` 

****

### 24 - GetPresetList
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3EGetPresetList%3C/name%3E%3Cp%20type=%22dec%22%20name=%22startindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%22100%22/%3E' 
```  
 Xml string decoded: 
```  
<name>GetPresetList</name><p type="dec" name="startindex" val="0"/><p type="dec" name="listcount" val="100"/>
```  

Response:  

```  
--- 
``` 

****

### 25 - GetRadioInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3EGetRadioInfo%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetRadioInfo</name>
```  

Response:  

```  
--- 
``` 

****

### 26 - GetRepeatMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetRepeatMode%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetRepeatMode</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>RepeatMode</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <repeat>off</repeat>
    </response>
</UIC> 
``` 

****

### 27 - GetShuffleMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetShuffleMode%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetShuffleMode</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>ShuffleMode</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <shuffle>off</shuffle>
    </response>
</UIC> 
``` 

****

### 28 - GetSleepTimer
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSleepTimer%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSleepTimer</name>
```  

Response:  

```  
--- 
``` 

****

### 29 - GetSoftwareVersion
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSoftwareVersion%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSoftwareVersion</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SoftwareVersion</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <version>WAM1500WWB-3117.1</version>
        <displayversion>WAM1500WWB-3117.1</displayversion>
    </response>
</UIC> 
``` 

****

### 30 - GetSpeakerBuyer
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSpeakerBuyer%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSpeakerBuyer</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SpeakerBuyer</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <buyer>ZF</buyer>
    </response>
</UIC> 
``` 

****

### 31 - GetSpeakerWifiRegion
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSpeakerWifiRegion%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSpeakerWifiRegion</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SpeakerWifiRegion</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <wifi>E</wifi>
    </response>
</UIC> 
``` 

****

### 32 - GetSpkName
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSpkName%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSpkName</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SpkName</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <spkname>
            <![CDATA[Speaker Name Here]]>
        </spkname>
    </response>
</UIC> 
``` 

****

### 33 - GetSubSoftwareVersion
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetSubSoftwareVersion%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetSubSoftwareVersion</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>SubSoftwareVersion</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <Subversion1>181R</Subversion1>
        <Subversion2>WAM1500WWT-1700</Subversion2>
        <Subversion3>Not Available</Subversion3>
        <Subversion4>Not Available</Subversion4>
        <Subversion5>Not Available</Subversion5>
    </response>
</UIC> 
``` 

****

### 34 - GetVolume
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetVolume%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>GetVolume</name>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?>
<UIC>
    <method>VolumeLevel</method>
    <version>1.0</version>
    <speakerip>ip_address</speakerip>
    <user_identifier></user_identifier>
    <response result="ok">
        <volume>5</volume>
    </response>
</UIC> 
``` 

****

### 35 - PCGetMusicListByCategory
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByCategory%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22categoryid%22%20val=%22folder%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByCategory</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="categoryid" val="folder"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="20"/>
```  

Response:  

```  
--- 
``` 

****

### 36 - PCGetMusicListByCategory
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByCategory%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22categoryid%22%20val=%22folder%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByCategory</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="categoryid" val="folder"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="20"/>
```  

Response:  

```  
--- 
``` 

****

### 37 - PCGetMusicListByCategory
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByCategory%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22categoryid%22%20val=%22folder%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByCategory</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="categoryid" val="folder"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="20"/>
```  

Response:  

```  
--- 
``` 

****

### 38 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%221$4%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="1$4"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 39 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%221$F%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="1$F"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 40 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%226654AF0052B59A1B05685A43DA07E373%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="6654AF0052B59A1B05685A43DA07E373"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 41 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%22folder%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="folder"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 42 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%22322bce17ef52c0b60c2f%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="322bce17ef52c0b60c2f"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 43 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%223aa71ce4a78f3960bf53%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="3aa71ce4a78f3960bf53"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 44 - PCGetMusicListByID
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EPCGetMusicListByID%3C/name%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22filter%22%20val=%22folder%22/%3E%3Cp%20type=%22str%22%20name=%22parentid%22%20val=%22abe6121c-1731-4683-815c-89e1dcd2bf11%22/%3E%3Cp%20type=%22dec%22%20name=%22liststartindex%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22listcount%22%20val=%2230%22/%3E' 
```  
 Xml string decoded: 
```  
<name>PCGetMusicListByID</name><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="filter" val="folder"/><p type="str" name="parentid" val="abe6121c-1731-4683-815c-89e1dcd2bf11"/><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="30"/>
```  

Response:  

```  
--- 
``` 

****

### 45 - SetAlarmInfo
Description: %20%20%20%20%20%20%20%20

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetAlarmInfo%3C/name%3E%3Cp%20type=%22dec%22%20name=%22index%22%20val=%220%22/%3E%3Cp%20type=%22dec%22%20name=%22hour%22%20val=%2222%22/%3E%3Cp%20type=%22dec%22%20name=%22min%22%20val=%2248%22/%3E%3Cp%20type=%22str%22%20name=%22week%22%20val=%220x01%22/%3E%3Cp%20type=%22dec%22%20name=%22volume%22%20val=%226%22/%3E%3Cp%20type=%22cdata%22%20name=%22title%22%20val=%22empty%22%3E%3C![CDATA[WCPT]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22description%22%20val=%22empty%22%3E%3C![CDATA[Norman%20Goldman]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22stationurl%22%20val=%22empty%22%3E%3C![CDATA[http://]]%3E%3C/p%3E%3Cp%20type=%22str%22%20name=%22soundenable%22%20val=%22off%22/%3E%3Cp%20type=%22dec%22%20name=%22sound%22%20val=%22-1%22/%3E%3Cp%20type=%22dec%22%20name=%22duration%22%20val=%220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetAlarmInfo</name><p type="dec" name="index" val="0"/><p type="dec" name="hour" val="22"/><p type="dec" name="min" val="48"/><p type="str" name="week" val="0x01"/><p type="dec" name="volume" val="6"/><p type="cdata" name="title" val="empty"><![CDATA[WCPT]]></p><p type="cdata" name="description" val="empty"><![CDATA[Norman Goldman]]></p><p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p><p type="cdata" name="stationurl" val="empty"><![CDATA[http://]]></p><p type="str" name="soundenable" val="off"/><p type="dec" name="sound" val="-1"/><p type="dec" name="duration" val="0"/>
```  

Response:  

```  
--- 
``` 

****

### 46 - SetAlarmOnOff
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetAlarmOnOff%3C/name%3E%3Cp%20type=%22dec%22%20name=%22index%22%20val=%220%22/%3E%3Cp%20type=%22str%22%20name=%22alarm%22%20val=%22on%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetAlarmOnOff</name><p type="dec" name="index" val="0"/><p type="str" name="alarm" val="on"/>
```  

Response:  

```  
--- 
``` 

****

### 47 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%221%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="1"/>
```  

Response:  

```  
--- 
``` 

****

### 48 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%2210%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="10"/>
```  

Response:  

```  
--- 
``` 

****

### 49 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%2213%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="13"/>
```  

Response:  

```  
--- 
``` 

****

### 50 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%222%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="2"/>
```  

Response:  

```  
--- 
``` 

****

### 51 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%2221%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="21"/>
```  

Response:  

```  
--- 
``` 

****

### 52 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%223%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="3"/>
```  

Response:  

```  
--- 
``` 

****

### 53 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%228%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="8"/>
```  

Response:  

```  
--- 
``` 

****

### 54 - SetCpService
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetCpService%3C/name%3E%3Cp%20type=%22dec%22%20name=%22cpservice_id%22%20val=%229%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetCpService</name><p type="dec" name="cpservice_id" val="9"/>
```  

Response:  

```  
--- 
``` 

****

### 55 - SetFunc
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetFunc%3C/name%3E%3Cp%20type=%22str%22%20name=%22function%22%20val=%22bt%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetFunc</name><p type="str" name="function" val="bt"/>
```  

Response:  

```  
--- 
``` 

****

### 56 - SetFunc
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetFunc%3C/name%3E%3Cp%20type=%22str%22%20name=%22function%22%20val=%22soundshare%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetFunc</name><p type="str" name="function" val="soundshare"/>
```  

Response:  

```  
--- 
``` 

****

### 57 - SetFunc
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetFunc%3C/name%3E%3Cp%20type=%22str%22%20name=%22function%22%20val=%22wifi%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetFunc</name><p type="str" name="function" val="wifi"/>
```  

Response:  

```  
--- 
``` 

****

### 58 - SetIpInfo
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetIpInfo%3C/name%3E%3Cp%20type=%22str%22%20name=%22uuid%22%20val=%22xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22ip%22%20val=%22192.10.1.197:49200%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetIpInfo</name><p type="str" name="uuid" val="xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="ip" val="192.10.1.197:49200"/>
```  

Response:  

```  
--- 
``` 

****

### 59 - SetLed
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetLed%3C/name%3E%3Cp%20type=%22str%22%20name=%22option%22%20val=%22off%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetLed</name><p type="str" name="option" val="off"/>
```  

Response:  

```  
--- 
``` 

****

### 60 - SetLed
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetLed%3C/name%3E%3Cp%20type=%22str%22%20name=%22option%22%20val=%22on%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetLed</name><p type="str" name="option" val="on"/>
```  

Response:  

```  
--- 
``` 

****

### 61 - SetLocale
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetLocale%3C/name%3E%3Cp%20type=%22str%22%20name=%22locale%22%20val=%22en-US%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetLocale</name><p type="str" name="locale" val="en-US"/>
```  

Response:  

```  
--- 
``` 

****

### 62 - SetNewPlaylistPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetNewPlaylistPlaybackControl%3C/name%3E%3Cp%20type=%22dec%22%20name=%22selcount%22%20val=%221%22/%3E%3Cp%20type=%22dec%22%20name=%22playtime%22%20val=%220%22/%3E%3Cp%20type=%22str%22%20name=%22type%22%20val=%22new%22/%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$0%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[musicName]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E' 
```  
 Xml string decoded: 
```  
<name>SetNewPlaylistPlaybackControl</name><p type="dec" name="selcount" val="1"/><p type="dec" name="playtime" val="0"/><p type="str" name="type" val="new"/><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="objectid" val="1$4$0"/><p type="cdata" name="songtitle" val="empty"><![CDATA[musicName]]></p><p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p><p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
```  

Response:  

```  
--- 
``` 

****

### 63 - SetNewPlaylistPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetNewPlaylistPlaybackControl%3C/name%3E%3Cp%20type=%22dec%22%20name=%22selcount%22%20val=%228%22/%3E%3Cp%20type=%22dec%22%20name=%22playtime%22%20val=%220%22/%3E%3Cp%20type=%22str%22%20name=%22type%22%20val=%22last%22/%3E%3Cp%20type=%22str%22%20name=%22device_udn%22%20val=%22uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx%22/%3E%3Cp%20type=%22str%22%20name=%22objectid%22%20val=%221$4$5%22/%3E%3Cp%20type=%22cdata%22%20name=%22songtitle%22%20val=%22empty%22%3E%3C![CDATA[Andromeda%20Dreams%20-%20'Sea'%20no%20Evil]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22thumbnail%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E%3Cp%20type=%22cdata%22%20name=%22artist%22%20val=%22empty%22%3E%3C![CDATA[]]%3E%3C/p%3E' 
```  
 Xml string decoded: 
```  
<name>SetNewPlaylistPlaybackControl</name><p type="dec" name="selcount" val="8"/><p type="dec" name="playtime" val="0"/><p type="str" name="type" val="last"/><p type="str" name="device_udn" val="uuid:xxxxxxxx-xxxxx-xxxxe-xxxxx-xxxxxxxxx"/><p type="str" name="objectid" val="1$4$5"/><p type="cdata" name="songtitle" val="empty"><![CDATA[Andromeda Dreams - 'Sea' no Evil]]></p><p type="cdata" name="thumbnail" val="empty"><![CDATA[]]></p><p type="cdata" name="artist" val="empty"><![CDATA[]]></p>
```  

Response:  

```  
--- 
``` 

****

### 64 - SetPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetPlaybackControl%3C/name%3E%3Cp%20type=%22str%22%20name=%22playbackcontrol%22%20val=%22pause%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetPlaybackControl</name><p type="str" name="playbackcontrol" val="pause"/>
```  

Response:  

```  
--- 
``` 

****

### 65 - SetPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetPlaybackControl%3C/name%3E%3Cp%20type=%22str%22%20name=%22playbackcontrol%22%20val=%22play%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetPlaybackControl</name><p type="str" name="playbackcontrol" val="play"/>
```  

Response:  

```  
--- 
``` 

****

### 66 - SetPlayPreset
Description: TuneIn – Play preset

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetPlayPreset%3C/name%3E%3Cp%20type=%22dec%22%20name=%22presetindex%22%20val=%2215%22/%3E%3Cp%20type=%22dec%22%20name=%22presettype%22%20val=%220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetPlayPreset</name><p type="dec" name="presetindex" val="15"/><p type="dec" name="presettype" val="0"/>
```  

Response:  

```  
<?xml version="1.0" encoding="UTF-8"?><UIC><method>StopPlaybackEvent</method><version>1.0</version><speakerip>192.10.1.11</speakerip><user_identifier>public</user_identifier><response result="ok"><playtime>5106</playtime></response></UIC>
``` 

****

### 67 - SetPlayPreset
Description: TuneIn – Play preset

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetPlayPreset%3C/name%3E%3Cp%20type=%22dec%22%20name=%22presetindex%22%20val=%223%22/%3E%3Cp%20type=%22dec%22%20name=%22presettype%22%20val=%220%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetPlayPreset</name><p type="dec" name="presetindex" val="3"/><p type="dec" name="presettype" val="0"/>
```  

Response:  

```  
--- 
``` 

****

### 68 - SetRepeatMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetRepeatMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22repeatmode%22%20val=%22all%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetRepeatMode</name><p type="str" name="repeatmode" val="all"/>
```  

Response:  

```  
--- 
``` 

****

### 69 - SetRepeatMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetRepeatMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22repeatmode%22%20val=%22off%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetRepeatMode</name><p type="str" name="repeatmode" val="off"/>
```  

Response:  

```  
--- 
``` 

****

### 70 - SetRepeatMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetRepeatMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22repeatmode%22%20val=%22one%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetRepeatMode</name><p type="str" name="repeatmode" val="one"/>
```  

Response:  

```  
--- 
``` 

****

### 71 - SetSelectRadio
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/CPM?cmd=%3Cname%3ESetSelectRadio%3C/name%3E' 
```  
 Xml string decoded: 
```  
<name>SetSelectRadio</name>
```  

Response:  

```  
--- 
``` 

****

### 72 - SetShuffleMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetShuffleMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22shufflemode%22%20val=%22off%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetShuffleMode</name><p type="str" name="shufflemode" val="off"/>
```  

Response:  

```  
--- 
``` 

****

### 73 - SetShuffleMode
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetShuffleMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22shufflemode%22%20val=%22on%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetShuffleMode</name><p type="str" name="shufflemode" val="on"/>
```  

Response:  

```  
--- 
``` 

****

### 74 - SetSleepTimer
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetSleepTimer%3C/name%3E%3Cp%20type=%22str%22%20name=%22option%22%20val=%22off%22/%3E%3Cp%20type=%22dec%22%20name=%22sleeptime%22%20val=%22300%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetSleepTimer</name><p type="str" name="option" val="off"/><p type="dec" name="sleeptime" val="300"/>
```  

Response:  

```  
--- 
``` 

****

### 75 - SetSleepTimer
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetSleepTimer%3C/name%3E%3Cp%20type=%22str%22%20name=%22option%22%20val=%22pause%22/%3E%3Cp%20type=%22dec%22%20name=%22sleeptime%22%20val=%22300%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetSleepTimer</name><p type="str" name="option" val="pause"/><p type="dec" name="sleeptime" val="300"/>
```  

Response:  

```  
--- 
``` 

****

### 76 - SetSleepTimer
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetSleepTimer%3C/name%3E%3Cp%20type=%22str%22%20name=%22option%22%20val=%22start%22/%3E%3Cp%20type=%22dec%22%20name=%22sleeptime%22%20val=%22300%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetSleepTimer</name><p type="str" name="option" val="start"/><p type="dec" name="sleeptime" val="300"/>
```  

Response:  

```  
--- 
``` 

****

### 77 - SetSpeakerTime
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetSpeakerTime%3C/name%3E%3Cp%20type=%22dec%22%20name=%22year%22%20val=%222017%22/%3E%3Cp%20type=%22dec%22%20name=%22month%22%20val=%224%22/%3E%3Cp%20type=%22dec%22%20name=%22day%22%20val=%228%22/%3E%3Cp%20type=%22dec%22%20name=%22hour%22%20val=%2222%22/%3E%3Cp%20type=%22dec%22%20name=%22min%22%20val=%2248%22/%3E%3Cp%20type=%22dec%22%20name=%22sec%22%20val=%2254%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetSpeakerTime</name><p type="dec" name="year" val="2017"/><p type="dec" name="month" val="4"/><p type="dec" name="day" val="8"/><p type="dec" name="hour" val="22"/><p type="dec" name="min" val="48"/><p type="dec" name="sec" val="54"/>
```  

Response:  

```  
--- 
``` 

****

### 78 - SetSpkName
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetSpkName%3C/name%3E%3Cp%20type=%22cdata%22%20name=%22spkname%22%20val=%22empty%22%3E%3C![CDATA[[Samsung]%20R1]]%3E%3C/p%3E' 
```  
 Xml string decoded: 
```  
<name>SetSpkName</name><p type="cdata" name="spkname" val="empty"><![CDATA[[Samsung] R1]]></p>
```  

Response:  

```  
--- 
``` 

****

### 79 - SetVolume
Description: Volume = 4

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetVolume%3C/name%3E%3Cp%20type=%22dec%22%20name=%22volume%22%20val=%223%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetVolume</name><p type="dec" name="volume" val="3"/>
```  

Response:  

```  
--- 
``` 

****

### 80 - SetVolume
Description: Volume = 4

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetVolume%3C/name%3E%3Cp%20type=%22dec%22%20name=%22volume%22%20val=%224%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetVolume</name><p type="dec" name="volume" val="4"/>
```  

Response:  

```  
--- 
``` 

****

### 81 - SetVolume
Description: Volume = 5

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESetVolume%3C/name%3E%3Cp%20type=%22dec%22%20name=%22volume%22%20val=%225%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SetVolume</name><p type="dec" name="volume" val="5"/>
```  

Response:  

```  
--- 
``` 

****

### 82 - SpkInGroup
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3ESpkInGroup%3C/name%3E%3Cp%20type=%22str%22%20name=%22act%22%20val=%22select%22/%3E' 
```  
 Xml string decoded: 
```  
<name>SpkInGroup</name><p type="str" name="act" val="select"/>
```  

Response:  

```  
--- 
``` 

****

### 83 - SetMute
Description: Mute OFF

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetMute%3C/name%3E%3Cp%20type=%22str%22%20name=%22mute%22%20val=%22off%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetMute</name><p type="str" name="mute" val="off"/>
```  

Response:  

```  
--- 
``` 

****

### 84 - SetMute
Description: Mute ON

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetMute%3C/name%3E%3Cp%20type=%22str%22%20name=%22mute%22%20val=%22on%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetMute</name><p type="str" name="mute" val="on"/>
```  

Response:  

```  
--- 
``` 

****

### 85 - SetPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetPlaybackControl%3C/name%3E%3Cp%20type=%22str%22%20name=%22playbackcontrol%22%20val=%22pause%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetPlaybackControl</name><p type="str" name="playbackcontrol" val="pause"/>
```  

Response:  

```  
--- 
``` 

****

### 86 - SetPlaybackControl
Description: ---

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetPlaybackControl%3C/name%3E%3Cp%20type=%22str%22%20name=%22playbackcontrol%22%20val=%22resume%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetPlaybackControl</name><p type="str" name="playbackcontrol" val="resume"/>
```  

Response:  

```  
--- 
``` 

****

### 87 - SetTrickMode
Description: Next Song

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetTrickMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22trickmode%22%20val=%22next%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetTrickMode</name><p type="str" name="trickmode" val="next"/>
```  

Response:  

```  
--- 
``` 

****

### 88 - SetTrickMode
Description: Previous Song

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cpwron%3Eon%3C/pwron%3E%3Cname%3ESetTrickMode%3C/name%3E%3Cp%20type=%22str%22%20name=%22trickmode%22%20val=%22previous%22/%3E' 
```  
 Xml string decoded: 
```  
<pwron>on</pwron><name>SetTrickMode</name><p type="str" name="trickmode" val="previous"/>
```  

Response:  

```  
--- 
``` 

****

### 89 - GetDmsList
Description: List of DLNA server detected by the speaker

Example: 

```  
curl 'http://ip_speaker:55001/UIC?cmd=%3Cname%3EGetDmsList%3C%2Fname%3E%3Cp%20type%3D%22dec%22%20name%3D%22liststartindex%22%20val%3D%220%22%2F%3E%3Cp%20type%3D%22dec%22%20name%3D%22listcount%22%20val%3D%2220%22%2F%3E' 
```  
 Xml string decoded: 
```  
<name>GetDmsList</name><p type="dec" name="liststartindex" val="0"/><p type="dec" name="listcount" val="20"/>
```  

Response:  

```  
--- 
``` 

****


baclpt 2017/04/09