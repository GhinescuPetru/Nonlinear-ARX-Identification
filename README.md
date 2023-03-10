# Nonlinear-ARX-Identification

A dataset is given, measured on an unknown dynamic system with one
input and one output. The task of this project is to create a black-box
model for this system, using a nonlinear ARX model that is a polynomial
in the previous inputs and outputs. A second data set measured on the
same system is provided for validating the developed model. The ARX
model was generated for configurable model orders and polynomial
degree on the identification data(the first data set) and then validated
on the second data set using two mods:
-one-step-ahead prediction, which uses knowledge of the real delayed
outputs of the system;
-simulation, in which knowledge about the real outputs is not
available, so we can only use previous outputs of the model itself.
The best ARX model it's chosen based on the mean squared error
between the real output and the output generated by the model. The
project was made using Matlab.
