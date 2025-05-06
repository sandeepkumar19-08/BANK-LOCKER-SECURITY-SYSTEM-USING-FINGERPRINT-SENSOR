# Bank Locker Security System Using Fingerprint Sensor (LPC2148)

A secure bank locker access control system developed using the LPC2148 ARM7 microcontroller and a fingerprint sensor. This project uses biometric authentication to ensure only authorized users can access the locker.

## 🔐 Overview

This embedded system authenticates users via their fingerprint using a biometric sensor module. Once a valid fingerprint is detected, a locker is unlocked via a servo motor or solenoid. Unauthorized access attempts can trigger a buzzer and can be logged or alerted via GSM.

## ⚙️ Platform

- **Microcontroller:** LPC2148 (ARM7TDMI-S based)
- **IDE:** Keil uVision
- **Programming Tool:** Flash Magic
- **Language:** Embedded C

## 📦 Features

- Fingerprint-based authentication
- Locker control via motor or solenoid
- LCD interface for user feedback
- Buzzer for unauthorized access alert
- Expandable with GSM module for SMS alerts

## 🛠️ Hardware Components

- LPC2148 ARM7 Development Board
- R305 Fingerprint Sensor (or compatible)
- 16x2 LCD Display
- Servo Motor or Electromagnetic Lock
- Buzzer
- GSM Module (SIM800L or similar) *(optional)*
- Power Supply (5V regulated)
- Breadboard and Jumper Wires
