# Parking-Nielit-campus
IoT Smart Parking System — ESP32 + LoRa 433MHz + Adafruit IO + Real-time slot booking via web
IoT Smart Parking System is a real-time IoT-based smart parking system built 
using two ESP32 microcontrollers communicating over LoRa 
433MHz wireless. Drivers can view live slot availability and 
book a parking slot from any browser using this website.

Features:
- Live slot status (FREE / OCCUPIED / RESERVED)
- Driver slot booking with token generation
- Remote gate control via Adafruit IO dashboard
- LoRa 433MHz wireless communication (1km range)
- Real-time data via Adafruit IO MQTT
- Booking persistence across page refreshes

Hardware: ESP32 + HC-SR04 + Servo + LoRa SX1278 + OLED
Cloud: Adafruit IO + GitHub Pages
