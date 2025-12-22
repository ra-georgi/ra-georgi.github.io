---
title: "3D-Planning-and-Control"
excerpt: "Simulate Quadrotor flight using different control techniques in different scenarios.<br/><img src='/images/QS.gif'>"
collection: portfolio
---

<img src="/images/QS.gif" style="display: block; margin-left: auto; margin-right: auto; max-width: 600px;">
<p style="text-align: center; font-size: smaller;"><a href="https://github.com/ra-georgi/3D-Planning-and-Control">Project Link</a></p>

* Developing a modular and extensible Python tool for simulating quadcopter motion and experimenting with 
different motion planning and control techniques 
* Currently implemented features:  
 Simulation: Set actuator limits, actuator delays, waypoints, wind disturbances (constant or Gaussian), obstacles (spherical)  
 Planning: Dijkstra, A*, RRT*, iLQR (Iterative Linear Quadratic Regulator) 
 Control: Cascade PID, LQR (using JAX for autodiff), linear MPC (using Casadi for optimization) 
 Visualization: Plots of state variable evolution with time, animation of quadcopter flight 