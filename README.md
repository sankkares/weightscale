This project is a Smart IoT Weighing Scale that measures a user's weight and estimates their hydration status by analyzing weight changes over time. The system uses a load cell connected to an HX711 amplifier, which sends weight measurements to an ESP32 microcontroller. The ESP32 uploads the data to the cloud using Wi-Fi, enabling remote monitoring and analysis.

The collected data is stored on ThingSpeak, where trends are visualized through graphs. The system calculates a 3-day moving average and compares daily weight changes to identify possible dehydration or water retention. If a significant decrease in weight is detected, the system indicates Possible Dehydration; if there is a significant increase, it indicates Possible Water Retention. Otherwise, the hydration status is displayed as Normal.

A responsive web dashboard presents the current weight, historical trends, and hydration status, making it easy for users to monitor their health. This project combines embedded systems, IoT, cloud computing, and data analytics to provide an affordable and intelligent health monitoring solution suitable for homes, fitness centers, hospitals, and elderly care.

Technologies Used:

ESP32
Load Cell
HX711 Amplifier
ThingSpeak Cloud
HTML, CSS, JavaScript (Dashboard)
Chart.js
Arduino IDE
