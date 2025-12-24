# Two-Stage OTA Design in Cadence Virtuoso

## Overview
This repository contains the **design, simulation, and analysis of a CMOS two-stage Operational Transconductance Amplifier (OTA)** implemented using **Cadence Virtuoso with the Spectre simulator**.  
The project focuses on understanding core **analog IC design principles**, including biasing, small-signal and large-signal behavior, frequency response, stability, and power consumption.

The OTA follows a classical **two-stage architecture** and uses **Miller compensation** to ensure stable operation.

---

## Objectives
- Design a CMOS two-stage OTA using schematic-level MOSFETs  
- Verify correct DC biasing and saturation of all transistors  
- Analyze small-signal and large-signal behavior  
- Evaluate key performance parameters such as gain, bandwidth, phase margin, slew rate, and power  

---

## OTA Architecture
The designed OTA consists of:
- **NMOS differential input pair**
- **PMOS current mirror active load**
- **Second-stage common-source amplifier**
- **Miller compensation capacitor**
- **Biasing network** to ensure saturation operation

---

## Tools & Environment
- **EDA Tool:** Cadence Virtuoso  
- **Simulator:** Spectre  
- **Technology:** gpdk90
---
