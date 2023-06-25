# CNC Plotter Machine

The Secure Communication with NRF24L01 Module and Arduino Nano project aims to establish a secure and encrypted communication channel between two devices using the NRF24L01 wireless module and Arduino Nano microcontrollers. This project ensures the confidentiality and integrity of data transmitted between the devices by implementing encryption algorithms and secure communication protocols.

This project is special than the rest of the other projects that I have done so far, as it contains an illustration of the circuit of the sender and the receiver i have made using Fritzing software, and a PCB drawing ready to print it using EasyEDA software. All of this you will find it in this [folder](https://oshwlab.com/ashrafabdulkhaliq80/security-project).

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Components](#components)
- [Usage](#usage)
- [Configuration](#configuration)

## Features

- **Wireless Communication**: Establish a wireless communication link between two Arduino Nano devices using the NRF24L01 module.
- **Encryption**: Implement encryption algorithms to encrypt the data transmitted between the devices, ensuring confidentiality.
- **Authentication**: Authenticate the devices to establish a trusted communication channel and prevent unauthorized access.
- **Secure Protocols**: Utilize secure communication protocols to protect against data tampering or interception.
- **Reliable Delivery**: Implement mechanisms to ensure reliable delivery of data between the devices.
- **Configurable Parameters**: Customize encryption algorithms, authentication mechanisms, and communication protocols according to your specific requirements.

## Getting Started

To get started with the CNC plotter machine, follow these steps:

1. Assemble the hardware components [Transmitter] according to this [schematic diagram](transmitter-device/transmitter-circuit.png).
2. Connect the CD-ROM stepper motors to the motor driver, and then connect the motor driver to the Arduino Uno.
3. Download and install [Arduino IDE](https://www.arduino.cc/en/software), [Inkscape 0.91](https://inkscape.org/release/inkscape-0.91/?latest=1) and [Processing](https://processing.org/download).
4. Install the [AFMotor](AFMotor.rar) Library, you can install it manually by downloading the files and install it into Arduino IDE or directly from library manager.
5. Adjust the pen holder to securely hold the pen or marker.
6. Place a sheet of paper or a drawing surface on the flat surface where you want the plotter to draw.
7. Power on the Arduino Uno and initiate communication with the plotter machine.
8. There is ready gcode to test if you want.
8. If you get stucked with any step, you can give a look for the original article [here](https://electricdiylab.com/how-to-make-arduino-mini-cnc-plotter-machine/).
9. Output, [our machine while drawing](https://drive.google.com/file/d/1T6XbWHDwXpsRdm7keNW0uuRVcscyL0hK/view).
![output](output.jpg)

## Components

- 2 * Arduino Nano
- 2 * NRF24L01 Module
- 1 * LCD 2x16
- 1 * 10K Potentiometer

## Usage

Once the CNC plotter machine is set up and connected, you can use various methods to control its movements and create drawings:

- **Direct Commands**: You can send direct commands to the Arduino Uno via a serial terminal or a custom software interface to control the plotter machine's movements.
- **G-Code**: Generate G-code instructions using software such as Inkscape or CAD programs, and then send the G-code commands to the plotter machine for precise drawing.
- **Predefined Patterns**: Utilize preconfigured patterns or designs by storing them in the Arduino's memory or by creating specific functions in the Arduino sketch.

## Configuration

The CNC plotter machine can be customized to suit your specific needs and preferences. Here are a few customization options:

- **Drawing Size**: Adjust the dimensions of the plotter machine to accommodate larger or smaller drawing surfaces.
- **Pen Options**: Experiment with different pens or markers to achieve various line thicknesses and effects.
- **Control Interface**: Develop a custom software interface to control the plotter machine and send commands more conveniently.
- **Additional Features**: Expand the functionality of the plotter machine by adding sensors, an LCD display, or additional actuators.
