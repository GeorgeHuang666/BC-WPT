# BC-WPT
The netlists give the empirical circuit model of multi-node BC-WPT. Model parameters can be adjusted as needed.

SSSH: one source and one harvester deployed on human body.

SSMH: one source and multiple harvesters deployed on human body.

SSMH-SA: multiple harvesters are on the same side of the source.

SSMH-OP: multiple harvesters are on the opposite side of the source.

The empirical circuit model consists of the source, the harvesters, the forward path, and the backward path. The source is modeled as the voltage source V<sub>s</sub> and the source resistor R_s. The resistor of the electrode and the contact resistor between electrode and skin are denoted by R_e. The harvester consists of the bridge-structure rectifier and the load of R_{load} and C_{load}. The forward path is modeled as an RC network consisting of R_{arm}, C_{arm} and C_{leak}, where C_{leak} refers to the coupling capacitor between the arm and the ground plane. The backward path consists of two parts. One is the coupling capacitor C_{air} between the floating ground electrodes. The other is the coupling capacitor C_{tgG} and C_{rgG} between the floating ground electrodes of source and harvester and the external ground plane. C_{tsg} refers to the coupling capacitor between the signal and ground electrodes of the source while C_{rsg} refers to the coupling capacitor between the signal and ground electrodes of the harvester. The parameters of R_{arm}, C_{arm}, C_{leak}, C_{tsg}, C_{rsg}, and C_{air} are extracted from CST.
