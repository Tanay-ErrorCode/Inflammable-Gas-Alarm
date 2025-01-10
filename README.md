# Inflammable-Gas-Alarm-IoT

This project is a gas leakage alarm system designed to detect and respond to dangerous gas levels. It integrates various hardware components to ensure functionality and works seamlessly with an Android app for monitoring and control.

## Hardware Components and Their Functions

1. **ESP32 Microcontroller**  
   - **Function:** Serves as the brain of the system, handling sensor data, Wi-Fi connectivity, and communication with Firebase.

2. **Gas Sensor (MQ2)**  
   - **Function:** Detects gas concentration in the air and sends analog signals to the ESP32.

3. **Buzzer**  
   - **Function:** Alerts users with an audible alarm when gas levels exceed a safe threshold.

6. **OLED Display (SSD1306)**  
   - **Function:** Displays real-time sensor data, Wi-Fi connection status, and system information.

7. **EEPROM (Built-in ESP32)**  
   - **Function:** Stores device and Wi-Fi credentials persistently, allowing the system to reconnect without reconfiguration.

8. **LEDs**
   - **Function:** Used to simulate the working of the external siren and fan.
     
## Features  

This project uses smart technology to monitor gas levels in real-time and ensures safety by automatically triggering alarms, fans, and sirens in case of a gas leak. It also integrates with a smartphone app, allowing users to control these safety measures remotely. The system operates in two modes: "AUTOMATIC" and "MANUAL." In automatic mode, it handles all safety actions like turning on fans and alarms upon detecting a leak. Alternatively, users can switch to manual mode if they prefer to manage these actions themselves. The goal is to provide an accessible and reliable solution for enhancing safety at home.

## Android App Integration

This system works with an Android app to:
- Monitor real-time gas levels.
- Receive alerts in case of emergencies.
- Remotely control the exhaust fan and siren.


## Circuit Diagram

Below is the circuit diagram illustrating the hardware setup of the project. It shows the connections between the ESP32, gas sensor, buzzer, OLED display, and other components.

![diagram](https://github.com/user-attachments/assets/07d68cf8-6faa-4305-bd54-29c6715fa3dd)


---

## You can watch the detailed video <a href="https://www.youtube.com/watch?v=ScOWkRvkewk" target="_blank">here</a>.

