# Nonlinear Ultrasound Parameter Estimation Using the Extended Comparative Method (ECM)

This project was developed at the Medical Imaging Laboratory (PUCP).  
We estimated the nonlinear acoustic parameter B/A using second harmonic ultrasound propagation and simulations in MATLAB.

---

## Overview
Fatty liver disease alters tissue acoustic properties.  
The nonlinear parameter B/A increases in fatty tissue, making it useful for tissue characterization.

We implemented an adaptation of the **Extended Comparative Method (ECM)** to estimate B/A using simulated ultrasound data.

---

## My Contributions
- Simulated nonlinear ultrasound propagation using **K-Wave (MATLAB)**.  
- Designed FIR bandpass filters centered on the second harmonic.  
- Generated nonlinear coefficient maps for homogeneous and inhomogeneous media.  
- Applied **Total Variation (TV)** filtering to reduce noise while preserving edges.  
- Compared ECM outputs with analytical expectations.

---

## Key Findings
- ECM successfully estimated B/A values close to expected tissue behavior.  
- TV filtering improved stability of nonlinear coefficient maps.  
- Multiple filtering stages are required to avoid artifacts in derivative-based calculations.

---

## Tools & Skills
**MATLAB**, **K-Wave**, **Signal processing**, **Ultrasound physics**, **Harmonic imaging**, **Filtering techniques**

---

## Impact
This project contributes to improved ultrasound-based tissue characterization, with potential applications in early detection of fatty liver disease.

