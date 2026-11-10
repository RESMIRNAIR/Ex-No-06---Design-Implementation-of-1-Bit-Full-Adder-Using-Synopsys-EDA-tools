# Ex No: 06 - Design & Implementation of 1-Bit Full Adder Using Synopsys EDA tools

## Aim
The aim is to design and implement a 1-bit Full Adder using Synopsys EDA tool and verify its functionality through transient analysis simulation.

## Tools Required

### Synopsys EDA Suite
- Synopsys Custom Compiler – For CMOS schematic design.
- Synopsys PrimeWave Design Environment – For simulation setup and waveform analysis.
- Synopsys PrimeSim HSPICE / PrimeSim – For circuit simulation and analysis.

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**
- Linux-based operating system compatible with the installed Synopsys tools.

## Procedure:
### 1. Launch Synopsys Custom Compiler Environment :
     Open Synopsys Custom Compiler and set up the working library.
     Create a new design library and associate it with the appropriate CMOS technology PDK.
     Create a new schematic cell view for the CMOS circuit design.
### 2. Schematic Design:
    Launch Synopsys Custom Compiler and create a new design library associated with the appropriate CMOS technology PDK.
    Create a new schematic cell view for the required CMOS complex gate.
    Select the required NMOS and PMOS transistors from the technology library based on the given Boolean expression.
    Connect the NMOS and PMOS transistors appropriately to implement the required pull-down and pull-up networks.
    Connect the transistor gate terminals to the corresponding input signals.
    Connect the supply terminals to VDD and GND, ensuring that the bulk terminals are connected to the appropriate supply potentials.
    Connect DC voltage sources (VDC) to provide the required supply voltage and pulse voltage sources (VPULSE) to apply the input signals.
    Connect the output terminal to the common node of the pull-up and pull-down networks.
### 3. Simulation:
    Check the schematic for errors and verify the electrical connections.
    Create a testbench for the CMOS design.
    Launch Synopsys PrimeWave Design Environment.
    Select the appropriate simulator, such as PrimeSim HSPICE.
    Configure transient analysis to study the time-domain response.
    Set the simulation parameters, including supply voltage, input pulse period, rise time, fall time, and simulation stop time.
    Run the simulation and verify the simulation results.


## Circuit Diagram

<img width="712" height="433" alt="image" src="https://github.com/user-attachments/assets/ac1969f6-b2b5-4394-9dba-d457dfa5ebe9" />


## Truth Table for 1-Bit Full Adder
![image](https://github.com/user-attachments/assets/328fae3c-b83a-4cd6-b394-54323dc59673)


## Schematic Diagram
### 1. Schematic of 1-Bit Full Adder:

<img width="712" height="337" alt="Screenshot 2026-11-10 155301" src="https://github.com/user-attachments/assets/3e905133-3777-445a-9e2c-e1cb69b58c72" />



## Output
### Transient Analysis Output:
<img width="931" height="467" alt="Screenshot 2026-11-10 155335" src="https://github.com/user-attachments/assets/e2d05621-8d77-4425-9354-bac9075b2d43" />

<img width="959" height="452" alt="Screenshot 2026-11-10 155421" src="https://github.com/user-attachments/assets/d8535c76-6abc-496f-88bb-cc7f1c9fce7b" />


## Results
1. Successfully designed the **1-bit Full Adder** schematic using **Synopsys EDA tools**.
2. Performed **transient analysis**, verifying the correct operation of the **Full Adder**.
3. Observed **correct logic switching behavior** in response to input signals.
