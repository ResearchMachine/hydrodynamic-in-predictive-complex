# (2022) Forecast of Oil Production of Special Group of Wells. Hydrodynamic Simulator Development, Finite Element Method.
**Programming Language:** Python 3 (fipy, matplotlib, numpy)  
**Project Сode:**  [FipyFracSolver.ipynb](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  
**Project Full Description** (in Russian):  [Description.pdf](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/Description.pdf)  
**Company:**  Gazpromneft Technology Partnerships LLC. 


### I. Motivation
Earlier in the project [(2021) Complex Predictive Model Transfer](https://github.com/ResearchMachine/commercial-project-parcing-of-predictive-complex) the complex model was transferred from Excel format to VBA format. This model does not take into account hydrodynamics, which leads to the need for manual fitting of the model.
Existing software does not allow taking into account a key reservoir property (permeability depends on pressure) when calculating production volume, which leads to the need to adapt models by varying reservoir parameters and hydraulic fracture properties arbitrarily - this leads to the risk of making incorrect decisions in terms of multi-stage hydraulic fracturing technology.

### II. Problem
The main goal of this project is the introduction of a hydrodynamic model into the forecast complex.
Tasks:
* selection of the optimal model solver for performance;  
* comparison of model results with the commercial simulator tNavigator;  
* forecast of pressure and flow rates;  
* implementation of the prototype in Python.  

### III. Key Results 
* Selected the optimal solver for the model in terms of computation speed (finite element method with mesh thickening in the crack area, the model is a non-linear diffusion equation in partial derivatives);  
* Adapted the solver to the conditions of the problem, developed a Python 3 prototype and made a forecast of the production volume of one well.  
* 5% - maximum deviation from the commercial simulator tNavigator.  


### IV. Content
Real parameters of wells changed (NDA).  
Input data: description of the model from company engineers.  
Problems: artifacts of model nonlinearity.  
Methods: nonlinear differential equations, numerical and analytical methods, Python 3, Jupyter Notebook.  

![image](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/assets/70639823/d42dd782-9e78-4415-95f4-d34a72a0364a)
![image](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/assets/70639823/3ac03fb1-9b36-4c4f-b988-9ed75c22c23d)  
**The results of the prototype: the distribution of pressure around the well and the volume of oil production per day.**

**Project Сode:**  [FipyFracSolver.ipynb](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  
**Project Full Description** (in Russian):  [Description.pdf](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/Description.pdf)  

