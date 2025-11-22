
# Hydrodynamic Simulator for Oil Production Forecasting: Finite Element Method Implementation  
**Solution Code:** [FiPyFracSolver.ipynb](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  
**NDA:** well parameters (changed)  
**Coding Language:** Python 3 (FiPy, NumPy, Matplotlib)  
**Organization:** Gazpromneft Technology Partnerships LLC  

### I. Business Challenge  
* Existing approximation-based models required manual parameter tuning due to omitted hydrodynamics fundamentals  
* Commercial simulators (tNavigator) lacked capability to model pressure-dependent permeability - a critical reservoir characteristic  

### II. Technical Objectives  
Developed a physics-based forecasting solution through:  
* Implementation of 2D quasilinear diffusion equation for pressure/flow rate forecasting  
* Python 3 prototype development for production deployment with open-source libs  

### III. Key Achievements  
* Implemented optimized finite element solver with adaptive mesh refinement near fracture zones  
* Achieved <5% deviation from commercial simulator results while incorporating pressure-permeability relationship   
* Reduced manual tuning requirements by modeling fundamental hydrodynamics  

### IV. Technical Implementation  
* Real well parameters (confidential under NDA)  
* Engineering specifications from reservoir experts  
* Challenge: Nonlinearity artifacts in physical model    
* Solved nonlinear partial differential equations using:  
  - Finite element method (FiPy)  
  - Adaptive meshing for fracture zones  
  - Numerical/analytical hybrid approach  

**Visualization:**  
<img width="676" height="173" alt="image" src="https://github.com/user-attachments/assets/cc610f17-2762-4d79-b259-1024ae5ff39c" />
<img width="271" height="196" alt="image" src="https://github.com/user-attachments/assets/cbed9676-f217-45ac-9d92-15ebc83c424c" />
*Figure 1: Simulated pressure distribution and daily production volume*  

**Solution Code:** [FiPy Fracture Solver](https://github.com/ResearchMachine/commercial-project-hydrodynamic-in-predictive-complex/blob/main/FipyFracSolver.ipynb)  

## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

This project is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

