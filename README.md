Execution Videos:
1. https://youtube.com/shorts/GcznaPap2tc?si=TbEegLLsbRlQk1K4
2. https://youtube.com/shorts/EfAxiSUI5Mo?si=XBb93sHVLCXaDvzF
3. https://youtube.com/shorts/DxaJCATmgEs?si=_HFMfLFY-m1I-99E

**BLE-based Distance Estimation System**
**Objective** 
The primary objective of this team-based assignment is to develop a Bluetooth Low Energy (BLE) distance estimation system using ESP32 modules, where the distance between devices is calculated based on the signal strength (RSSI) and transmission power (txPower) values. This involves not only establishing BLE communication but also implementing a mathematical model to estimate real-world distances from signal characteristics.

**Significance**
This project holds educational significance in introducing students to real-world IoT system design by combining wireless communication, signal processing, and embedded system programming. It provides practical insights into how BLE technology is used in proximity-based applications such as indoor navigation, asset tracking, or smart access systems, thereby bridging theoretical concepts with hands-on implementation and performance analysis.

**Methodology**
The system is built by first establishing BLE communication between ESP32 devices, then modifying the client to read RSSI values from the server's advertising packets. Using a path-loss model, the client estimates the distance in real time, which is displayed on the serial monitor. Measurements are taken at various known distances and compared with estimated values through tables and bar charts for performance evaluation.

![Image](https://github.com/user-attachments/assets/ec1e70e7-d2f2-49ea-ac19-1c187b5a357e)
![Image](https://github.com/user-attachments/assets/8d431141-3221-4d74-94c2-e97338bdd54e)

**Table of results**
![Image](https://github.com/user-attachments/assets/0a3be339-746e-45c3-a140-5e34d32d7996)
