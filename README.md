CIS-563-Smoke-Simulation
========================
I implemented Physically Based Smoke Simulation using C++.  
It is implemented using semi-langrangian system. The simulator uses MAC grid structure in which velocity was stored on the faces between grid cells and density, pressure is stored at center of grid cells.   
The system includes the implementation of advection of velocity, pressure projection, cubic interpolation, euler integration, incomplete cholesky preconditioner for the conjugate gradiant, buoyancy forces, and vorticity confinement. 
