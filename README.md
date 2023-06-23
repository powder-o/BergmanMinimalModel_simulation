# BergmanMinimalModel_simulation
This is a simplified simulation of Glucose and Insulin kinetics in the human body using Bergman Minimal Mathematical model.

## Bergman’s Minimal Model
A model to show how glucose and insulin concentrations change in the blood over time using ordinary differential equations. Bergman’s minimal model was created in the eighties by Richard N. Bergman. He is currently the Director of the Cedars-Sinai Diabetes and Obesity research Institute in Los Angeles, California. Dr. Bergman created the Bergman minimal model as an approach to understanding the effects of insulin secretion and sensitivity on glucose tolerance.

The model was initially used in studies using animals. It was stated by Godsland that animals, specifically dogs, have appreciably higher pancreatic insulin response to glucose (Pacini). When the model was initially applied in humans, the response was inadequate for people with type 2 diabetes. However, the minimal model is still used because there were a variety of solutions to the problems involved with the model. There are many people approaching the model in different ways to better estimate parameter values associated with the model.

Equation (1) represents the physiological factors that determine the restoration of plasma glucose after injection: the effect of Glucose (P1), and the effect of active insulin (X), which acts to return glucose to its respective basal level. Equation (2) represents the flow of insulin from plasma into the interstitial compartment (Bergman, 2005). The interstitial compartment contains two parameters: P2 and P3. Equation (3) describes the release of insulin in respect to the amount of glucose that has been injected. This particular equation also relates to the amount of insulin that is released by the pancreas and makes note that this number can never be a negative number.

![image](https://github.com/powder-o/BergmanMinimalModel_simulation/assets/95707267/b52a72a7-48af-4c28-8957-f62d4f0d2569)

## Code
We use the libraries : Numpy, Scipy and Matplotlib to implement the code. Function odeint from sciply.integrate is used to solve the differential equations.

Note that we have taken values of the parameters p1 to p6 as a considered average. They are not the orignal value of a patient but the average of a poplulation.
