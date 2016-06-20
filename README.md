# 3D N-body Simulation using WebGL
This was my final project for CSCE470 - Computer Graphics. It is a 3D gravitational N-body simulation written in JavaScript using WebGL, so it runs in any web browser that supports WebGL. A detailed decription of the implementation can be found in the writeup. The simulation is [posted here](http://cse.unl.edu/~drempe/CSCE470/finalProject/src/nBody_sim.html) if you'd like to check it out without cloning.

![Simulation Running](https://github.com/davrempe/webgl-nbody-sim/tree/master/Common/images/screenshot.png "Example of simulation running")

# To Run After Cloning:
* Place the contents of the repository on a local server to run.
	* Most browsers won't let you properly open the HTML page from your local file system due to "security concerns" when the application tries to access the textures directory. This is why a localhost is necessary.
* Open `src/nBody_sim.html` to run the application.

# Controls:
* _LEFT-MOUSE_ drags will rotate the simulation, and you can zoom in and out using _MIDDLE-MOUSE_ button drags.
* <kbd>CTRL</kbd>+_LEFT-MOUSE_ drag will pan over the simulation.
* Ability to start, stop, and parameterize the simulation are all included in the UI on the right side of the page.
