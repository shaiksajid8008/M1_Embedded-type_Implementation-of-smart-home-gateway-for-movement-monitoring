## Structural and behavioral
IFTTT is a web-based service by which we can create chains of conditional statements, called applets. Using these applets, we can send Emails, posts to Twitter, posts to Facebook, play music, SMS, notifications, etc. Here in this project, we are using IFTTT to send SMS notifications to the mobile phone when the system detects a fall.
# STEPS TO IFTTT
- To use the IFTTT sign in to your IFTTT account if you already have one or creating an account
- Now click on the documentation to get the key which will be used in our programming part.
- After that click on create 
- Next, search for webhooks and select it
- After clicking the webhooks, now you want to select “Receive a web request” and give an event name as per your wish. In my case, I have given fall detect
- if you want to play any song when the magnitude exceeds the thresh hold value, you can set any song to play by repeating these all step from the creating part but instead clicking Android SMS, you want to select Android Service, then you want to select play a specific song to play anysong as per your wish.
- After that click on Create Action
## Architecture Level
- ESP8266EX also integrates an enhanced version of Tensilica's L106 Diamond series 32-bit processor, with on-chip SRAM, besides the Wi-Fi functionalities.ESP8266EX is often integrated with external sensors and other application specific devices through its GPIOs; codes for such applications are provided in examples in the SDK. Espressif Systems Smart Connectivity Platform (ESCP) demonstrates sophisticated systemlevel features include fast sleep/wake context switching for energyefficient VolP,adaptive radio biasing.For low-power operation, advance signal processing, and spur cancellation and radio co-existence features for common cellular, Bluetooth,DDR,LVDS,LCD interference mitigation.
