# Model Predictive Control

Repo for Model Predictive Control(MPC) implementations using different optimizers. Contains the following:

* fmincon(MATLAB) code for holonomic MPC
* CVXOPT(Python) code for holonomic MPC
* CVXOPT(Python) code for non-holonomic MPC
* Demo QP solver using CVXOPT
* Cubic spline and Bernstein polynomial fitting in Python for holonomic trajectories.


## Repository Structure

```
.
├── polynomial_fitting
    ├── polyfit_spline_bernstein.ipynb      (Notebook containing Holonomic cubic spline and Bernstein polyfitting in Python)
├── fmincon_holonomic 
    ├── run.m                               (Main MATLAB code for holonomic MPC using fmincon)
├── CVXOPT_holonomic                        
    ├── main.ipynb                          (Notebook for holonomic MPC using CVXOPT in Python)
├── CVXOPT_nonhn                        
    ├── main.ipynb                          (Notebook for non-holonomic MPC using CVXOPT in Python)
    ├── CVX_demo.ipynb                      (Demo QP solver using CVXOPT)

```