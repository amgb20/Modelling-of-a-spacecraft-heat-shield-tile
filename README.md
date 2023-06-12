# Modelling-of-a-spacecraft-heat-shield-tile

The report highlights the simulation of heat equations that dene the heat 
ow through a
space shuttle's insulation tile. Matlab was used to implement 4 dierent methods relying on
Fourier's heat equations.
The program showed that the best method is Crank-Nicolson as it has the smallest inac-
curacies (O(x2;t2)). We could conclude that this method is unconditionally stable [4] and
has the smallest divergence from the given temperature of 450 Kelvin. Therefore, the time
step stability nt and spatial step stability nx were found being respectively 941 number of
timesteps and 4 number of spatial steps. A shooting method, studied during the rst semester,
was created to have the maximum thickness required for the desired temperature; a maximum
thickness of 0.568mm was computed for a temperature of 450K which is the one we are not
allowed to exceed.

However, the primary tasks were made with some assumptions that were given. To have a
deeper analysis of the concept, some enhancements have been created to reinforce the code's
accuracy. You will nd everything in the GUI.
