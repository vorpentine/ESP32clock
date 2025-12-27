Welcome to the page of my (W.I.P.) project called 

<img src="https://github.com/telepath9/ESPclock/blob/54c39c18d9204351de640fb42218651ce3664671/pics/newfont.png" alt="Alt Text" width="100%" height="100%">

which basically is a smart clock that connects to wifi to get the time. 
It relies on a ESP8266 (devboard: Wemos D1 mini, soon i will make it work also for ESP32).

At the actual state, it uses hardcoded wifi credentials (that the user must insert in the firmware before compiling it),
then, it retrieves the time (hour and minutes) from an NTP server.

After it has synced with NTP server for the first time, it can work also in OFFLINE mode, thanks to the RTC module, which can track the time without any connection to internet.

<img src="https://github.com/telepath9/ESPclock/blob/6b2b2224a42deda354a8a7220dcf724643eb9c2e/pics/pic1.jpg" alt="Alt Text" width="100%" height="100%">

🔜In the next release, the v2.0, user won't need to use hardcoded credentials anymore, plus there would be some other features so, 
stay tuned...

<img src="https://github.com/telepath9/ESPclock/blob/fc8962a5a3ac24c1769f0fc2af601251f94913a0/pics/v2.0_new.jpg" alt="Alt Text" width="100%" height="100%">
