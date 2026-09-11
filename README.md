# OpenMENA

This repository contains the supplementary material of the preprint paper "OpenMENA: An Open-Source Memristor Interfacing and Compute Board for Neuromorphic Edge-AI Applications" by Ali Safa et al., College of Science and Engineering, Hamad Bin Khalifa University, Doha, Qatar.


The BOM can be generated from the schematic in KiCAD.

**Some details:**

Potentiometers use 20K 10 turns;
Pull down for the crossbar use 2.2k;
Gain setting resistors for the amplifiers use 12k;
In the back, use 500 ohm for R30 see picture attached, while leaving the R29 pad untouched.

**Small Required Modification to the PCB**

Please solder together pads 12 and 13 of both U12 and U13 (this was mistakenly ommitted in the first version of the PCB)

If you are using this work, please cite as follows:

Ali Safa, Farida Mohsen, Zainab Ali, Bo Wang, & Amine Bermak. (2026). OpenMENA: An Open-Source Memristor Interfacing and Compute Board for Neuromorphic Edge-AI Applications. 2026 IEEE 8th International Conference on Artificial Intelligence Circuits and Systems (AICAS), Ha Long Bay, Vietnam, 2026 (in press)

The pre-print of the paper can be found in the link below:

https://arxiv.org/abs/2511.03747





