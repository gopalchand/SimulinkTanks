# SimulinkTanks
MATLAB Simulink simulation of logic to control valves filling two water tanks

PW is power to pump
V1 is the control for valve 1 leading to tank 1 (low => closed) and V2 to tank 2
D1 is the water level detector for tank 1 (high => tank full) and D2 for tank 2

When both V1 and V2 are low, tanks 1 and 2 are full and the simulation stops

Tanks are simulated by an integrator
