# Working Principle

The working principle of the Alcohol Detector is based on alcohol vapor sensing and real-time signal processing.

Initially, the MQ3 sensor remains active and continuously monitors the surrounding air. The sensor contains a sensitive semiconductor material whose resistance changes when alcohol molecules come into contact with it.

This resistance variation produces a corresponding analog voltage signal. The Arduino UNO reads this analog value through its analog input pin and converts it into a digital value using the built-in Analog-to-Digital Converter (ADC).

The Arduino compares the digital value with a predefined threshold. If the reading remains below the threshold, the system remains in a normal state and no alert is generated.

If the alcohol concentration exceeds the threshold, the Arduino immediately activates the buzzer and LED. The buzzer produces an audible warning while the LED provides visual indication. Once the alcohol level falls below the threshold, the alerts are automatically deactivated.

This continuous monitoring process ensures reliable and real-time alcohol detection.
