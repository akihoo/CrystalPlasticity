# CrystalPlasticity
CP UMAT and CZM UEL for Abaqus full details in: https://doi.org/10.1016/j.ijsolstr.2024.113110 

The latest version of single crystal solver

Inputs (PROPS)

PROPS(1): phi1 - 1st Bunge angle

PROPS(2): PHI  - 2nd Bunge angle

PROPS(3): phi2 - 3rd Bunge angle

PROPS(4): grain-ID

PROPS(5): material-ID

PROPS(6): "0" for using usermaterials.f / "1" for manual entry to PROPS


The user entries are given in userinputs.f / useroutputs.f / usermaterial.f files


Video Tutorials
1. Single crystal uniaxial test: https://youtu.be/T1bCw61qMLw

2. Dream3D2Abaqus polycrytal plasticity: https://youtu.be/s0r0Tgjc7Io
   
3.a. Neper polycrystal mesh generation: https://youtu.be/zAH1m9wIT_4

3.b. Neper2Abaqus polycrystal plasticity: https://youtu.be/FfixSufVZ30



References for the solver:

https://doi.org/10.1016/j.ijplas.2006.10.013

https://doi.org/10.1016/j.ijmecsci.2009.03.005

https://doi.org/10.1016/j.ijplas.2023.103773

References for the GND calculation:

https://doi.org/10.1016/j.ijplas.2018.05.001

https://doi.org/10.1016/j.ijplas.2024.104013
