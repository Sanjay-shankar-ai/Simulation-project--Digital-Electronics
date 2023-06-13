# TITLE
Microcontroller Device Control System

# THEORY
This program enables a microcontroller to control a simple device, such as an LED light or a motor. The program utilizes digital output pins of the microcontroller to send control signals to the device. The code provided below demonstrates how to control a LED light connected to the microcontroller.


# PROGRAM
```
// Microcontroller Device Control System
// LED Control Program

// Pin Configuration
#define LED_PIN 2 // Digital Pin connected to the LED

void setup() {
  pinMode(LED_PIN, OUTPUT); // Set LED_PIN as an output pin
}

void loop() {
  digitalWrite(LED_PIN, HIGH); // Turn on the LED
  delay(1000); // Wait for 1 second
  digitalWrite(LED_PIN, LOW); // Turn off the LED
  delay(1000); // Wait for 1 second
}
```
# Microcontroller-Based LED Light Control System

This program controls a LED light using a microcontroller.

## Requirements

* A microcontroller
* A LED light
* A button

## Instructions

1. Connect the LED light to the microcontroller.
2. Connect the button to the microcontroller.
3. Upload the code to the microcontroller.
4. Press the button to turn on and off the LED light.

