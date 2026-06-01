# Ćuk Converter (B2-G4)

This project focuses on the design and implementation of a **Ćuk DC-DC Converter** using the **TL494 PWM controller**.  
The objective was to realize a functioning converter with a regulated output and verify its operation through both simulation and hardware testing.

---

## Specifications

- **Input Voltage:** 10 V
- **Output Voltage:** 7.5 V – 12.5 V
- **Switching Frequency:** 10 kHz
- **Output Current:** 1 A

---

## Overview

The following steps were carried out:

### 1. MATLAB Simulink Simulation

- Designed and simulated the Ćuk converter topology
- Verified key waveforms such as diode current and inductor voltage in **Continuous Conduction Mode (CCM)**
- Increased load resistance to observe **Discontinuous Conduction Mode (DCM)** behavior

### 2. Hardware Implementation

- Built the circuit using discrete components and **TL494** as the PWM generator
- Observed real-time waveforms on an oscilloscope to validate functionality
- Fine-tuned the duty cycle to achieve the required output voltage range

### 3. PCB Design:

- Designed a custom PCB layout for the converter
- Soldered and tested the complete system on the fabricated board

---

## Tools & Components Used

- MATLAB Simulink
- TL494 PWM Controller
- Oscilloscope
- Power Electronics Components (Inductors, Capacitors, MOSFETs, Diodes)

---

## Results

- Successfully achieved regulated DC output
- Verified CCM and DCM operating conditions
- Hardware results closely matched simulation outputs

---

