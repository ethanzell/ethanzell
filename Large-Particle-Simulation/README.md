This folder is for any files I have related to simulation of large particle systems. 

The kind of particle system of interest here is: symmetric (all particles/agents have the same dynamics), controlled, finite-state, continuous-time. 
Each particle has state space $[d]:= \lbrace 1,\dots, d \rbrace$ and when there are $n$ particles the particle process has state space $[d]^n$. When we consider the proportion of players in each state (of $[d]$), it makes sense to talk about a notion of distance between states (of $[d]^n$) in the Euclidean sense by considering the empirical measure process of the particles/agents. That is, if the agents are listed as $X^1_t, \dots, X^n_t$, then the empirical measure of the process is defined as:
$$\mu^n_t := \sum_{i=1}^n \delta_{X^i_t},$$
where $\delta$ is the dirac measure. The hitting time we mention is for $\mu^n_t$; it is defined as:
$$\tau := \inf \lbrace t\geq 0: \mu^n_t \not \in B_{\delta}(\mu^n_0) \rbrace.$$ 

In Large_Particle_Simulation.iypnb
  The notebook builds several functions to simulate a large particle system with various options for controls. Then it allows you to compute the hitting times for a state of a certain distance from your starting state. The visualization in this notebook is for:
  $$\mathbb{P} (\tau \leq t).$$
  
