 ESP32-web-streaming-camera-face-detection-telegram-alert-
  Door Security Camera
An ESP32-CAM based smart door camera that streams live video, detects faces, and sends photo alerts to your phone through Telegram.
   Features : 
Live MJPEG streaming over Wi-Fi, viewable from any browser on the local network
On-device face detection running directly on the ESP32-CAM
Telegram notifications that send a photo whenever a face is detected, with a 4-second cooldown to avoid spam
Remote control via Telegram bot commands (e.g. request a photo on demand)
Dedicated FreeRTOS task for Telegram, so networking never blocks video streaming

  Hardware :
ESP32-CAM (AI-Thinker)
FTDI programmer / USB-serial adapter
5V power supply
(add any extras: PIR sensor, LED, case, etc.)

  Software and Libraries
Arduino IDE
ESP32 board package v2.0.17 (see the note below)
(add your Telegram library, e.g. UniversalTelegramBot, ArduinoJson)

⚠️⚠️⚠️ Important: use ESP32 core 2.0.17. Newer versions removed face detection support.


![image alt](https://github.com/matyos370/ESP32-web-streaming-camera-face-detection-telegram-alert-/blob/main/ESP32-CAM%20Door%20Security%20Hardware%20Guide.png?raw=true)
![image alt](https://github.com/matyos370/ESP32-web-streaming-camera-face-detection-telegram-alert-/blob/main/ESP32-CAM%20Video%20Streaming%20Guide.png?raw=true)
![image alt](https://github.com/matyos370/ESP32-web-streaming-camera-face-detection-telegram-alert-/blob/main/ESP32-CAM%20Face%20Detection%20Infographic.png?raw=true)
![image alt](https://github.com/matyos370/ESP32-web-streaming-camera-face-detection-telegram-alert-/blob/main/Telegram%20Integration%20and%20Face%20Detection%20Alerts.png?raw=true)
