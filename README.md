# VGA Controller

## Description
This project implements a VGA controller capable of generating VGA signals to drive a monitor. The controller manages colors based on user input from switches and is designed to run on a DE10-Lite FPGA board.

## Features
- **Horizontal and Vertical Synchronization**: Generates accurate VGA_HS and VGA_VS signals based on the VGA protocol.
- **Color Control**: RGB outputs are controlled by switches to produce red, green, and blue colors.
- **Pixel Clock**: Divides the system clock (50 MHz) to a pixel clock of 25 MHz.

## Project Files
### VHDL Files
- `vhdl2_uppgift_1a.vhd`: Main design for the VGA controller.
- `vhdl2_uppgift_1a_vhd_tst.vhd`: Testbench for verifying the design.

### Documentation
- `Ahmed_abdulkadir_vhdl2_uppgift_1a.docx`: Complete documentation of the project, including requirements, system architecture, verification, and validation.

### Scripts
- `.do` file for simulation in ModelSim.

## Tools Used
- **Quartus Prime**: For synthesis and implementation on the FPGA.
- **ModelSim**: For simulation and verification of VHDL code.
- **DE10-Lite**: FPGA board for hardware validation.

## Requirements
This project fulfills the following requirements:
1. Generate horizontal and vertical synchronization according to the VGA protocol.
2. Produce accurate color control based on user switches.
3. Simulate and verify functionality in ModelSim.
4. Validate the design on a VGA monitor via the DE10-Lite board.

## Usage
### Simulation
1. Import the `.vhd` files into ModelSim.
2. Use the provided `.do` file to run the simulation.
3. Check waveforms for VGA_HS, VGA_VS, and RGB signals.

### Implementation
1. Upload the design to the DE10-Lite FPGA board using Quartus Prime.
2. Connect a VGA monitor to the board.
3. Use the switches to observe color changes on the screen.

## Test Protocols
Verification and validation test protocols are detailed in the documentation.

## Author
**Ahmed Abdulkadir**  
Email: [Ahmed.abdulkadir@live.se]  
Date: [2024-12-01]

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
