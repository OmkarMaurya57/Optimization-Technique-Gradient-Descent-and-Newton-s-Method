# Gradient Descent & Newton’s Method Optimization

This project implements and analyzes **Gradient Descent** and **Newton’s Method** for function optimization. Both algorithms were applied on benchmark functions (including the Rosenbrock function) to study convergence behavior under varying tolerance levels and step sizes.

---

##  Overview
- **Gradient Descent**: Iterative method using a fixed step size to minimize the objective function.  
- **Newton’s Method**: Second-order optimization approach leveraging the Hessian matrix for faster convergence.  
- Experiments were run with varying **tolerance values (τ = 10⁻¹ … 10⁻²⁰)** and different initialization points.  
- Comparative analysis of convergence speed, accuracy, and computational trade-offs.  

---

##  Features
- Implemented **Gradient Descent** with:
  - Constant step length
  - Backtracking line search
- Implemented **Newton’s Method** with:
  - Exact Hessian-based updates
  - Fast convergence near minima
- Tabular & graphical comparison of convergence rates across tolerance levels.
- Discussion of shortcomings (e.g., sensitivity to initial conditions, ill-conditioning).

---

##  Key Results
- Gradient Descent converges reliably but may require **more iterations** for smaller tolerances.  
- Newton’s Method achieves **nearly 10× faster convergence** than Gradient Descent for the Rosenbrock function.  
- Trade-off: Higher precision improves accuracy but increases computational cost.  
- Backtracking line search improved step size selection, reducing iterations.  

---





