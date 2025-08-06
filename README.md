
# Hydrodynamic Simulator for Oil Production Forecasting: Finite Element Method Implementation  
**Programming Language:** Python 3 (FiPy, NumPy, Matplotlib)  
**Core Solution:** [FiPyFracSolver.ipynb](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  
**Organization:** Gazpromneft Technology Partnerships LLC  

### I. Business Challenge  
* Existing approximation-based models required manual parameter tuning due to omitted hydrodynamics fundamentals  
* Commercial simulators (tNavigator) lacked capability to model pressure-dependent permeability - a critical reservoir characteristic  
* This limitation forced arbitrary parameter adjustments, compromising decision-making in multi-stage hydraulic fracturing operations  

### II. Technical Objectives  
Developed a physics-based forecasting solution through:  
* Benchmarking against industry-standard tNavigator simulator  
* Implementation of 2D quasilinear diffusion equation for pressure/flow rate forecasting  
* Python prototype development for production deployment  

### III. Key Achievements  
* Implemented optimized finite element solver with adaptive mesh refinement near fracture zones  
* Achieved <5% deviation from commercial simulator results while incorporating pressure-permeability relationship  
* Delivered production-ready Python prototype forecasting well output with physics-based accuracy  
* Reduced manual tuning requirements by modeling fundamental hydrodynamics  

### IV. Technical Implementation  
**Data & Constraints:**  
* Real well parameters (confidential under NDA)  
* Engineering specifications from reservoir experts  
* Challenge: Nonlinearity artifacts in physical model  

**Methodology:**  
* Solved nonlinear partial differential equations using:  
  - Finite element method (FiPy)  
  - Adaptive meshing for fracture zones  
  - Numerical/analytical hybrid approach  

**Visualization:**  
![Pressure Distribution](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/assets/70639823/d42dd782-9e78-4415-95f4-d34a72a0364a)  
![Production Forecast](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/assets/70639823/3ac03fb1-9b36-4c4f-b988-9ed75c22c23d)  
*Figure 1: Simulated pressure distribution and daily production volume*  

**Solution Code:** [FiPy Fracture Solver](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

This project is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

