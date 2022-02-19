# pihole-stats
pihole stats on Adafruit ESP32-S2 TFT Feather

Created for the Adafruit ESP32-S2 TFT Feather board. Displays a few stats from the pihole api. 

change the hosts and SSID/PASS to connect to your Wifi and Pihole servers. 

const char* host         = "192.168.0.1";
// uncomment for second host
//const char* host2        = "192.168.0.2";
const char* ssid         = "SSIS";
const char* password     = "PASS";

Display has a handy background to separate the stats. It's really not that exciting, just something for me to learn ESP32. 

![image](https://user-images.githubusercontent.com/882893/154817802-dacda236-f7d1-46ef-ae64-1e0fe96ff080.png)
