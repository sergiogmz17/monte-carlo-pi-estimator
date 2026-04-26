# Monte Carlo Pi Estimator (Java)

[cite_start]This project uses a Monte Carlo simulation to estimate the mathematical constant $\pi$. [cite_start]By using random sampling and coordinate geometry, the program provides an approximation based on the ratio of points that fall within a circular area versus a square area[cite: 9, 10].

## Features
- [cite_start]**Large Scale Simulation**: Generates 100,000 random points for each simulation run.
- [cite_start]**Coordinate Geometry**: Uses the Pythagorean theorem ($d = \sqrt{x^2 + y^2}$) to determine point placement.
- [cite_start]**Accuracy Analysis**: Calculates percentage error against `Math.PI` to verify precision[cite: 10].
- [cite_start]**Multiple Runs**: Supports running the simulation multiple times to calculate a stable average[cite: 11].

## The Math Behind It
1. [cite_start]A square is defined with a range of [-10,000, 10,000] for both X and Y.
2. [cite_start]Points are randomly generated within this square.
3. [cite_start]The program checks if the distance from the center (0,0) is less than or equal to the radius (10,000).
4. [cite_start]$\pi$ is estimated using the formula: $4 \times (\text{Points inside Circle} / \text{Total Points})$[cite: 10].

## How to Run
[cite_start]This project was developed using **BlueJ**. 
1. Open the project in any Java IDE.
2. Create an instance of the `EstimatePi` class.
3. [cite_start]Call `runSimulation(int numRuns)` to execute the simulation and view the results in the console[cite: 11].

## Skills Demonstrated
- Java Programming (Arrays, Randomization, Math class)
- Simulation Modeling
- Statistical Analysis & Error Calculation
