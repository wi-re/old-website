# Particle Methods and Applications Conference 2024

The Slides: https://docs.google.com/presentation/d/1W1yhR9dHK5ysy2fIDsSPK6_JHSIFXYCW/edit#slide=id.p1

Our recent (May 2024) paper published at ICLR 2024: https://openreview.net/forum?id=HKgRwNhI9R

Last Years live demo from SPHERIC 2023 (Rhodes) using Continuous Convolutions to learn a kernel function: https://colab.research.google.com/drive/1wdJoWvu1U5pftkjpjG0gb0ldSh5-CgDX (if the code doesnt work contact me please)

If you have any suggestions or ideas or collaboration ideas contact me via email at rene.winchenbach at tum.de or find me on linked in: https://www.linkedin.com/in/rene-winchenbach-56a217257/ 

Interesting reads if you are interested in more machine learning in physics:
- Learning Lagrangian Fluid Mechanics with Continuous Convolutions: the baseline of our current research https://openreview.net/forum?id=B1lDoJSYDH 
- Guaranteed Conservation of Momentum for Learning Particle-based Fluid Dynamics: a follow up work on the prior paper that builds in hard constraints to ensure conservation of momentum https://arxiv.org/abs/2210.06036
- Physics informed machine learning with Smoothed Particle Hydrodynamics: Hierarchy of reduced Lagrangian models of turbulence: The paper presented by Michael Woodward at PMAC https://arxiv.org/abs/2110.13311
- Message-Passing Neural PDE Solvers: A state of the art graph based neural network approach to solving generic PDEs https://openreview.net/forum?id=vSix3HPYKSU

What we plan on doing next:
- Hybrid solvers, e.g., low order SPH method + Neural network corrections to achieve higher order accuracy
- Investigating more general Radial Basis Function Networks for particle mechanics
- Learning specific subparts of an SPH simulation that are really expensive, e.g., the recent iterative particle shifting method
- Publishing our dataset (after some more work to make it more representative) as a dataset paper