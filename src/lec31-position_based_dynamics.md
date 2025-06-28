# Position Based Dynamics Framework
" Classical dynamics simulation methods formulate the change of
momentum of a system as a function of applied forces, and evolve
positions through numerical integration of accelerations and velocities. Position-based approaches, instead, compute positions directly, based on the solution to a quasi-static problem."

"Position-based methods are tailored particularly for use in interactive environments. They provide a high level of control and are
stable even when simple and fast explicit time integration schemes
are used."

"In this tutorial we focus on position-based simulation methods
which omit the velocity and acceleration layer and directly modify the positions."

In this section we present Position-Based Dynamics (PBD), an approach which omits the velocity and acceleration layer and immediately works on the positions [MHHR07]. We will first describe
the basic idea and the simulation algorithm of PBD



