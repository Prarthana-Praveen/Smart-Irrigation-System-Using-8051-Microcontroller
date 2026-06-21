# Smart Irrigation System Using 8051 Microcontroller

## Overview

The Smart Irrigation System is an embedded systems project designed to automate irrigation based on soil moisture and water availability. The system uses an AT89S52 (8051 family) microcontroller to monitor sensor inputs and control a water pump automatically.

The primary objective of this project is to conserve water, reduce manual effort, and protect irrigation pumps from dry-run damage.

---

## Problem Statement

Traditional irrigation methods often rely on manual monitoring, leading to:

* Water wastage due to over-irrigation
* Increased labour requirements
* Lack of real-time soil condition monitoring
* Pump damage caused by dry running

This project addresses these issues through an automated and low-cost irrigation solution.

---

## Features

* Automatic irrigation control
* Soil moisture monitoring
* Water level monitoring
* Dry-run motor protection
* Real-time status display using 16×2 LCD
* Dual power supply architecture (5V logic and 12V motor)

---

## Components Used

| Component               | Purpose                    |
| ----------------------- | -------------------------- |
| AT89S52 Microcontroller | Main controller            |
| Soil Moisture Sensor    | Detects soil condition     |
| Water Level Sensor      | Detects water availability |
| 16×2 LCD Display        | Displays system status     |
| Relay Module            | Controls pump switching    |
| 12V DC Water Pump       | Irrigation actuator        |
| 5V Power Supply         | Logic circuit power        |
| 12V Power Supply        | Pump power                 |

---

## Working Principle

1. The microcontroller continuously reads the soil moisture sensor.
2. If the soil is wet, the pump remains OFF.
3. If the soil is dry, the system checks the water level sensor.
4. If water is available, the pump turns ON.
5. If the tank is empty, the pump remains OFF to prevent dry-run damage.
6. The LCD displays the current status of the system.
7. The process repeats continuously at regular intervals.

---

## Logic Table

| Soil Condition | Water Available | Pump Status |
| -------------- | --------------- | ----------- |
| Wet            | Yes/No          | OFF         |
| Dry            | Yes             | ON          |
| Dry            | No              | OFF         |

---

## Applications

* Agricultural irrigation systems
* Home gardening
* Greenhouses
* Smart farming solutions
* Water conservation projects

---

## Future Enhancements

* IoT-based monitoring and control
* Mobile application integration
* Solar-powered operation
* Weather-based irrigation scheduling
* Cloud data logging and analytics

---
## Block Diagram
<img width="1402" height="787" alt="blockdiagram" src="https://github.com/user-attachments/assets/391bc1fc-67ac-4440-82e1-51bf40952139" />

---

## Project Photos

<img width="963" height="625" alt="IMG-20260618-WA0008" src="https://github.com/user-attachments/assets/02eed636-7ebc-44df-a3f2-010a82aca815" />
<img width="879" height="614" alt="IMG-20260618-WA0009" src="https://github.com/user-attachments/assets/8d73cc1a-b777-43de-ac01-2cb00e392949" />
<img width="899" height="625" alt="IMG-20260320-WA0035" src="https://github.com/user-attachments/assets/d4ca891c-d7d8-4666-a0fb-c83394425863" />

---
## Team Members

* Aryananda S
* Isac Reji
* Nivedita Vinay
* Prarthana Praveen

---

## Project Outcome

This project successfully demonstrates how embedded systems can be used to automate irrigation, improve water efficiency, reduce manual intervention, and support sustainable agricultural practices.

---

### Department of Electronics & Communication Engineering

### Academic Year 2024–25

