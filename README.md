# IoT Hands-On Work | Arduino Projects

A collection of hands-on **Arduino programming exercises, IoT experiments, sensor interfacing projects, and electronic component implementations**. This repository documents my practical learning journey in Arduino, embedded systems, and the Internet of Things (IoT).

The projects cover fundamental programming concepts, LED control, sensors, displays, motors, interrupts, and serial communication. New projects and experiments will be added as I continue learning.

## Technologies & Tools

- **Programming Language:** Arduino C/C++
- **Platform:** Arduino Uno and compatible boards
- **IDE:** Arduino IDE
- **Hardware:** Sensors, LEDs, motors, displays, and electronic components
- **Domains:** Internet of Things (IoT) and Embedded Systems

## Repository Projects

### 1. Basic Arduino Programming & LED Control

| Project | Description |
|---|---|
| [Blink LED](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Blink%20LED.ino) | Blinks an LED at regular intervals. |
| [Button Controlled LED](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Button%20Controlled%20LED.ino) | Controls an LED using a push button. |
| [Toggle LED with Button](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Toggle%20LED%20with%20Button.ino) | Toggles the LED state when the button is pressed. |
| [PWM Fade (Fade In + Fade Out)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/PWM%20Fade%20%28Fade%20In%20%2B%20Fade%20Out%29.ino) | Gradually increases and decreases LED brightness using PWM. |
| [RGB LED Control](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/RGB%20LED%20Control.ino) | Experiments with controlling RGB LED colors. |
| [Non-Blocking Delay Pattern](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Non-Blocking%20Delay%20Pattern.ino) | Demonstrates timing operations without relying on blocking delays. |

### 2. Sensors & Environmental Monitoring

| Project | Description |
|---|---|
| [LDR — Automatic Night Light](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/LDR%20%28Light%20Sensor%29%20%E2%80%94%20Auto%20Night%20Light.ino) | Uses a light-dependent resistor to detect light levels and control a light. |
| [DHT11 Temperature & Humidity](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/DHT11%20Temperature%20%26%20Humidity.ino) | Reads temperature and humidity using a DHT11 sensor. |
| [Read Temperature (LM35)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Read%20Temperature%20%28LM35%29.ino) | Reads temperature using an LM35 analog temperature sensor. |
| [Ultrasonic Sensor (HC-SR04)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Ultrasonic%20Sensor%20%28HC-SR04%29.ino) | Measures distance using an ultrasonic sensor. |
| [Read Analog Input (Potentiometer)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Read%20Analog%20Input%20%28Potentiometer%29.ino) | Reads analog values from a potentiometer. |

### 3. Displays & Audio

| Project | Description |
|---|---|
| [I2C LCD Display (16x2)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/I2C%20LCD%20Display%20%2816x2%29.ino) | Displays information on a 16×2 LCD using I2C communication. |
| [Buzzer Tone (Tone Melody)](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Buzzer%20Tone%20%28Tone%20Melody%29.ino) | Generates tones or a simple melody using a buzzer. |

### 4. Motors & Actuators

| Project | Description |
|---|---|
| [Servo Motor Sweep](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Servo%20Motor%20Sweep.ino) | Sweeps a servo motor through a range of angles. |

### 5. Communication & Advanced Concepts

| Project | Description |
|---|---|
| [Serial Communication Basics](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Serial%20Communication%20Basics.ino) | Introduces serial communication between Arduino and a computer. |
| [Interrupt Example](https://github.com/nomanabdullah26/IoT-Hand-On-Work/blob/main/Interrupt%20Example.ino) | Demonstrates interrupt-based event handling. |

## Hardware Requirements

Depending on the project, you may need:

- Arduino Uno or a compatible development board
- USB cable
- Breadboard and jumper wires
- LEDs and resistors
- Push buttons
- RGB LED
- Potentiometer
- LDR sensor
- DHT11 temperature and humidity sensor
- LM35 temperature sensor
- HC-SR04 ultrasonic sensor
- 16×2 I2C LCD module
- Buzzer
- Servo motor

**Note:** Not every project requires all components. Check the individual source code before assembling the circuit.

## How to Run the Projects

1. Install the [Arduino IDE](https://www.arduino.cc/en/software).
2. Clone or download this repository.
3. Open the required `.ino` file in Arduino IDE.
4. Connect the Arduino board and the required components according to the circuit.
5. Select the appropriate board and COM port.
6. Install any required libraries mentioned in the source code.
7. Click **Verify** to compile the sketch.
8. Click **Upload** to upload the program to your Arduino board.
9. Open the Serial Monitor when required by the project.

## Learning Objectives

- Understand Arduino programming fundamentals.
- Practice digital and analog input/output operations.
- Learn PWM-based LED brightness control.
- Interface sensors with a microcontroller.
- Read temperature, humidity, light, and distance measurements.
- Control motors, LEDs, and buzzers.
- Understand serial communication and interrupt handling.
- Build a foundation for IoT and embedded systems development.

## Future Improvements

As I continue learning, I plan to expand this repository with:

- More sensor and actuator projects.
- Additional Arduino communication experiments.
- Practical IoT applications.
- Circuit diagrams and wiring instructions.
- Project demonstrations and documentation.

## Repository Updates

This repository is a work in progress. New source code, experiments, and improvements will be added regularly as part of my hands-on learning journey.

## Author

**Noman Abdullah**

GitHub: [@nomanabdullah26](https://github.com/nomanabdullah26)

Repository: [IoT-Hand-On-Work](https://github.com/nomanabdullah26/IoT-Hand-On-Work)

---

⭐ If you find this repository useful, consider giving it a star!
