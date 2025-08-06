# Real-Time-Driver-Drowsiness-And-Alcohol-Detection-System-For-Accident-Prevention
This project is a real-time driver safety system that detects drowsiness and alcohol consumption using sensors. If alcohol is detected through a gas sensor or signs of drowsiness like prolonged eye closure or head movement are observed via sensors, it triggers alerts or stops the vehicle to prevent accidents.
# Real-Time Driver Drowsiness and Alcohol Detection System

## Overview

This project aims to enhance road safety by detecting driver drowsiness and alcohol consumption in real time using sensors. When drowsiness or alcohol is detected, the system activates alerts or stops the vehicle to prevent accidents.

## Features

- Real-time alcohol detection using an MQ3 gas sensor  
- Drowsiness detection using IR sensor (eye blink detection)  
- Automatic alert system (buzzer/LED) on detection  
- Vehicle ignition control (optional relay module)  
- Compact and low-cost hardware implementation  

## Components Used

- Arduino UNO / NodeMCU / Raspberry Pi   
- MQ3 Alcohol Sensor  
- IR Sensor for eye blink detection  
- Buzzer for alert system  
- Relay Module for vehicle engine control (optional)  
- Power supply or battery pack  
- Jumper wires and breadboard  

## Working Principle

The system works by continuously monitoring the driver’s condition using alcohol and drowsiness detection sensors. It ensures safety by alerting or stopping the vehicle based on sensor inputs.

### 1. Alcohol Detection

- An **MQ3 gas sensor** is used to detect the presence of alcohol in the driver's breath.  
- When the driver exhales near the sensor, it measures the concentration of alcohol vapors.  
- If the detected value exceeds a predefined safety threshold, the system:  
  - Activates a **buzzer** or **LED alert**  
  - Optionally **disables the vehicle ignition** using a relay module to prevent driving under influence.  

### 2. Drowsiness Detection

- An **IR sensor** is placed near the driver’s eyes to detect eye blink patterns.  
- If the driver's eyes remain closed for a prolonged period (indicating drowsiness), the system:  
  - Triggers a **buzzer alarm** to alert the driver.  
  - Optionally, the system can **disable the engine** to stop the vehicle safely.  

### 3. Alert System

- A **buzzer and LED** system provides real-time alerts to the driver.  
- Alerts are triggered when:  
  - Alcohol is detected  
  - Drowsiness is detected  
- These alerts aim to wake the driver or prevent them from driving under unsafe conditions.  

### 4. Vehicle Control (Optional)

- A **relay module** can be connected to the ignition system of the vehicle.  
- When a risk is detected (alcohol or drowsiness), the relay cuts off the ignition, preventing the vehicle from starting or continuing.  

## Installation

1. Connect the sensors to the Arduino as per the circuit diagram.  
2. Upload the Arduino code to the board using the Arduino IDE.  
3. Power the system and test each sensor individually.  
4. Integrate the system with the vehicle model or simulation.  

## Circuit Diagram

![WhatsApp Image 2025-08-06 at 12 00 48_dce21ea3](https://github.com/user-attachments/assets/48f28424-ac70-4db8-acca-78586fcde688)



## How to Use

1. Power on the system.  
2. The sensors will start monitoring automatically.  
3. If alcohol is detected or the driver appears drowsy, a buzzer will sound.  
4. Optionally, the engine system will be disabled using a relay.
5. <img width="3007" height="2549" alt="image" src="https://github.com/user-attachments/assets/f00eceda-063a-4817-a0df-91622577b3c3" />
 

## Code

 **[View Arduino Code Here]("C:\Users\Chaitanya Jenne\Documents\Arduino\sketch_aug6b\sketch_aug6b.ino")**  


## Applications

- Cars and commercial vehicles  
- Driver monitoring in transport and logistics  
- Safety enhancement systems in smart vehicles  

## Future Improvements

- GSM module for sending SMS alerts to emergency contacts  
- GPS integration for location tracking  
- AI-based drowsiness detection (if camera support is added later)  

## License

This project is open-source and free to use for educational and research purposes.

## Contact

**Name:** Jenne Chaitanya  
**Email:**jennechaitanya@gmail.com  

