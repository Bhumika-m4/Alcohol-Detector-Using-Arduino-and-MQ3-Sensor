# System Architecture

The Alcohol Detector system consists of four major sections: input sensing, processing unit, alert generation, and power supply.

The MQ3 Alcohol Sensor serves as the input device. It continuously monitors the surrounding air and detects alcohol vapors. The sensor output is transmitted to the Arduino UNO in the form of an analog voltage.

The Arduino UNO acts as the central processing unit. It receives sensor data, converts analog signals into digital values using its internal ADC, and compares the readings against a predefined threshold value.

The alert section includes an LED and buzzer. When alcohol levels exceed the threshold, the Arduino sends control signals to activate both devices. The LED provides visual indication, while the buzzer generates an audible warning.

The power supply section ensures stable operation of all components. Together, these modules create a complete embedded alcohol detection system suitable for safety applications.

## Circuit Diagram

![Circuit Diagram](./circuit%20diagram.png)
