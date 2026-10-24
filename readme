# ♻️ Smart Waste Segregation System

<h1 align="center">Smart Waste Segregation System</h1>

<p align="center">
  <em>An ESP32-based embedded system for automated classification and segregation of wet, dry, and metallic waste.</em>
</p>

<p align="center">
  <img alt="ESP32" src="https://img.shields.io/badge/Controller-ESP32-blue?logo=espressif&logoColor=white">
  <img alt="Language" src="https://img.shields.io/badge/Language-Embedded%20C%2FC%2B%2B-orange">
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Arduino%20IDE-teal?logo=arduino&logoColor=white">
  <img alt="Domain" src="https://img.shields.io/badge/Domain-Embedded%20Systems-green">
  <img alt="Project" src="https://img.shields.io/badge/Project-IoT%20Prototype-purple">
</p>

---

## 📖 About the Project

The **Smart Waste Segregation System** is an embedded systems project designed to automate the classification of waste into three categories: **wet, dry, and metallic**.

Traditional waste segregation often depends on manual sorting, which can be time-consuming and inconsistent. This project explores a sensor-based approach using an ESP32 microcontroller to detect waste properties and control a servo motor to direct waste toward the appropriate compartment.

The system integrates an infrared (IR) sensor, a moisture sensor, and an inductive proximity sensor. The ESP32 processes the sensor inputs using embedded control logic and operates the servo mechanism according to the detected waste category.

The project demonstrates practical applications of **microcontroller programming, sensor interfacing, actuator control, GPIO operations, and embedded system integration**.

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔍 **Object Detection** | IR sensor detects the presence of an object |
| 💧 **Moisture Detection** | Moisture sensor helps identify wet waste |
| 🔩 **Metal Detection** | Inductive proximity sensor detects metallic objects |
| 🧠 **Embedded Control Logic** | ESP32 processes sensor inputs to determine the waste category |
| ⚙️ **Automated Segregation** | Servo motor directs waste toward the selected compartment |
| ♻️ **Three Waste Categories** | Designed for wet, dry, and metallic waste |
| 🔌 **Hardware Integration** | Combines sensors, a microcontroller, and an actuator |
| 🧪 **Prototype-Based Design** | Suitable for embedded systems learning and waste-management demonstrations |

---

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| **ESP32 Development Board** | Main microcontroller for sensor processing and control |
| **IR Sensor** | Detects the presence of waste |
| **Moisture Sensor** | Measures moisture-related properties of the waste |
| **Inductive Proximity Sensor** | Detects metallic objects |
| **Servo Motor (SG90/MG90S)** | Controls the waste-diversion mechanism |
| **5V Power Supply** | Supplies power to compatible components |
| **Voltage Regulation** | Provides appropriate voltage where required |
| **Connecting Wires** | Establish electrical connections between components |
| **Waste Compartments** | Collect the segregated waste categories |

For detailed component information, refer to `Components.md` if it is included in the repository.

---

## 💻 Software & Development Tools

| Technology | Purpose |
|---|---|
| **Embedded C/C++** | Implements the control logic |
| **Arduino IDE** | Code development and firmware upload |
| **ESP32 Arduino Core** | Provides ESP32 support for the Arduino development environment |
| **Wokwi** | Circuit and firmware simulation, where applicable |
| **GPIO** | Interfaces sensors and actuators with the ESP32 |
| **PWM / Servo Control** | Controls the servo motor position |

---

## ⚙️ Working Principle

The system follows a sensor-based detection and actuation sequence.

1. **Object Detection:** The IR sensor detects waste entering the input area.
2. **Moisture Measurement:** The moisture sensor provides readings used to identify wet waste.
3. **Metal Detection:** The inductive proximity sensor checks for metallic material.
4. **Signal Processing:** The ESP32 reads the sensor inputs and evaluates the programmed conditions.
5. **Category Selection:** The control logic selects the appropriate waste category based on the sensor readings.
6. **Servo Actuation:** The servo motor moves to the corresponding position.
7. **Waste Segregation:** The waste is directed toward the selected compartment.

The classification accuracy depends on sensor calibration, waste properties, sensor placement, and the implemented decision logic.

---

## 🏗️ System Architecture

The system can be divided into three functional stages:

| Stage | Components | Responsibility |
|---|---|---|
| **Input Layer** | IR, moisture, and inductive proximity sensors | Detects object presence and relevant material properties |
| **Processing Layer** | ESP32 microcontroller | Reads sensor inputs and evaluates classification conditions |
| **Output Layer** | Servo motor and waste compartments | Directs the detected waste toward the selected category |

### System Flow

