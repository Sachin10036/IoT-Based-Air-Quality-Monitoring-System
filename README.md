# AirGuard 360: IoT-Based Air Quality Monitoring System

Table of Contents

Introduction <br />
Features <br />
Components <br />
Usage <br />
System Architecture <br />
Code Explanation <br />
Data Visualization <br />
Future Enhancement <br />


Introduction: <br />
AirGuard 360 is an innovative IoT-based air quality monitoring system designed to provide real-time monitoring of environmental conditions, including temperature, humidity, and gas concentrations. The system uses sensors connected to a NodeMCU ESP8266 microcontroller to gather data and upload it to cloud platforms like Blynk and ThingSpeak for visualization and analysis.

Features: <br />
Real-time Monitoring: Continuously tracks temperature, humidity, and gas concentrations.<br />
Cloud Integration: Uploads data to Blynk and ThingSpeak for remote monitoring and analysis.<br />
Alerts: Provides visual and auditory alerts for poor air quality.<br />
User-friendly Interface: Accessible via mobile app and web dashboard.<br />
Data Logging: Supports historical data analysis and trend detection.<br />

Components: <br />
NodeMCU ESP8266: Microcontroller with WiFi capability.<br />
DHT11: Sensor for temperature and humidity.<br />
MQ135: Sensor for gas concentrations.<br />
LCD: Displays real-time data.<br />
Buzzer and LED: Alerts for poor air quality.<br />
Blynk and ThingSpeak: Cloud platforms for data visualization.<br />

Usage: <br />
Power On: Connect the sensors and power up the NodeMCU.<br />
Monitor: Use the Blynk app or web dashboard to monitor real-time data.<br />
Alerts: The system will trigger LED and buzzer alerts if air quality exceeds the threshold.<br />
Analyze Data: View and analyze data trends on ThingSpeak.<br />

System Architecture: <br />
Sensors: DHT11 and MQ135 gather environmental data.<br />
NodeMCU ESP8266: Collects sensor data and uploads it to the cloud.<br />
Cloud Platforms: Blynk and ThingSpeak store and visualize data.<br />
Alerts: LED and buzzer notify users of poor air quality.<br />

Code Explanation: <br />
The project code is divided into several sections: <br />

WiFi and Cloud Setup: Establishes connection to WiFi and initializes Blynk and ThingSpeak.<br />
Sensor Reading: Collects data from DHT11 and MQ135 sensors.<br />
Data Upload: Sends data to Blynk and ThingSpeak for visualization.<br />
Alerts: Triggers LED and buzzer if air quality is poor.<br />

Data Visualization: <br />
Blynk Platform: Provides real-time dashboard via mobile app and web interface.<br />
ThingSpeak: Offers tools for advanced data visualization and historical data analysis.<br />

Future Enhancements: <br />
Expand Sensor Types: Integrate additional sensors for specific pollutants.<br />
Increase Coverage: Expand monitoring to cover larger areas.<br />
Enhance Alerts: Implement advanced notification systems (SMS, email).<br />
