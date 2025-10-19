# Smart Convenient Store Model Using Raspberry Pi 4

### Course Project: *Microprocessors and Microcontrollers (INS314802)*  
**Vietnam National University – International School (VNUIS)**  
**Semester:** Fall 2024 – Final Project  
**Score:** 9.5 / 10  

---

## Project Members
- **Pham Van Phuong** – Team Leader (40%)  
- **Nguyen Khac Long** – Member (40%)
- **Vu Duc Hung** – Member (20%)

---

## Description
This project demonstrates the **design and development of a smart convenience store model** using **Raspberry Pi 4**, integrated with **RFID technology** for access control, payment automation, and real-time database management.  

The system combines **hardware modules** (RFID reader, servo barrier, LCD display) with a **full-stack web application** (ReactJS + NodeJS + MySQL) to simulate a **cashless and automated retail environment**.  
Customers can authenticate using RFID cards, select products on a web interface, and automatically complete payments. The Raspberry Pi manages both hardware control and database communication, while the web server allows administrators to monitor transactions and operations remotely.

---

## Objectives
1. Build a **smart, low-cost, and automated convenience store** prototype.  
2. Integrate **hardware and software** for real-time management.  
3. Enable **RFID-based authentication and cashless payment**.  
4. Create a **centralized dashboard** for admin monitoring.  
5. Apply **IoT and microcomputer technology** to smart retail solutions.  

---

## System Overview

### Hardware Components
| Component | Function |
|------------|-----------|
| **Raspberry Pi 4** | Central control and data processing unit |
| **RC522 RFID Reader** | Scans RFID tags for authentication |
| **RFID Cards** | Unique customer identification |
| **I2C LCD Display** | Displays transaction and user messages |
| **Servo Barrier** | Opens/closes automatically for entry and exit |
| **Power Supply (5V DC)** | Provides power for all connected modules |

---

### Software Stack
| Layer | Technology |
|-------|-------------|
| **Frontend** | React + TypeScript + Vite |
| **Backend** | NodeJS + ExpressJS |
| **Database** | MySQL |
| **Hardware Interface** | Python (RFID, LCD, Servo) |
| **Communication** | RESTful API between Python ↔ NodeJS ↔ ReactJS |

---

##  Repository Structure
smart-convenient-store-rpi4/
├── code/
│ ├── client/my-react-app/ # ReactJS frontend
│ ├── server/ # NodeJS backend
│ └── rfid.py # Python script (RFID, LCD, Servo control)
├── image/ # Circuit diagrams & prototype photos
├── smart-convenient-store-rpi4.pdf # Full project report
└── README.md # This file


---

## System Workflow
1. **RFID Card Scan:** Raspberry Pi authenticates user data via MySQL.  
2. **Access Granted:** Servo barrier opens, LCD shows welcome message.  
3. **Shopping Interface:** Customer selects products on React-based web app.  
4. **Checkout Process:** NodeJS backend handles payment and updates database.  
5. **Payment Confirmation:** Barrier opens again for exit.  
6. **Admin Dashboard:** Displays transactions, customers, and product logs in real time.

---

## Methodology
- **RFID Authentication:** Python + RC522 for user validation.  
- **Backend (NodeJS + MySQL):** Handles transactions, payments, and data APIs.  
- **Frontend (ReactJS):** Customer shopping interface and admin dashboard.  
- **LCD Display & Servo:** Controlled through GPIO pins on Raspberry Pi.  
- **Data Synchronization:** Real-time RESTful communication between hardware, backend, and web UI.

---  

**🎥 Demo Video:** [Watch on Google Drive](https://drive.google.com/file/d/1WfGedNuDOvaQmCwx1YG8U2nXw76zbecG/view?usp=sharing)  
**💻 Source Code:** [View Repository](https://github.com/LongNk0702/RaspberryPi4---Smart-convenient-store---fullstack)


---

## License
MIT License © 2025 – Group 1, VNUIS  
Developed for academic and research purposes.

