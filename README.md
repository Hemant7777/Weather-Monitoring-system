# Weather-Monitoring-system
Data(temperature &amp; Humidity) collect from the DHT-11 sensor
Sent the data to a remote server(thingspeak)
Live data monitoring 
Deep sleep mode for esp32 Time and Date collect from NTPC Server
Store data in My SQL Database


Specila Note...............
if you use nowmal NTPC library 
you got the date format error .... getFormattedDate()

To Avoid this ERROR
The easiest way to get date and time from an NTP server is using an NTP Client library. For that we’ll be using the NTP Client library forked by Taranais. Follow the next steps to install this library in your Arduino IDE:

1. Delete NTPC library 
2. Click here( https://github.com/taranais/NTPClient) to download the NTP Client library. You should have a .zip folder in your Downloads
3. Unzip the .zip folder and you should get NTPClient-master folder
4. Rename your folder from NTPClient-master to NTPClient
5. Move the NTPClient folder to your Arduino IDE installation libraries folder
6. Finally, re-open your Arduino IDE

