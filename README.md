# Black_hole_simulation

Black Hole M87 Simulation

This project is a visual simulation of a black hole, inspired by the supermassive black hole M87. The simulation leverages Python and the Pygame library to create a simple yet accurate representation of gravitational effects on photons (particles of light) as they pass near the black hole. The project incorporates physical constants and principles, such as gravitational pull, escape velocity, and relativistic effects, to model how light behaves around the black hole.

Features
	1.	Event Horizon Visualization:
	•	The event horizon of the black hole is represented as a dark circle, corresponding to the Schwarzschild radius, beyond which nothing can escape.
	2.	Photon Path Simulation:
	•	Photons are emitted from a source at the edge of the screen and travel toward the black hole.
	•	Their paths are dynamically altered due to the immense gravitational pull of the black hole.
	3.	Accretion Disk Representation:
	•	Surrounding the black hole is a colorful accretion disk, modeled to visually simulate the appearance of hot gases swirling around the event horizon.
	4.	Physics-Based Interaction:
	•	Relativistic corrections and gravitational lensing effects are applied to photon trajectories based on the mass of the black hole and the distance of the photons.
	5.	Dynamic Visualization:
	•	The photons’ paths are displayed in real-time, showing how they either orbit, escape, or get pulled into the black hole.

Technical Details
	•	Programming Language: Python
	•	Library Used: Pygame for graphical rendering and physics simulation.
	•	Constants Used:
	•	Speed of light (c)
	•	Gravitational constant (G)
	•	Black hole mass (m)
	•	Core Classes:
	•	BlackHole: Represents the black hole, its position, mass, event horizon, and its gravitational pull on photons.
	•	Photon: Represents a particle of light, with properties like position, velocity, and trajectory history.

How It Works
	1.	The BlackHole class defines the black hole’s position, mass, event horizon, and the gravitational force it exerts on nearby objects.
	2.	The Photon class models individual particles of light. Each photon starts with an initial position and velocity, and its trajectory is updated frame by frame based on gravitational forces.
	3.	The simulation initializes multiple photons, launching them toward the black hole from varying distances.
	4.	As photons approach the black hole, their paths bend due to gravitational lensing. Photons close to the event horizon may get absorbed, while others escape with curved trajectories.
	5.	The visual output is a dynamic display of photon paths around the black hole, highlighting gravitational lensing effects.

How to Run
	1.	Clone this repository:

git clone https://github.com/yourusername/blackhole-m87-simulation.git
cd blackhole-m87-simulation


	2.	Install the required dependencies:

pip install pygame


	3.	Run the simulation:

python blackhole_m87_simulation.py


	4.	Enjoy the mesmerizing visuals of photons interacting with the black hole’s gravitational field!

Future Improvements
	•	Implementing additional relativistic effects, such as time dilation.
	•	Enhancing the accretion disk visuals with more realistic textures and animations.
	•	Allowing user interaction to adjust black hole properties (mass, size) or photon launch positions.
	•	Adding background stars and other cosmic elements for an immersive experience.

This project is an excellent starting point for understanding black holes and gravitational physics, as well as exploring Pygame’s capabilities for scientific simulations.
