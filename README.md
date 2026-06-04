# Cuk Converter 

This project focuses on the design and implementation of a **Cuk DC-DC Converter** using the **TL494 PWM controller**. The objective was to realize a functioning converter with a regulated output and verify its operation through both simulation and hardware testing.

## Specifications

- **Input Voltage:** 10 V  
- **Output Voltage:** 7.5 – 12.5 V  
- **Switching Frequency:** 7.5 kHz  
- **Output Current:** 1 A  

## Overview

The following steps were carried out:

1. **MATLAB Simulink Simulation**:  
   - Designed and simulated the Cuk converter topology  
   - Verified key waveforms: diode current and inductor voltage in **Continuous Conduction Mode (CCM)**  
   - Increased load resistance to observe **Discontinuous Conduction Mode (DCM)** behavior

2. **Hardware Implementation**:  
   - Built the circuit using discrete components and **TL494** as the PWM generator  
   - Observed real-time waveforms on an oscilloscope to validate functionality  
   - Fine-tuned the duty cycle to achieve the required output voltage range
   - Soldered the components on a perfboard and further verified functionality.

## Files in the Repository

- `powerproject.slx` – Simulink model of the converter  
- `B1-G10 EE252 PROJECT REPORT.pdf` – Complete project report with schematics, waveform snapshots, and analysis

The above mentioned report contains the video demonstration of the circuit and some images showing the hardware circuit and output waveforms for different conditions.
