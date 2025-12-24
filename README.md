This repository presents the design, simulation, and analysis of a CMOS two-stage Operational Transconductance Amplifier (OTA) implemented using Cadence Virtuoso with the Spectre simulator. The objective of this project is to understand and demonstrate the fundamental analog IC design principles involved in achieving high gain, adequate bandwidth, stable operation, and low power consumption.

The design follows a classical two-stage OTA architecture, consisting of a differential input stage followed by a common-source gain stage. Miller compensation is used to ensure closed-loop stability.

🎯 Objectives

Design a CMOS two-stage OTA using standard MOSFET devices

Achieve high open-loop gain with stable frequency response

Analyze DC, AC, and transient performance using Cadence

Study key trade-offs between gain, bandwidth, stability, slew rate, and power

🧱 Architecture

The OTA consists of:

Input differential pair (NMOS) for differential amplification

Current mirror load (PMOS) for high gain

Second gain stage (common-source amplifier)

Miller compensation capacitor for frequency compensation

Biasing network to ensure all transistors operate in saturation

🛠 Tools & Technology

EDA Tool: Cadence Virtuoso

Simulator: Spectre

Technology: CMOS PDK (generic / university-provided)

Analysis Types: DC, AC, Transient

🔌 Schematic Design

All circuit blocks are designed using schematic-level MOSFETs

Pins are used to define clear inputs, outputs, and supply connections

The OTA is instantiated in a separate testbench for simulation
