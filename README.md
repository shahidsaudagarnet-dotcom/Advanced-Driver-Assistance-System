# Advanced Driver Assistance System (ADAS) to Avoid Accidents

## Overview

This project presents an **Advanced Driver Assistance System (ADAS)** designed to reduce accidents at **T-junctions**, where limited visibility and conflicting traffic movements often result in collisions.

The system utilizes **ultrasonic sensors**, **RF communication modules**, and **Arduino-based controllers** to detect approaching vehicles and coordinate preventive actions. By monitoring traffic conditions and enabling communication between vehicles, the system improves situational awareness and helps avoid accidents through timely warnings and automatic intervention.

---

## Problem Statement

T-junctions are among the most accident-prone road intersections due to:

- Limited visibility
- Blind spots
- Complex traffic interactions
- Delayed driver response

Traditional driver awareness alone is often insufficient to prevent collisions in such scenarios.

---

## Objectives

- Detect vehicles approaching a T-junction.
- Monitor potential collision scenarios in real time.
- Enable communication between vehicles using RF technology.
- Provide alerts and preventive actions before collisions occur.
- Improve road safety at critical intersections.

---

## System Architecture

### Major Components

#### Transmitting Unit

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- RF Transmitter Module
- Vehicle Motor Controller

#### Receiving Unit

- Arduino UNO
- RF Receiver Module
- Vehicle Motor Controller
- LCD Display
- Piezo Buzzer

#### Roadside Infrastructure

- Ultrasonic Sensors positioned near T-junctions
- RF Communication Nodes
- Warning Display System

---

## Working Principle

1. Vehicle Detection
2. Data Processing
3. RF Communication
4. Collision Prediction
5. Safety Response

---

## Hardware Requirements

- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD Display
- Regulated Power Supply
- Transformer
- GSM Module
- Piezo Buzzer
- RF Module

---

## Software Requirements

- Arduino IDE
- Embedded C/C++

---

## Results

- Vehicle detection achieved successfully.
- RF communication established.
- Collision warnings generated.
- Improved T-junction safety demonstrated.

---

## Conclusion

The proposed ADAS system uses ultrasonic sensing and RF communication to detect collision risks at T-junctions and provide preventive actions. The solution is cost-effective, scalable, and improves road safety.

---

## Authors

- Adil
- Md Abrar Ahmed
- Md Haseeb Sufiyan
- Mohammed Shahid Saudagar
- Prof. Roopa Chanashetty

Department of Electronics and Communication Engineering  
PDA College of Engineering, Kalaburagi, India
