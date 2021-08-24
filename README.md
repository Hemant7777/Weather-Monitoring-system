# Weather-Monitoring-system
Data(temperature &amp; Humidity) collect from the DHT-11 sensor
Sent the data to a remote server(thingspeak)
Live data monitoring 
Deep sleep mode for esp32 Time and Date collect from NTPC Server
Store data in My SQL Database


Specila Note...............
if you use nowmal NTPC library 
you got the date format error .... getFormattedDate()

to avoid this error delete NTPC library  and instal NTPClient-master Library
