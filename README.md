# USB-to-UART Converter PCB

A USB-to-UART converter PCB designed using KiCad as a learning project to understand the basic PCB design workflow.

## Overview

The board uses the CP2102N USB-to-UART bridge to provide communication between a computer's USB interface and a microcontroller's UART interface.

The PCB uses a USB Type-C connector as the USB interface and provides an external UART header.

## Main Components

- CP2102N USB-to-UART bridge
- USB Type-C receptacle
- ESD protection diode
- SMD resistors and capacitors
- Status LEDs
- 5-pin UART header

## KiCad Design Workflow

- Schematic capture
- Component selection
- Footprint assignment
- Custom footprint/library integration
- PCB component placement
- PCB routing
- Via usage
- Ground plane
- Design Rule Checking (DRC)
- 3D PCB visualization

## Schematic

![Schematic](images/schematic.png)

## PCB Layout

![PCB Layout](images/pcb-layout.png)

## 3D View

![3D View](images/3d-view.png)

## Tools

- KiCad
- CP2102N USB-to-UART bridge

## Project Status

Completed as a learning/prototype project to understand the basic KiCad PCB design workflow.

> **Note:** This project is intended for learning and portfolio demonstration and has not been validated as a production-ready PCB.

## Acknowledgement

This project was developed as a learning exercise based on a guided USB-to-UART PCB design tutorial. The project was recreated independently to understand the KiCad schematic and PCB design workflow.
