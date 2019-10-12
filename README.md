# BC-WPT
The netlists give the empirical circuit model of multi-node BC-WPT. Model parameters can be adjusted as needed.

SSSH: one source and one harvester deployed on human body.

SSMH: one source and multiple harvesters deployed on human body.

SSMH-SA: multiple harvesters are on the same side of the source.

SSMH-OP: multiple harvesters are on the opposite side of the source.

The empirical circuit model consists of the source, the harvesters, the forward path, and the backward path. The source is modeled as the voltage source V<sub>s</sub> and the source resistor R<sub>s</sub>. The resistor of the electrode and the contact resistor between electrode and skin are denoted by R<sub>e</sub>. The harvester consists of the bridge-structure rectifier and the load of R<sub>load</sub> and C<sub>load</sub>. The forward path is modeled as an RC network consisting of R<sub>arm</sub>, C<sub>arm</sub> and C<sub>leak</sub>, where C<sub>leak</sub> refers to the coupling capacitor between the arm and the ground plane. The backward path consists of two parts. One is the coupling capacitor C<sub>air</sub> between the floating ground electrodes. The other is the coupling capacitor C<sub>tgG</sub> and C<sub>rgG</sub> between the floating ground electrodes of source and harvester and the external ground plane. C<sub>tgG</sub> refers to the coupling capacitor between the signal and ground electrodes of the source while C<sub>rgG</sub> refers to the coupling capacitor between the signal and ground electrodes of the harvester.
