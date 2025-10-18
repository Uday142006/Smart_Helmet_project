                                                          MUST READ
Smart Helmet Using Arduino 🛵🪖  
A College Tech Fest Hardware Project (4th Position Winner) 🎉🏅

Overview 🚀
This project presents an Arduino-based Smart Helmet that enhances two-wheeler rider safety by integrating real-time wear detection, alcohol sensing, and drowsiness detection, using a wireless 433 MHz RF module. These safety features ensure the vehicle only starts in safe conditions—perfect for college tech fests and practical IoT learning! 🔧👨‍💻​​

Key Features 🔥
Wear Detection: Uses IR sensors to ensure the helmet is worn before ride start. 🎯

Alcohol Detection: MQ-3 sensor prevents engine start if alcohol is detected. 🍺🚫

Drowsiness Detection: Implements a time-window logic to accurately recognize sleepiness patterns, ignoring normal blinking and alerting riders to prevent accidents. 😴⚠️

Required Components 📋
Transmitter (Helmet Side)
Arduino UNO R3 – 1

433 MHz RF Transmitter Module – 1

IR Sensor – 2 (wear & drowsiness detection)

MQ-3 Alcohol Sensor – 1

LED & Buzzer – 1 each

Breadboard – 1

2-cell Lithium Battery (recommended 7.4V output, regulated to 5V)

Helmet (old/broken, perfect for demo purposes)

Connecting wires:

Plain wires (two bunches)

Jumper wires: male-male, male-female, female-female (two bunches each)

Electrical insulation tape (for secure connections)

Receiver (Vehicle Side)
Arduino UNO R3 – 1

433 MHz RF Receiver Module – 1

16x2 LCD with I2C Module – 1

1-Channel Relay Module – 1

LED & Buzzer – 1 each

Breadboard – 1

Connecting wires

Miscellaneous
Optional: BO motor for ignition demo

For support, contact: 📞 7047122601

Where to Buy Components (Kolkata, India) 🛒
Chandni Market, Kolkata

Head to the background area of Chandni E-Mall for affordable electronic components. Just tell shopkeepers it’s for an Arduino hardware project. 🏬💡

For helmets, look for second-hand or broken helmets from local vendors—great for demos and budget-friendly. 🪖💰

Grab both plain and jumper wires as specified above to cover your wiring needs. 🔌

Library Setup 🧰
Install LiquidCrystal_I2C via Arduino IDE Library Manager (search: Frank de Brabander).

Required libraries:

RH_ASK (RadioHead)

SPI and Wire (built-in)

If you face errors like no matching function for call to LiquidCrystal_I2C::begin(), verify your library version. 🔍📚

Build Advice 💡
Double-check sensor placement and wiring before powering. ⚡

Calibrate sensor sensitivity using module potentiometers. 🔧

It may fail a few times but don’t lose hope—persist and troubleshoot carefully! 🛠️💪

Test modules independently before full integration. 🧩

Stay confident and motivated—your project will work! 🚀🙂

Acknowledgement 🙏
Proudly developed for our college tech fest hardware competition, winning the 4th position! Thanks to all teammates and mentors for the support! 🌟🎖

Reference 📚
Documentation: https://circuitdigest.com/microcontroller-projects/smart-helmet-using-arduino

Video Demo: https://www.youtube.com/watch?v=iRjUAR8dogc
