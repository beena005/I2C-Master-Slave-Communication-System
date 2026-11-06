# I2C-Master-Slave-Communication-System
Design and simulation of a complete I2C Master and Slave communication system using Verilog HDL

## Project Overview

This project implements a complete Inter-Integrated Circuit (I2C) communication system using Verilog HDL. It consists of an I2C Master and an I2C Slave, enabling serial communication through a two-wire interface.

The design is developed for simulation and functional verification using EDA Playground.

## Objectives

- Design an I2C Master module using Verilog HDL.
- Design an I2C Slave module.
- Implement serial data transmission and reception.
- Understand I2C START and STOP conditions.
- Implement ACK/NACK acknowledgement mechanisms.
- Verify communication through simulation.

## System Architecture

The system consists of:

1. **I2C Master:** Initiates communication, generates the clock (SCL), sends slave addresses and transmits data.
2. **I2C Slave:** Responds to the master's address, receives data and generates acknowledgement signals.
3. **I2C Bus:** Uses two communication lines:
   - SDA – Serial Data
   - SCL – Serial Clock

## Features

- Master-Slave communication
- Two-wire serial communication
- START and STOP condition generation
- 7-bit slave addressing
- Data transmission and reception
- ACK/NACK handling
- FSM-based control logic
- Simulation-based functional verification

## Tools and Technologies

- HDL: Verilog
- Simulation Platform: EDA Playground
- Language: Verilog HDL
- Verification: Testbench and waveform analysis

## Simulation

The design is simulated using EDA Playground. The testbench verifies the communication between the I2C Master and Slave.

Simulation waveforms are included in the repository to demonstrate the communication process.

## Project Structure

- `Verilog/` – Master, Slave and Top modules.
- `Testbench/` – Verification testbench.
- `Simulation/` – Simulation waveforms and results.
- `Documentation/` – Project report and presentation.

## Learning Outcomes

- Understanding I2C serial communication protocol.
- RTL design using Verilog HDL.
- FSM-based digital design.
- Master-Slave communication.
- Functional verification using simulation.

## Author

**Beena Antony**

M.Tech – VLSI and Embedded Systems

## License

This project is available for educational and academic purposes.
