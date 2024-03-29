# Central trajectory

This project is to compute central trajectories with different methods.

## File List
* functions.py
* minmaxradiuscircle.py
* demoMeanMinCircle.py
* demoPercentMinCircle.py
* demoTrajGraph.py

## How to run demo files
* functions.py and minmaxradiuscircle.py are header files (not for running).

1. Open a terminal.
2. Go to the directory where all files are saved.
3. Type '''python3 filename.py’’’ for demo———.py files to run the demonstration.

### function.py
* This file includes functions that are used to compute central trajectories.

### minmaxradiuscircle.py
* This file includes functions that are used to compute the minimum radius enclosing circle.

### demoMeanMinCircle.py
* This demo presents the minimum radius enclosing ball of 100% data, its center and the average point as a new point is added by the user.
* Input: The x and y coordinates of the starting point.
* Output: Minimum radius enclosing ball that includes all data, its center, and the average point of user clicked data points.

### demoPercentMinCircle.py
* This demo presents the minimum radius enclosing ball using user specified percentage of data and the minimum radius enclosing ball of 100% data as a new point is added by the user.
* Input: The x and y coordinates of the starting point and the percent of data that the user wants to include.
* Output: One minimum radius enclosing ball that includes all data (red), its center (red), one minimum radius enclosing ball
         that includes specified percent of data (blue), and its center (blue).

### demoTrajGraph.py
* This demo presents 3D graphs original trajectory, minimum radius circle trajectory, user specified percent subset minimum radius circle trajectory, and average trajectory.
* Input: The number of time steps, x-perturbation constant, y-perturbation constant, and the percentage of data points that the user wants to include.
* Output: 3D graphs of original trajectory (black), minimum radius circle trajectory (blue), subset minimum radius circle trajectory (green), and average trajectory (red) using 100 generated trajectories.
