# Displacement Based Dynamics
I have been writing physics simulation software for over 10 years, mostly focussing on real time rigid body simulation. Over the years I've written up some notes, mostly for myself, but also to help new people coming into the team. This is a soomewhat formal writeup of some of those notes.

Contents:
- A derivation of position based dynamics via discretizing the equations of motion coming from constrained Lagrangian dynamics
- Some tricks on how to improve and stabilize the solver, e.g. relaxation, regularization and using a non-linear iterative update
- A derivation of adding non-linear forces to the simulation (e.g. spring/damping), again using first order linearization to solve the system. As a byproduct, this shows how XPBD can be derived in a general way

This method can be applied to a variety of physics simulation. I show its use for Rigid Bodies, Particles, Soft Bodies, and finally for a physics based IK solver.
