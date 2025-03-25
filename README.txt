# 🧭 DRO & DIVIDER Systems – Embedded Control Interface for Watchmaking Machinery

> Embedded systems project developed during a summer internship – ENSEA (2024)

## 📌 Project Summary

This project involved designing and prototyping two embedded control systems — a **Digital Read-Out (DRO)** interface and a **DIVIDER** motor control module — to modernize mechanical watchmaking machines, without altering their vintage aesthetic.

We developed a full-stack embedded application based on STM32 microcontrollers, including sensor data acquisition, user interface development (TouchGFX), real-time control of motors, and communication between devices.

> 💡 Non-confidential project – suitable for public sharing.

---

## 🔧 Key Features

### 🖥️ DRO System (Main Controller)
- 7” capacitive touchscreen interface
- Real-time display of axis positions (X/Y/Z)
- GUI with control functions: 
  - `ZERO`, `Ø/R`, `+/-`, spindle speed, and torque
- Interfaces: RL2IC sensors, UART, I2C, RS422

### ⚙️ DIVIDER System
- Dual stepper motor control:
  - Linear advance (motor 1)
  - Angular indexing (motor 2)
- Precision via screw/nut + endless screw systems
- Controlled from DRO board via I2C

---

## 🧠 Technical Stack

| Category              | Tools / Technologies                     |
|-----------------------|------------------------------------------|
| Embedded Programming  | C, STM32CubeIDE, HAL drivers             |
| GUI Development       | TouchGFX                                 |
| Microcontrollers      | STM32F411xE (Nucleo), STM32H7 (Riverdi) |
| Communication         | I2C, UART, RS422                         |
| Signal Prototyping    | Logic Analyzer, Oscilloscope, Putty      |
| Hardware Design       | KiCad (schematics), sensors, motors      |
| Components            | RS485 Click, UART Mux, Incremental encoders, NEMA 17, Riverdi 7" LCD |

---

## 🛠️ Main Contributions

✅ Designed and implemented a user-friendly GUI on STM32 using TouchGFX  
✅ Developed communication interfaces (I2C, UART, RS422) between boards and sensors  
✅ Integrated stepper motor drivers with PWM and direction control  
✅ Built functional hardware prototypes with debugging via logic analyzers  
✅ Collaborated directly with a non-technical client to translate mechanical requirements into embedded specs

---

## 📸 Screenshots

> See full PDF report with schematics, GUI designs and prototyping photos here:  
📄 [Rapport_de_projet_Watchscale.pdf](./Rapport_de_projet_Watchscale.pdf)

---

## 👨‍💻 Authors

- **Selim Farci** – Embedded Systems Engineering Student (ENSEA)  
- **Abdelkader Chambi** – Embedded Systems Engineering Student (ENSEA)  
- **Eyraud Michaël** – Internship supervisor and initiator of the project (Mécaniquement Vôtre)

---

## 🪪 License

This project is released under the **MIT License**.  
Note: proprietary hardware is subject to company use policies.
