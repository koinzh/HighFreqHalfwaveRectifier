# HighFreqHalfwaveRectifier
A basic design for high frequency half-wave rectifier with SMS7630 and FR4 PCB.

## Overview
This repository contains the design, simulation, and testing files for a High-Frequency Half-Wave Rectifier used in RF energy harvesting applications. The rectifier is designed using SMS7630 Schottky diodes and a 1.6 mm FR4 PCB, with a focus on achieving efficient RF to DC conversion at 0.9 GHz.

## Project Highlights
- Objective: Develop a low-cost, high-efficiency rectifier for wearable electronics and renewable energy systems.
- Tools: ADS (Advanced Design System) for schematic, layout, and co-simulation; MATLAB for additional data analysis.
- Key Components: SMS7630 Schottky diode, FR4 PCB.
- Applications: Wearable electronics, RF energy harvesting, and small-scale renewable energy solutions.

## Project Structure


## How to Use
### Requirements
- ADS 2024: To open and modify the schematic and layout designs.
- MATLAB: For data analysis and result visualization (optional).

### Instructions
- Download the Repository: Clone the repository to your local machine:

        ```git clone https://github.com/koinzh/HighFreqHalfwaveRectifier.git```
- Open ADS:
Load the workspace files in ADS to view or modify the rectifier design.
- Run Simulations:
Simulate the circuit using the co-simulation features in ADS. The simulation setup files are located in the simulation_data/ directory.
- Analyze Data:
Use the provided MATLAB script in scripts/ to analyze the output data from the ADS simulation.

## Key Results
- Efficiency: Maximum efficiency of 55% at 0.9 GHz with optimized impedance matching.
- S11 Parameter: Achieved good input matching with an S11 of -19.7 dB at the target frequency.
- Challenges: The FR4 PCB material led to performance constraints at higher frequencies due to its dielectric properties.

## Future Work
- Explore the use of high-performance substrates like Rogers for better efficiency at higher frequencies.
- Investigate more advanced Schottky diodes or alternative diode technologies for improved RF energy harvesting.

## License
This project is licensed under the MIT License.