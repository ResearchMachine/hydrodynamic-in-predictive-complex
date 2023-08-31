# (2022) Forecast of Oil Production of Special Group of Wells. Hydrodynamic Simulator Development, Finite Element Method.
**Project Type:** Commercial project  
**Programming Language:** Python 3 (fipy, matplotlib, numpy)  
**Project Сode:**  [FipyFracSolver.ipynb](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  
**Project Full Description** (in Russian): 
**Company:** 


Hydrodynamic Simulator Development. Forecast of Oil Production of special Group of Wells, Finite Element Method.
individual commercial project. Company: Gazpromneft Technology Partnerships LLC (RUS). Programming Language: Python 3 (fipy, matplotlib, numpy).

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
The model solver (finite element method, fipy library) was selected, which made it possible to repeat the result of the commercial simulator tNavigator (maximum deviation 5%).


### IV. Content



Input data: description of the model from company experts, operator of a commercial simulator.

Problems: artifacts of model nonlinearity.

Methods: nonlinear differential equations, numerical and analytical methods, Python 3, Jupyter Notebook.



