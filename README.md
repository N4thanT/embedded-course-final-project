# embedded-course-final-project


Purpose & Goal: Display current electricity prices in an analouge way.

Tools and methodologies: 
    - ESP32 (or ESP32-C3 mini, but mine refused to connect to wifi, or ESP32-2432S028 for both screen and microcontroller, but didn't have the right cable for that), 
    - WS2812,
    - platformIO, 
    - nps API, 
    - ArduinoJson, 
    - HTTP GET request, 
    - NTP sync, 
    - DHCP(?).

Related notes:
	RED - prices are high
	YELLOW - prices are okay 
	GREEN - prices are low
	BLUE - error

Progress notes:
    "Everything that can go wrong, will go wrong."