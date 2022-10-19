**2D Position estimation using trilateration from time of flight sensors and least squares optimization.**

trilaterion/math.py accepts a .txt file with a list of radii of measurements from the time of flight sensors in the area of interest and performs trilateration over these radii based on the number of senors. Least squares optimization gives a 2D location along with a radius of uncertainity as the output.

A sample example with readings from 3 time of flight sensors over 6 locations is provided in this repository. result_1.txt contains the readings from the sensor which is then processed in math.py and the output visualization images and gif is saved in the visualization folder.
