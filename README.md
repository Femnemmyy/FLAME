# FLAME
Analytical model of flame deflector environment for rocket engine testing

Uses a combination of the [1], [2], and [3] to implement heat flux calculations and shock calculations to derive flow conditions between the exit of the rocket nozzle to the surface of the deflector. Requires the use of RPA or another simulation tool to find the conditions and properties of the flow at nozzle exit. Addiitonally, heat flux can be used to calculate surface temperature using [4] or importing a simplified thermal model created using FEA data.

[1] - A Simple Equation for Rapid Estimation of Rocket Nozzle Convective Heat Transfer Coefficients, Bartz, 1957
[2] - LAUNCH DEFLECTOR DESIGN CRITERIA AND THEIR APPLICATION TO THE SATURN C-1 DEFLECTOR, Evand and Sparks, 1963
[3] - Engineering Relations for Heat Transfer and Friction in High-Velocity Laminar and Turbulent Boundary-Layer Flow Over Surfaces With Constant Pressure and Temperature, Eckert, 1956
[4] - Flame Deflector Design, Standard For, Phillips, 1990
