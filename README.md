# 🔒 Digital Logic Binary Lock System

A hardware-based secure digital locking system designed entirely utilizing fundamental Digital Logic Design (DLD) principles[cite: 2]. This project demonstrates a fail-safe security mechanism that operates purely on hardware logic without any microcontrollers or software programming[cite: 2]. It acts as a security gateway, permitting access only upon the entry of a predefined 4-bit binary password ("1001")[cite: 2].

## 🚀 Key Features
* **Hybrid Architecture:** Combines combinational logic for exact password validation and sequential logic for attempt tracking and memory[cite: 2].
* **Attempt Tracking System:** Utilizes a 74HC73 Dual J-K Flip-Flop as a counter to track failed attempts, visually displaying a countdown from 3 to 0 on a 7-segment display via a CD4511 BCD-to-7-Segment Decoder[cite: 2].
* **Automated Lockdown & Alarm:** If 0 attempts are reached, a 74HC32 (OR) gate freezes the flip-flop's inputs, preventing further attempts[cite: 2]. Simultaneously, it activates a Red LED and a 5V Piezo Buzzer to signify system lockdown[cite: 2].
* **Transistor-Based Auto-Reset:** Employs an NPN Transistor (BC547) as an active-low electronic switch[cite: 2]. Upon correct password entry, it automatically resets the attempt counter back to '3' without manual intervention[cite: 2].

## 🛠️ Components & Technologies Used
* **Simulation Tool:** Tinkercad / CircuitWizard[cite: 2]
* **Logic Gates:** 74HC04 (NOT), 74HC08 (AND), 74HC32 (OR)[cite: 2]
* **Sequential Components:** 74HC73 (Dual J-K Flip-Flop)[cite: 2]
* **Display & Output:** CD4511 Decoder, 7-Segment Display, Piezo Buzzer, LEDs[cite: 2]
* **Hardware Interfacing:** BC547 NPN Transistor, 4-position DIP switch[cite: 2]

## 👨‍💻 Project Contributors
* Muhammad Maaz Mushtaq[cite: 2]
* Shavez Yousaf[cite: 2]
* Abdul Rahim Shera[cite: 2]
## 🔗 Live Simulation
* **Tinkercad Circuit:** [Click here to view live simulation] ( https://www.tinkercad.com/things/bmWxQptt3UQ-dld-binary-lock-system?sharecode=xjaH-aFAVpDa2kHtGMU-JK_1w7PQYypTRmuvLYitUX4 )
## 📄 Project Documentation
For a detailed breakdown of the circuit design, logic diagram, block diagram, and real-world applications (such as ATM security and smart access control), please view the **Project Report PDF** included in this repository[cite: 2].
