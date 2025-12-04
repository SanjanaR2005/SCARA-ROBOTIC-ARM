# SCARA Robot Wiring Reference

Controller: Arduino UNO  
Stepper Motors: 3 × NEMA 17  
Stepper Drivers: 3 × TMC2208  
Servo Motors: 2 × SG90 / MG90S  
Power Supply: 12V 3A  

## Power
- 12V → VM of all TMC2208 drivers
- GND → Common ground for Arduino, Drivers, and Power Supply
- Arduino powered by USB
- Servos powered from Arduino 5V

## TMC2208 Driver Wiring (All 3 Drivers)
- VM → 12V
- GND → GND
- VIO → Arduino 5V
- STEP → D2 / D4 / D6
- DIR → D3 / D5 / D7
- EN → GND
- Motor → A1 A2 B1 B2

## Servo Motors
- Wrist Servo → D9
- Gripper Servo → D10
- Red → 5V
- Brown → GND
- Yellow → PWM Pin

