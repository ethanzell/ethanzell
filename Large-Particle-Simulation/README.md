This folder is for any files I have related to simulation of large particle systems. 

The kind of particle system of interest here is: symmetric (all particles/agents have the same dynamics), controlled, finite-state, continuous-time. 
Each particle has state space $[d]:\{1,\dots, d\}$ and when there are $n$ particles the particle process has state space $[d]^n$. When we consider the proportion of players in each state (of $[d]$), it makes sense to talk about a notion of distance between states (of $[d]^n$) in the Euclidean sense by considering the empirical measure process of the particles/agents. 

In Large_Particle_Simulation.iypnb
  The notebook builds several functions to simulate a large particle system with various options for controls. Then it allows you to compute the hitting times for a state of a certain distance from your starting state.  
  
