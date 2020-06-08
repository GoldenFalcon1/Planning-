# Model Documentation

This file contains the documentation for the **Planning Project**.

## Task Description

The goal in this project is to **build a path planner that is able to create smooth, safe trajectories** for the car to follow. The highway track has other vehicles, all going different speeds, but approximately obeying the 50 MPH speed limit.

The car transmits its location, along with its sensor fusion data, which estimates the location of all the vehicles on the same side of the road.

## What is the Path

A **trajectory** is constituted by as set of (x, y) points. Every 20 ms the car moves to the next point on the list.
In this framework, the car moves from point to point perfectly.

Since the car always moves to the next waypoint after 20ms, the **velocity** of the vehicle is given by how much future waypoints are spaced.
In other words, the larger the space between waypoints, the faster the car will be.

