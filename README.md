Design and Analysis of a Voltage-Fed DC–DC Converter

This project presents the design, simulation, and experimental validation of a voltage-fed full-bridge DC–DC converter optimized for resistive load applications. The system is capable of stepping up an 80 V input to a stable 400 V output while maintaining high efficiency and galvanic isolation using a high-frequency transformer.


Key Features

Topology: Simplified full-bridge voltage-fed converter with transformer-based isolation
Voltage Gain: 5× (80 V → 400 V)
Efficiency: Achieved 87.6 % in hardware testing
Simulation Tools: MATLAB/Simulink and PLECS for modeling and waveform analysis
Hardware Components: SiC MOSFETs (IMW120R045M1), SiC diodes (IDWD20G120C5), WaveCT WCU300 controller, and CHROMA power systems
Measurement Tools: Keysight InfiniiVision oscilloscope and power analyzer


Methodology

Simulation Phase: Converter modeled in PLECS and validated under varying duty cycles to study voltage gain and switching behavior.
Hardware Implementation: Built a lab-scale prototype with a 1:6 high-frequency transformer, custom gate driver, and FPGA-based control via WaveCT and Simulink.
Analysis: Measured voltage and current waveforms, efficiency, and total harmonic distortion (THD) using oscilloscope and analyzer tools.


Results

Output voltage: 418 V (hardware) vs. 455 V (simulation)
Efficiency: 87.6 % confirmed via MSO power analysis
Demonstrated stable operation and high-gain voltage conversion suitable for solar, EV subsystems, and DC laboratory setups.


Sustainability Impact

This converter aligns with UN Sustainable Development Goals —
SDG 7: Affordable and Clean Energy, and SDG 9: Industry, Innovation, and Infrastructure —
by supporting efficient and scalable renewable energy power conversion
