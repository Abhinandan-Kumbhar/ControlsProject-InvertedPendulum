## Summary
### Problem
![Problem](https://github.com/Abhinandan-Kumbhar/ControlsProject-InvertedPendulum/blob/main/problem.PNG)

Consider a modified scenario where the pivot of the pendulum is attached to the top a cart that can move along the x-direction as shown in the figure. 
The cart is driven by an engine which exerts a horizontal force  F . in addition, the cart also experiences a resistance  f  due to its motion.  
An LQR controller needs to be designed for regulating the force exerted, so that the pendulum can be stabilized in the inverted position. 
The controller should work even if the pendulum is off the vertical or the cart is moving initially.

##Tasks
1. Studied the dynamics of problem and obtained governing differential equations and determined the rate of change of state  
2. Found out the fixed points and linearized about the desired fixed point  
3. Checked for stability of the fixed point and controllability about the fixed point  
4. Designed a LQR controller based on the results obtained above using suitable cost matrices  
5. Solve for the state from the differential equations and plot the behaviour of the different state components  
6. Create a graphical simulation of the pendulum-cart system.  
7. Create a block diagram of the linearized system in Simulink and analyze its behaviour.  

MATLAB codes
**pendcart_abhinandan.m**  --  contains the code describing the rate of change of the state of the system  
**sim_pendcart_abhinandan.m** --  contains the code with the different parameters, initial conditions, matrices, LQR controller, differential equation solver and graph plotter  
**disp_pendcart_abhinandan.m** --  contains the code for making the graphical simulation of the system  
**pendcartsim_abhinandan.slx** --  contains the Simulink block diagram of the system  

![Demo](https://github.com/Abhinandan-Kumbhar/ControlsProject-InvertedPendulum/blob/main/Demo.mp4)
