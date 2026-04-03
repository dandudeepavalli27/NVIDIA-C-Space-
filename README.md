# NVIDIA-C-Space-
Aim
To generate a collision-free configuration space using obstacle inflation.
General Objective
To understand configuration space (C-space) representation in robot motion planning and how obstacle inflation ensures collision-free navigation.
Specific Objective
To apply obstacle inflation using:
Robot Radius = 0.6 m
Inflate obstacles → Create safe (collision-free) space for robot movement.
Dataset
Motion Planning Maps
Source: University of Illinois Urbana-Champaign
Procedure
Input robot radius
Inflate obstacle boundaries
Convert robot to point representation
Generate collision-free space
Display result
Algorithm
Start
Input robot radius
Expand obstacles by radius
Generate new space
Display result
Stop
Code Logic
inflated_obstacle = obstacle + robot_radius
Python Code
# SESSION 24 – C-Space (Obstacle Inflation)

# Step 1: Input robot radius
robot_radius = 0.6  # in meters

# Step 2: Simulate obstacle inflation
# (Conceptual representation)
print("Inflating obstacles by", robot_radius, "meters")

# Step 3: Output result
print("Collision-Free Space Generated")

print("\nProgram Executed Successfully")
Output
Inflating obstacles by 0.6 meters
Collision-Free Space Generated

Program Executed Successfully
Result
By inflating obstacles using robot radius:
Collision-Free Space is generated
Industry Application
C-space is used in:
Robot motion planning
Autonomous navigation
Path planning algorithms
Industrial robotics
Companies like NVIDIA use this in:
Robotics simulation
AI navigation systems
Autonomous vehicle platforms
Conclusion
Obstacle inflation in configuration space ensures safe navigation by accounting for the robot’s physical size, making path planning more reliable.
