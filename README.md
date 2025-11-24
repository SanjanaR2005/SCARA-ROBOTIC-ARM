# SCARA-ROBOTIC-ARM
SCARA ARM Control using Arduino | NEMA17 | TMC2208 | MG90S
A custom-built 4 Degree-of-Freedom SCARA robotic arm designed for pick-and-place operations using **Arduino** and **NEMA17 stepper motors**. This project aims to explore embedded control systems, kinematics, and automation relevant to industrial robotics.

##Features
- 4 DOF SCARA configuration
- Stepper control with **TMC2208 drivers** (smooth + silent)
- Servo-based end-effector control (MG90S / SG90)
- 12V power system with LM2596 buck converter
- Payload capacity: **200–300g**


## 🧰 Hardware / Components Used
| **Component** | **Qty** | **Notes** |
|--------------|:-------:|-----------|
| NEMA 17 Stepper Motors | 3 | Base, Elbow, Vertical lift |
| MG90S / SG90 Servo Motors | 2 | Wrist rotation + gripper control |
| TMC2208 Stepper Drivers | 3 | Silent Smooth STEP/DIR drivers |
| Arduino UNO  | 1 | Main controller |
| GT2 Timing Belt + 16T Pulleys | 1 set | Motion transmission |
| 12V 3A Power Supply | 1 | Primary power |
| Bearings, Couplers, M3 Screws | — | Mechanical structure |

