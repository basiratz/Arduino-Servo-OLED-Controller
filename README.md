# Arduino Servo OLED Controller

An Arduino Uno project that controls a servo motor using a potentiometer and displays the servo angle on an OLED screen.

## Features
- Controls servo position using a potentiometer.
- Converts analog input into an angle from 0° to 180°.
- Displays the current angle on a 128×64 OLED display.
- Updates the display continuously.

## Components
- Arduino Uno
- Servo motor
- Potentiometer
- SSD1306 128×64 I²C OLED display
- Breadboard and jumper wires

## Wiring

| Component | Arduino connection |
|---|---|
| Servo signal | D9 |
| Potentiometer middle pin | A0 |
| OLED SDA | A4 |
| OLED SCL | A5 |
| OLED VCC | 5V |
| OLED GND | GND |

Connect the potentiometer's outer pins to 5V and GND.

## Libraries
- Servo
- Wire
- Adafruit GFX
- Adafruit SSD1306

Install the Adafruit libraries using Arduino IDE's Library Manager.

## How it works
The Arduino reads the potentiometer's analog value, maps it to an angle between 0° and 180°, moves the servo, and displays the angle on the OLED.

### Project Image and Video
<img width="1600" height="1100" alt="servo-led" src="https://github.com/user-attachments/assets/785c2ab3-b7cb-4fa6-8d6e-55d55e61084c" />


https://github.com/user-attachments/assets/8fc592f1-6459-4498-87b9-feecba6fcbab
