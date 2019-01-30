# Home Automation using Domoticz, motionEye and ESP8266

## Main Features:
  - Smart electrical heating management
  - Legacy wired alarm appliance go to Internet
  - Cameras and motion detection with motionEye 
  - Robust Domoticz implementation with two synchronized servers (cluster) 

## Architecture:
  - Domoticz High Availability Cluster : Synology Dz V3.5877 (Main) - Raspberry Dz V4.97 (Backup) - Node.js scripts
  - Alarm server : Raspberry - motionEye - iot_ALARM-SVR Node.js 
  - Sensors/Actuators : ESP8266 (Electrodragon IoT ESP8266 Relay Board and standalone ESP-12E) - Arduino sketchs

## Forum topics about:
  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=17032

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=21608

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=22436

  - http://www.domoticz.com/forum/viewtopic.php?f=38&t=23914

  - https://easydomoticz.com/forum/viewtopic.php?f=21&t=4798
