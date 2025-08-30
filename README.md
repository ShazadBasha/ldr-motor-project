# LDR Motor Project

This project is about controlling a DC motor using an LDR (Light Dependent Resistor) and MOSFETs.

## Goals
- Motor should turn ON when it is dark.
- Motor should turn OFF when there is light.
- Learn switching using both N-channel and P-channel MOSFETs.
- Test the effect of resistors, diode, and gate capacitor.

## Current Status
✅ Basic circuit working (without diode & gate capacitor)  
🔲 Next: Add diode across motor for protection  
🔲 Next: Add gate capacitor for stability  
🔲 Next: Try bigger MOSFETs (IRFZ44N, IRF540N) for easy soldering

## Components
- LDR
- Resistors: 10kΩ, 100kΩ, 220Ω (others for testing)
- N-channel MOSFET (e.g., IRFZ44N, IRF540N)
- P-channel MOSFET (optional for experiments)
- Diode: 1N4007 (flyback diode across motor)
- Capacitor: 100nF (gate stabilization)

## How it Works
- LDR changes resistance with light.
- Resistor + LDR form a voltage divider.
- This voltage controls the MOSFET gate.
- Motor runs in dark and stops in light.
