---
layout: default
title: Neurorehab
---

# Music-Based Video Game Therapy for Hand Rehabilitation

This project was developed at the Biomechanics and Applied Robotics Laboratory (PUCP).  
We created a music-driven video game therapy system to support wrist and hand rehabilitation in children with cerebral palsy.

---

## Overview
Children with cerebral palsy often struggle with wrist and hand movements. Traditional therapy can be repetitive and demotivating.

We designed a **playful rehabilitation interface** combining:
- Music therapy principles  
- Real-time IMU motion tracking  
- Three therapeutic video games  
- Adjustable difficulty and therapist configuration  

---

## My Contributions
- Designed and implemented the full software system in **Unity (C#)**.  
- Integrated **BNO055 IMU sensors** for real-time wrist and finger tracking.  
- Developed three therapeutic games: Bubble, Rocket, Squirrel.  
- Implemented music-based cues (metronome timing, volume feedback).  
- Built therapist configuration menus for movement type, repetitions, and difficulty.  
- Processed IMU data using Butterworth and Savitzky–Golay filters.  
- Conducted a pilot study with 10 children (8–12 years).

---

## Key Findings
- Music reduced movement variability across tasks → smoother, more predictable motor control.  
- Children rated the system as relaxing and engaging.  
- ROM remained stable, but movement consistency improved.  
- Positive usability feedback supports future clinical trials.

---

## Gallery

<div style="display:flex; flex-wrap:wrap; gap:30px; justify-content:center; margin-top:20px;">

  <div style="text-align:center; width:30%; min-width:250px;">
    <img src="/assets/movimientos.png" 
         style="width:100%; border-radius:10px;">
    <p style="color:#9fb3c8; font-size:14px; margin-top:8px;">
      Squirrel game (wrist abduction/adduction), Rocket game (wrist flexion/extension), and Bubble game (finger flat pinch) 
    </p>
  </div>

  <div style="text-align:center; width:30%; min-width:250px;">
    <img src="/assets/hardware.png" 
         style="width:100%; border-radius:10px;">
    <p style="color:#9fb3c8; font-size:14px; margin-top:8px;">
      Hardware setting
    </p>
  </div>

  <div style="text-align:center; width:30%; min-width:250px;">
    <img src="/assets/seq_diagram.png" 
         style="width:100%; border-radius:10px;">
    <p style="color:#9fb3c8; font-size:14px; margin-top:8px;">
      Software sequence diagram
    </p>
  </div>

  <div style="text-align:center; width:30%; min-width:250px;">
    <img src="/assets/pilot_study.jpg" 
         style="width:100%; border-radius:10px;">
    <p style="color:#9fb3c8; font-size:14px; margin-top:8px;">
      Pilot study
    </p>
  </div>

</div>

---

## Tools & Skills
**Unity (C#)**, **IMU sensors**, **Signal processing**, **MATLAB**, **Game design**, **Human–computer interaction**, **Pediatric rehabilitation**

---

## Impact
This system integrates Neurologic Music Therapy with interactive gaming, offering a motivating alternative to traditional rehabilitation.

Published in:
- **Journal of NeuroEngineering and Rehabilitation (2024):** Integration of music-based game approaches with wearable devices for hand neurorehabilitation: a narrative review
- **Journal of NeuroEngineering and Rehabilitation (2025):** Evaluation of wrist and finger function in healthy children through music-based video game therapy
