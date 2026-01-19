## Overview 
This repository contains the complete design and simulation of a Two-Stage CMOS Operational Amplifier using Cadence Virtuoso.
The project covers schematic-level design, biasing, frequency compensation, and performance analysis such as DC operating point, AC gain, bandwidth, phase margin, and transient response.
This project is intended for analog VLSI / CMOS analog circuit design learning and academic purposes.

## Tech / Tools 
    EDA Tool: Cadence Virtuoso
    Technology: gpdk090  
    Amplifier Type: Two-Stage OPAMP
    
## Analysis Performed:
    DC Analysis
    AC Analysis
    Transient Analysis
    Gain & Bandwidth
    Phase Margin & Stability

## Description of Circuit
The op-amp uses a classical NMOS differential input stage with PMOS active loads, followed by a common-source second gain stage and Miller compensation to ensure stability. Instead of relying on ideal blocks, every device was biased and sized using DC operating point, transconductance, output resistance, and saturation margin, just like in an industry design cycle. All parameters were refined through iterative Spectre simulations until both gain and stability targets were met.

## Results
The amplifier achieves an open-loop DC gain of 𝟓𝟖.𝟒𝟗 𝐝𝐁
A phase margin of 𝟒𝟓.𝟗𝟔°, confirming a stable, properly compensated two-stage op-amp that changes with the change of supply voltage and resistance and current values and getting gain upto 80 dB approx.
