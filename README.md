# Smart_Buffer_Stock_Solution

This system is made as a solution to one of the problem statements (VM742) in the Smart India Hackathon 2022 and is aimed to suppliment the growing investments of the Indian Government towards Buffer Stocks in India. This system monitors the amount of capacity used in given Buffer Stocks at various locations on a dashboard. It also provides a rough estimate of the weight of the stocked food.

### Description:
- Each buffer stock location must be equipped with a microcontroller such as an ESP32 along with an internet connection. The logic of the microcontroller can be found in main_Logic.ino.
- The microcontroller measures the sensor values and uploads it to dweet.io.
- Freeboard.io gets this data from dweet.io, applies calculations to obtain Percentage of capacity used, weight and outputs a nice dashboard.
- The configuration for Freeboard is in dashboard.json


### Requirements:
- ESP32 Microcontroller
- SR-HC04 Ultrasonic Distance Sensor(s)
- HC-SR04 Ultrasonic Distance Sensor(s)
- RGB LED(s)
- A Wi-Fi Connection
- A 3.3V Power Supply
