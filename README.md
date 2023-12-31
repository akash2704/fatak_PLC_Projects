# Fatak PLC Projects

This repository contains various projects related to Fatak PLC. The projects are developed using different programming languages and frameworks to demonstrate different functionalities and applications of Fatak PLC.

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
- [Installation](#installation)
- [Hardware](#Hardware)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Fatak PLC is a programmable logic controller developed specifically for industrial automation and control systems. It provides a reliable and flexible solution for managing various processes and machinery in manufacturing and industrial environments.

This repository serves as a collection of projects that utilize Fatak PLC to showcase its capabilities and demonstrate practical implementations in different scenarios. Each project focuses on a specific aspect or application, providing code samples and documentation for reference and learning purposes.

## Projects

Here is a list of projects currently included in this repository:

- **Lamp Switch Program:** A program that controls the switching on and off of a lamp using a microcontroller or other electronic components.
- **One-Switch Start/Stop Program:** A program that enables starting and stopping of a process or system using a single switch or button.
- **Logic Gates Program:** A program that simulates and performs logical operations such as AND, OR, and NOT gates to process binary inputs and produce corresponding output values
- **One-Way Traffic Light Program:** Controls the sequencing of traffic lights at an intersection to regulate one-way traffic flow in a coordinated and safe manner
- **Parking Lot Program:** Displays green light when the parking lot is empty, red light when it's full, and activates a yellow light when the number of cars is between 0 and 10, while also indicating the number of incoming cars
- **Analog Conversion Program:** Converts computer input values ranging from 0-16383 into engineering values, representing 4mA - 20mA in current register and 0-10V in voltage register.
- **Analog Conversion Program 2:** Displays engineering values and converts them into corresponding computer values, which are then sent to the output register.
- **Analog Conversion Program 3:** Uses the ADCNV function with offset removal, simplifying the conversion of analog input values to their corresponding engineering values.
- **Temperature and Humidity Sensor Program:** Reads and monitors temperature and humidity levels using sensors, providing real-time data and enabling further analysis or control based on environmental conditions.
- **Temperature-based PID Control Program:** Utilizes a thermocouple sensor for temperature measurement and applies PID control algorithm with configurable P, I, and D parameters through Modbus RTU slave communication for precise temperature regulati

Each project directory contains its own set of files, including source code, configuration files, and any additional resources required to run the project.

## Installation

To use the projects in this repository, you need to have a Fatak PLC device and the necessary software and tools installed. Please refer to the official Fatak PLC documentation for detailed installation instructions.

## Hardware
I am Using Fatak for PLC and Kinco for HMI the Modules include:
- **FBs-20MCJ2-AC :**  A **compact and versatile** PLC module with **advanced functionality**, featuring a wide range of **discrete input and output registers** for flexible and efficient automation and control applications..
- **FBs4A2D :** The FBs4A2D module is a versatile PLC module with **2 analog input and output channels**, enabling precise monitoring and control in industrial applications
- **FBs-2TC :** The FBs2TC module is a compact PLC module with **2 thermocouple input capability**, providing **accurate temperature measurement** for industrial control applications.
- **FBs-CM25E :** The FBsCM25E module is a powerful PLC module with **Ethernet communication** capability, offering **advanced networking** for efficient industrial automation and control systems

## Usage
User
Use this steps to run the programs in your computer 
1. Clone the repository in your local computer
```
$ git clone https://github.com/akash2704/fatak_PLC_Projects.git
```
3. opent Winproladder software to run the program
4. go to file
go to open and select open icon where you have to go to the derictory where the clob=ned drictory is present there select the program that you need.
write this  readme in shell

## Contributing

Contributions to this repository are welcome. If you would like to contribute a new project, improve existing projects, or suggest enhancements, please follow the standard GitHub workflow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

Please provide clear descriptions and explanations for your contributions to help with the review process.
