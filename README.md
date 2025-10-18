Smart Helmet Using Arduino
A College Tech Fest Hardware Project (4th Position Winner)

Overview
This project presents an Arduino-based Smart Helmet that enhances two-wheeler rider safety by integrating real-time wear detection, alcohol sensing, and drowsiness detection, using a wireless 433 MHz RF module. These features ensure the vehicle only starts in safe conditions—ideal for demonstration at college tech fests and practical IoT learning.​​

Key Features
Wear Detection: Uses IR sensors to ensure the helmet is worn before ride start.

Alcohol Detection: MQ-3 sensor prevents engine start if alcohol is detected.

Drowsiness Detection: Uses a time-window logic to accurately identify sleepiness patterns, ignoring normal blinking and alerting the rider to prevent accidents.

Required Components
Transmitter (Helmet Side)
Arduino UNO R3 – 1

433 MHz RF Transmitter Module – 1

IR Sensor – 2 (wear & drowsiness detection)

MQ-3 Alcohol Sensor – 1

LED & Buzzer – 1 each

Breadboard – 1

2-cell Lithium Battery (recommended 7.4V output, regulated to 5V)

Helmet (old/broken is fine for demo purposes)

Connecting wires:

Plain wires (two bunches)

Jumper wires: male-male, male-female, female-female (two bunches each)

1 roll electrical insulation tape (for secure current connections)

Receiver (Vehicle Side)
Arduino UNO R3 – 1

433 MHz RF Receiver Module – 1

16x2 LCD with I2C Module – 1

1-Channel Relay Module – 1

LED & Buzzer – 1 each

Breadboard – 1

Connecting wires

Miscellaneous
Optional: BO motor for demo ignition simulation.

For any issues, contact project support: 7047122601

Where to Buy Components (Kolkata, India)
Chandni Market, Kolkata

For all electronics: Visit the background area of Chandni E-Mall, filled with numerous shops selling all components at affordable prices. Just tell shopkeepers you're building an Arduino hardware project.

For helmet: Ask for second-hand or broken helmets from local vendors—suitable for demonstrations and saves costs.

For connecting wires: Get both plain wires and a variety of jumper wires as specified above.

Library Setup
LiquidCrystal_I2C: Install from Arduino IDE Library Manager (search “LiquidCrystal I2C by Frank de Brabander”).

Other required libraries: RH_ASK (RadioHead), SPI, Wire (last two are built-in).

If you see no matching function for call to 'LiquidCrystal_I2C::begin()', double-check the installed library version.

Build Advice
Carefully check sensor orientation and wiring before powering on.

Calibrate sensor thresholds using module potentiometers per your environment.

Take your time—hardware projects may fail a few times, but persistence and careful troubleshooting pay off.

Test each module independently before full integration.

Stay positive and confident—your project will work!

Acknowledgement
This project was developed for our college tech fest hardware competition, where we proudly secured the 4th position. Huge thanks to all teammates and supporters!

Reference
Documentation: How to Build a Smart Helmet using Arduino?​

Video Demo: Get Chrome for your computer​
