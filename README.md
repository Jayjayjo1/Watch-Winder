# 🚀 Project Name: [Watch Winder]

A watch winder to wind automatic watches while unworn to get them ready and working for you.

---

## 📌 Project Overview
* **Status:** In Progress / Prototype / Completed
* **Author(s):** Your Name
* **External Links:** [Link to CAD Folder (Drive/Fusion360)] | [Link to Component Datasheets]

Provide a brief paragraph describing the problem this project solves, how it works, and the general design choices you made.

---

## 🛠️ System Architecture & Specifications
### 1. Mechanical (CAD & 3D Printing)
* **Enclosure:** [e.g., 3D printed PLA, 15% infill, M3 heat-set inserts]
* **Key Components:** [e.g., Custom chassis, MG996R Servos]

### 2. Electrical & Electronics
* **Microcontroller:** [e.g., ESP32 WROOM / Arduino Nano]
* **Power Supply:** [e.g., 18650 Li-ion battery, 5V buck converter]
* **Sensors:** [e.g., MPU6050 Accelerometer, HC-SR04 Ultrasonic]

### 3. Firmware & Software
* **Language:** [e.g., C++ (Arduino IDE) / Python]
* **Key Libraries:** [e.g., Wire.h, WiFi.h]

---

## 📋 Bill of Materials (BOM)

| Component | Qty | Source / Link | Estimated Cost | Notes |
| :--- | :---: | :--- | :---: | :--- |
| ESP32 Development Board | 1 | [Amazon](https://amazon.com) | $7.00 | Main MCU |
| M3x10mm Button Head Screws | 12 | [Local Hardware] | $2.00 | For chassis assembly |
| 18650 Battery Shield | 1 | [AliExpress](https://aliexpress.com) | $3.50 | 5V and 3.3V regulation |

---

## ⚡ Setup & Installation
### Hardware Assembly
1. 3D print all chassis components located in the external CAD folder.
2. Melt the **M3 heat-set inserts** into the designated 4.0mm holes.
3. Mount the microcontroller using M3x6mm screws.

### Firmware Upload
1. Open the `/firmware` folder in the Arduino IDE.
2. Install the required libraries via the Library Manager.
3. Connect your board over USB, select the correct COM port, and press **Upload**.

---

## 📈 Testing & Future Adjustments
* [ ] Fix the weight distribution on the rear axis.
* [ ] Optimize battery consumption by introducing a deep-sleep cycle in code.
* [ ] Implement an OLED screen for real-time telemetry display.
