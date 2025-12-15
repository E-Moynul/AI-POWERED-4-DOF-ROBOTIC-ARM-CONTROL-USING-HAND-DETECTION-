### **HARDWARE REQUIREMENTS**

**1. Main Electronics**
* **Microcontroller:** Arduino Uno R3 (with USB Cable Type A-to-B)
* **Power Supply:** 5V DC Power Adapter (Min 2A, recommended 3A for stability)
* **Power Connector:** DC Female Power Jack Adapter (with screw terminals) OR Breadboard Power Supply Module

**2. Actuators (Motors)**
* **Micro Servos (x4):** SG90 (9g Servo) — *For Base, Shoulder, Elbow and Gripper*

**3. Mechanical Parts**
* **Frame Kit:** 4-DOF Robot Arm Acrylic Chassis Kit "MeArm"
* **Fasteners:** Set of M3 Screws, Nuts, and Spacers

**4. Circuit & Connections**
* **Breadboard:** Mini Breadboard (170 tie-points) or Half-size Breadboard
* **Jumper Wires:**
    * Male-to-Male (M-M) bundle
    * Male-to-Female (M-F) bundle

**5. Vision Input**
* **Camera:** Laptop's built-in camera
* **Computer:** Laptop

---

### **SOFTWARE REQUIREMENTS**

**1. Development Environment (IDE)**
* **Arduino IDE:** Version 1.8.x or 2.x (To upload code to the Arduino)
* **Python Code Editor:** Sublime Text (To run the CV script)

**2. Programming Languages & Runtimes**
* **Python:** Version 3.11
* **C++:** (Used natively within Arduino IDE)

**3. Python Libraries (Dependencies)**
* `opencv-python` (For image processing)
* `mediapipe` (For hand tracking)
* `pyserial` (For communication with Arduino)

**4. Arduino Libraries**
* `Servo.h`

**5. Drivers**
* **USB-Serial Driver:** CH340 or CP210x Driver
