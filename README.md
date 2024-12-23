- 👋 Hi, I’m @Lemmiegabe
- 👀 I’m interested in science fiction
- 🌱 I’m currently learning Physics
- 🔎 Overview: 	

This Python project is an N-body simulation designed to model and visualize the gravitational interactions of celestial bodies using symplectic integration methods. It features a variety of predefined configurations, real-time visualization, and energy diagnostics.

- 👀 Features:

Predefined configurations: Simulate scenarios such as the Sun-Earth-Moon system, equal-mass orbits, Broucke orbits, Lagrange points, and more.
Real-time visualization: View the dynamics in three 2D projections (XY, YZ, XZ) as the simulation progresses.
Energy diagnostics: Monitor total energy and angular momentum to evaluate system stability and integration accuracy.
Custom scenarios: Create and simulate your own initial conditions by editing the configurations.
GIF export: Generate animated GIFs of the simulation.
Requirements

Python Packages:
> numpy
> matplotlib
- 🪐 Configurations:
  
The project relies on additional Python files for predefined configurations:

broucke_orbit_config.py
equal_mass_orbit_config.py
figure_eight_orbit_config.py
jupiter_ganymede_io_config.py
lagrange_equilateral_config.py
random_cluster_with_center_config.py
solar_system_config.py
stable_orbit_test_config.py
sun_earth_moon_config.py
earth_moon_lagrange_config.py
earth_moon_lagrange_rotating_config.py
earth_moon_config.py
fisrt_part_config.py
Make sure these files are included in the same directory as the main script.

How to Run

Clone the repository or download all required files.
Install dependencies:
> pip install numpy matplotlib
Run the script:
> Verlet_Integrator.py
Choose a configuration from the menu and specify the simulation time and time step.

Menu Option:

When prompted, choose a configuration by entering the corresponding number:

Sun-Earth-Moon: Models the three-body interaction of the Sun, Earth, and Moon.
Equal Mass Orbit: Simulates equal-mass celestial bodies in orbit.
Figure-Eight Orbit: Simulates the iconic three-body figure-eight orbit.
Broucke Orbit: A specific three-body orbital configuration.
Lagrange Equilateral: Models a stable Lagrange point configuration.
Jupiter-Ganymede-Io: Simulates the interaction of Jupiter with its moons Ganymede and Io.
Solar System: Models the inner solar system.
Random Cluster: Generates a random cluster of celestial bodies with a central mass.
Earth-Moon Lagrange: Computes Earth-Moon Lagrange points.
Earth-Moon Lagrange (Rotating Frame): Models Lagrange points in a rotating reference frame.
Stability Test: Runs a stability test for a predefined system.
Two-Body (Earth-Moon): A simple two-body simulation.
Two Large Bodies with Small Particle: Simulates the dynamics of two massive bodies with a small test particle.
First_part_config.py: stability test- stable two body and input the intial condition of the third body.

Output

Real-Time Plot: Displays real-time trajectories in 2D projections.
Energy Diagnostics: Prints energy and angular momentum details to the console.
GIF Animation: Saves a GIF animation of the simulation as L1.gif.
Customization (optional)

Modify configurations in the imported files to define new scenarios.
Adjust simulation parameters, such as t_span, dt, and epsilon in the main script.
Enhance or customize visualization by editing the plotting sections.
Example

Here is a sample workflow for simulating the Sun-Earth-Moon system:

Run the script and choose Option 1 from the menu.
Input simulation time (e.g., 100) and time step (e.g., 1e-3).
Observe real-time plots and system diagnostics in the console.
View the saved animation in L1.gif(optional).
Troubleshooting

Missing configuration files: Ensure all configuration scripts are present in the directory.
Inconsistent energy diagnostics: Experiment with a smaller dt or adjust the softening parameter epsilon.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

