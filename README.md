# Autonomous Motions Template

This repository contains the code for our robot in the 2025-2026 Vex Robotics season Push Back.

## Features
- Position tracking via Odometry.
- Driving to points on a coordinate system while using a sigmoid function to maintain heading as it approaches the target.
- A boomerang controller to drive to a point with a specified final heading.
- Turning to a specified heading or coordinate.
- A PID controller for all our motions.
- An interpolated look up table (InterpLUT) to tune PID constants in real time while the autonomous is running.
- A 1D motion profile for accelerating, crusing at a maximum velocity, and then decelerating to the final velocity.
- A 2D motion profile that generates a trajectory from a Cubic Bezier curve, finds the velocities at each point, and compensates for centripetal force while turning.
- Other driver code for controlling the chassis and other subsystems.
