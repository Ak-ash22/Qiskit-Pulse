# Qiskit-Pulse
This repository is a guide to creating custom quantum gates by using qiskit pulse programming kit.

This project is aimed at creating custom quantum gates from pulse-level programming, which would provide user with higher precision control over quantum hardware than circuit-level programming. The idea of the project is to study the various pulse waveforms and their corresponding parameters and then be able to create a custom gate by obtaining a pulse schedule for a defined set of parameters. The result of the custom gate was then visualized by obtaining the number of counts or the histogram. This has been achieved in IBMQ Armonk backend (which is deprecated now). The project further includes the idea of finding the required instruction set for the desired output statevector, which can be used to build a pulse schedule and calibrate it to prepare a custom gate.

This project is licensed under the terms of the Apache-2.0 license.
