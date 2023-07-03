# PHY 553: Computational Physics
# Colin Recker, Creighton Physics Department 2023
IPython Notebook Files used for Computational Physics Class

Libraries used: NumPy, SciPy, SymPy

These are the .ipynb files that I used throughout my computational physics course PHY553. The homework assignments explored various techniques utilized throughout physics numerical modeling and simulations. The final project utilized learned techniques to study resonance effects in a modified double pendulum system.

## Modelling Resonance in the Modified Double Pendulum
This was my final project for the course that hinged upon numerical solutions to the chaotic system of the double pendulum. 
The nonlinear equations of the double pendulum system were solved numerically and an animation was created to showcase the chaotic nature of the double pendulum.

This system was extended by adding oscillatory translational motion to the upper pendulum. This increased the complexity of the derivation for the equations of motion, so SymPy was used to analytically find these equations of motion.
With this modified system, the equations of motion were solved numerically across a range of driving frequencies for the translation stage of the double pendulum. The average kinetic energy was calculated at each driving frequency, which was taken as a measure of resonance in the system. The driving frequency that corresponded to the highest average kinetic energy was determined to be the resonant driving frequency of the system, which was again animated to showcase the resonant behavior of the extended double pendulum system.

![](https://github.com/colinrec34/PHY553/blob/master/Double_Pendulum/animation.gif)

## Topics Covered in Homeworks
Algorithms, data visualization, data fitting/statistics, computational optimization, 3D graphics/animations, numerical solutions for integrals and linear/nonlinear differential equations, discrete Fourier transforms, Monte Carlo-Markov Chain Methods, Fast Fourier Tranforms, Relaxation Methods
