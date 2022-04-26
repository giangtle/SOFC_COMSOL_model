# SOFC_model
Compilation of different physics-based models of solid oxide fuel cell.

### Planar cell
The [folder](/COMSOL/planar_cell/)(/COMSOL/planar_cell/) includes COMSOL model of a planar cell in the 2D of width and length, detail description of the which can be found in this open access [journal](https://iopscience.iop.org/article/10.1149/1945-7111/ac59f4/meta).
Main physics:
* Gas transport from diffusion, electrochemical reaction, convection (<img src="https://latex.codecogs.com/svg.image?H_2,H_2O,O_2" /> ).
* Heat of reaction and heat transfer between a lumped solid and gas phases.
* Electrochemistry: Ohmic resistance, an RC element for electrode resistance and Nernstian chemical thermodynamical relationship.
* Frequency domain solution to the electrochemical impedance spectroscopy (EIS) response.

Snapshots:
<p align="center">
<img src="/images/planar_yH2.png" width="33%"><img src="/images/planar_Ts.png" width="33%"><img src="/images/planar_jF.png" width="33%">
</p>

<p align="center">
<img src="/images/planar_mole_frac.png" width="33%"><img src="/images/planar_EIS.png" width="33%"><img src="/images/planar_Bode.png" width="33%">
</p>

### Button cell
The [folder](/COMSOL/button_cell/)(/COMSOL/button_cell/) includes COMSOL model of a button cell in a test setup.
Main physics:
* Gas transport of the fuel gas, a mixture of <img src="https://latex.codecogs.com/svg.image?H_2,H_2O,N_2" /> (the oxidizing environment is assume to be fixed).
* Electrochemistry: Ohmic resistance, RC or Gerischer element to respresent electrode resistance and Nernstian chemical thermodynamical relationship.
* Frequency domain solution to the electrochemical impedance spectroscopy (EIS) response.

Snapshots:
<p align="center">
<img src="/images/button_yH2.png" width="33%"><img src="/images/button_yH2O.png" width="33%"><img src="/images/button_velocity.png" width="33%">
</p>

<p align="center">
<img src="/images/button_jF.png" width="33%"><img src="/images/button_EIS.png" width="33%"><img src="/images/button_Bode.png" width="33%">
</p>
