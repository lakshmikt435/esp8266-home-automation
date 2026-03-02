🌐 ESP8266 HTTP Client using Arduino

This project demonstrates how to interface an ESP8266 WiFi module with an Arduino to establish internet connectivity and perform an HTTP request.
The system connects to a WiFi network, establishes a TCP connection with a remote web server, sends an HTTP GET request, and prints the received response via serial monitor.
This project serves as a foundational implementation for IoT and home automation systems.

📌 PROJECT OVERVIEW

The program performs the following steps:
Resets the ESP8266 module
Initializes serial communication
Connects to a WiFi network
Obtains an IP address
Establishes a TCP connection with a web server
Sends an HTTP GET request
Receives and prints the HTTP response
Closes the connection

🛠 TECHNOLOGIES USED

Arduino
ESP8266 WiFi Module
Arduino C++
TCP/IP Protocol
HTTP Protocol
SoftwareSerial Library


🚀 How to Use

Open the .ino file in Arduino IDE
Install required ESP8266 library if needed
Update the WiFi SSID and Password in the code
Connect ESP8266 to Arduino using SoftwareSerial pins
Upload the code
Open Serial Monitor at 9600 baud rate