```text
Waste Input
    |
    v
IR Object Detection
    |
    v
Sensor Readings
(Moisture + Metal Detection)
    |
    v
ESP32 Control Logic
    |
    v
Waste Category Selection
    |
    v
Servo Motor Actuation
    |
    v
Selected Waste Compartment
```

---

## 📁 Recommended Project Structure

```text
Smart-Waste-Segregation-System/
│
├── README.md
├── .gitignore
├── LICENSE
│
├── src/
│   └── SmartWasteSegregation.ino
│
├── docs/
│   ├── Components.md
│   ├── Working_Principle.md
│   └── Circuit_Connections.md
│
├── screenshots/
│   ├── system-overview.png
│   └── circuit-diagram.png
│
└── simulation/
    └── wokwi-project-link.md
```

*This is a suggested structure. Keep your actual source filenames and folders, and create only the documentation and asset files you intend to maintain.*

---

## 🚀 Getting Started

### 1. Requirements

- ESP32 development board
- IR sensor
- Moisture sensor
- Inductive proximity sensor compatible with the interface circuitry
- Servo motor
- Appropriate power supply and connecting wires
- Arduino IDE with ESP32 board support installed

### 2. Open the Project

Open your Arduino source file in Arduino IDE. Use the actual `.ino` filename available in your repository.

### 3. Configure the Hardware

Connect the sensors and servo motor to the GPIO pins specified in your source code. Verify the operating voltage and signal levels of each component before powering the circuit.

### 4. Configure the ESP32

Select the correct ESP32 board and serial port in Arduino IDE.

### 5. Upload the Firmware

Compile the sketch and upload it to the ESP32. Open the Serial Monitor if the program uses serial output for debugging.

### 6. Test the System

Test the prototype using suitable wet, dry, and metallic test objects. Verify sensor readings, classification conditions, and servo movement.

*Refer to the actual wiring diagram and source code for pin assignments and setup details.*

---

## 🧪 Testing & Validation

The following tests can be used to evaluate the prototype:

- Verify IR sensor response when an object enters the detection area.
- Check moisture sensor readings using different moisture conditions.
- Test inductive sensor detection with suitable metallic objects.
- Verify the ESP32's classification decisions for different sensor combinations.
- Confirm that the servo moves to the intended position for each category.
- Repeat tests to identify sensor noise, inconsistent readings, and mechanical alignment issues.

---

## 🎯 Applications

- Educational demonstrations of embedded systems
- Waste segregation awareness projects
- Smart waste-management prototypes
- Sensor interfacing and actuator-control learning
- IoT and environmental automation concepts
- Engineering project demonstrations

---

## 🔮 Future Improvements

- Camera-based waste classification using computer vision
- IoT dashboard for system monitoring
- Wireless reporting of segregation statistics
- Bin-level monitoring using distance sensors
- Improved classification logic and sensor calibration
- Servo position feedback and fault detection
- Power optimization and alternative power sources
- Data logging for waste-category statistics
- Mechanical improvements for higher reliability

---

## ⚠️ Limitations

- Classification depends on the sensor characteristics and programmed decision rules.
- Some mixed-material or contaminated waste may not be classified reliably.
- Moisture readings can vary with sensor placement and material contact.
- Inductive proximity sensors detect suitable metallic targets but do not identify every material type.
- Mechanical sorting accuracy depends on the servo mechanism and compartment alignment.
- The project is a prototype and should not be considered a validated industrial waste-processing system.

---

## 🎓 Learning Outcomes

- ESP32 microcontroller programming using Embedded C/C++.
- Digital sensor interfacing and sensor-data processing.
- GPIO configuration and hardware-software integration.
- Servo motor control and actuator interfacing.
- Conditional control logic for sensor-based classification.
- Hardware testing, troubleshooting, and prototype validation.
- Understanding how embedded systems can address practical environmental problems.

---

## 🏁 Conclusion

The **Smart Waste Segregation System** demonstrates how an ESP32, multiple sensors, and a servo motor can be combined to create a prototype for automated waste segregation.

The project provides practical experience in embedded programming, sensor integration, actuator control, and hardware-software interaction while exploring a technology-based approach to more organized waste management.

---

## 👤 Author

**Shivam Borane**  
Electronics & Telecommunication Engineering

**Technical Focus:** Embedded Systems · ESP32 · Embedded C/C++ · Sensor Interfacing · IoT

---

## 📄 License

Refer to the repository's `LICENSE` file for the applicable license. Add or select a license only after confirming that you have the right to publish the project's source code and assets.

---

<p align="center">
  <em>Built with ESP32 • Designed for smarter waste segregation</em>
</p>
