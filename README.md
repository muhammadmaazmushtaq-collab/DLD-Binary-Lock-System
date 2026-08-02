# 🔒 Digital Logic Binary Lock System

A hardware-based secure digital locking system designed entirely utilizing fundamental Digital Logic Design (DLD) principles. This project demonstrates a fail-safe security mechanism that operates purely on hardware logic without any microcontrollers or software programming. It acts as a security gateway, permitting access only upon the entry of a predefined 4-bit binary password ("1001").

## 🚀 Key Features
* **Hybrid Architecture:** Combines combinational logic for exact password validation and sequential logic for attempt tracking and memory.
* **Attempt Tracking System:** Utilizes a 74HC73 Dual J-K Flip-Flop as a counter to track failed attempts, visually displaying a countdown from 3 to 0 on a 7-segment display via a CD4511 BCD-to-7-Segment Decoder.
* **Automated Lockdown & Alarm:** If 0 attempts are reached, a 74HC32 (OR) gate freezes the flip-flop's inputs, preventing further attempts. Simultaneously, it activates a Red LED and a 5V Piezo Buzzer to signify system lockdown.
* **Transistor-Based Auto-Reset:** Employs an NPN Transistor (BC547) as an active-low electronic switch. Upon correct password entry, it automatically resets the attempt counter back to '3' without manual intervention.

## 🛠️ Components & Technologies Used
* **Simulation Tool:** Tinkercad / CircuitWizard
* **Logic Gates:** 74HC04 (NOT), 74HC08 (AND), 74HC32 (OR)
* **Sequential Components:** 74HC73 (Dual J-K Flip-Flop)
* **Display & Output:** CD4511 Decoder, 7-Segment Display, Piezo Buzzer, LEDs
* **Hardware Interfacing:** BC547 NPN Transistor, 4-position DIP switch

## 🔗 Live Simulation
* **Tinkercad Circuit:** [Click here to view live simulation](https://www.tinkercad.com/things/bmWxQptt3UQ-dld-binary-lock-system?sharecode=xjaH-aFAVpDa2kHtGMU-JK_1w7PQYypTRmuvLYitUX4)

## 👨‍💻 Project Contributors
* Muhammad Maaz Mushtaq (Cs251041)
* Shavez Yousaf (Cs251075)
* Abdul Rahim Shera (Cs251306)

## 📄 Project Documentation
For a detailed breakdown of the circuit design, logic diagram, block diagram, and real-world applications (such as ATM security and smart access control), please view the **Project Report PDF** included in this repository.
