# X-Ray-Diffraction
Laser Diffraction Analysis for Additive Manufacturing
This repository contains code and resources for performing in-situ laser diffraction analysis to investigate phase transformations and structural alterations in metals during additive manufacturing (AM) processes.

Overview:
In-situ laser diffraction enables the identification of phase transformations and structural changes in metals as they undergo melting and solidification. This technique involves directing a laser at a metal sample, heating it to the melting point, and monitoring real-time structural changes using X-ray diffraction. Additive manufacturing, with its layer-by-layer deposition, creates unique thermal and structural conditions that significantly impact the material's microstructure and properties.

How It Works:
The sample is subjected to intense laser heating, with controlled parameters for laser power, focus, heating rate, and cooling rate. This control allows the simulation of specific conditions relevant to AM and welding processes. During laser heating, an X-ray or neutron beam is aimed at the sample, and its diffraction pattern is recorded over time, capturing the structure's response to heating and cooling.

Key Observations:
Phase Transitions: During heating, metals may undergo phase transformations, such as solid-to-liquid changes, shifts in crystal structure, or new phase formations.
Diffraction Patterns: Changes in diffraction patterns—shifts, broadenings, or disappearances of peaks—indicate structural transitions in the material.
Microstructural Evolution: This analysis helps track melting points, solidification processes, grain formation, and phase transitions, offering insight into the microstructural evolution of metals.
In-Situ Research Significance
In-situ diffraction studies provide dynamic data that static experiments cannot, proving valuable for applications in alloy design and AM. Understanding microstructure manipulation enables enhancements in material properties, such as fatigue and wear resistance, crucial for AM components.

LIPRAS Analysis:
This repository includes an analysis focused on the 002 diffraction plane, chosen for its ease of tracking. The analysis collects 2𝜃 values, intensity, and Full Width at Half Maximum (FWHM) data. Using this data, a custom code outputs a graph depicting volume change over time, which can reveal insights into the microstructural evolution.

Goals of LIPRAS Analysis:
Track structural alterations over time.
Assess the mechanical properties of AM components in relation to their microstructure (grain size, orientation, phase distribution).
Optimize AM parameters, such as cooling rates, laser velocity, energy input, and layer thickness, to refine microstructure and phase distribution, enhancing overall material performance.
