# Unreal Engine 5.1 Interactive Water

**This project contains some fixes of Unreal Engine Water plugin**

> :warning: Before pressing PIE button open this blueprint: `/Engine/Plugins/Experimental/Water/Content/FluidSimulation/Materials/Simulation/M_Fluid_Sim_01.uasset` in the blueprint, find the FoamForceRT node and in the parameters of this node change FoamForceRT to `FoamRT`

### Fixed

- Follow Player functionality
- Making ripples on different water heigth (different water Z-axis) for *Dynamic forces*
- Making ripples on different water heigth (different water Z-axis) for *Dynamic forces* with sockets

### Features
- Boat example
- Character example
- Dynamic force example
- Projectile force example

### TODO
- Fix shallow water simulation
- Fix river foam
