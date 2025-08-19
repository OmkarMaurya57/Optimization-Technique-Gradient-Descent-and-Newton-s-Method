
# Gradient Descent and Newton’s Method Implementation

## Overview
This project focuses on implementing and analyzing two fundamental optimization algorithms—**Gradient Descent** and **Newton’s Method**—with an emphasis on improving convergence through advanced step-size selection techniques. The study includes experiments with varying precision levels, performance comparisons, and visualization of results to highlight trade-offs between accuracy and computational efficiency.

## Key Contributions
- **Developed optimization code** implementing both **Gradient Descent** and **Newton’s Method**.  
- **Integrated exact line search algorithm** to achieve high precision in step size selection.  
- **Enhanced convergence efficiency** by introducing **backtracking line search**, reducing the number of iterations.  
- **Compared performance** of Newton’s Method vs. Gradient Descent, demonstrating **~10x faster convergence** for Newton’s Method.  

## Technical Highlights
- **Gradient Descent:**
  - Implemented with both constant and adaptive step sizes.  
  - Conducted experiments varying tolerance `τ` from `10⁻¹` to `10⁻¹³` to study convergence behavior.  
  - Analyzed trade-offs between precision and computational cost.  

- **Newton’s Method:**
  - Leveraged second-order derivative information (Hessian matrix) for improved convergence rate.  
  - Verified convexity via Hessian eigenvalues to ensure global minimum.  
  - Demonstrated rapid convergence even at tighter precision (`τ` down to `10⁻²⁰`).  

- **Line Search Techniques:**
  - **Exact line search** for theoretical precision.  
  - **Backtracking line search** for practical performance improvement and stability.  

## Results
- **Gradient Descent:** Effective but sensitive to step size; required more iterations for stricter tolerance.  
- **Newton’s Method:** Achieved significantly faster convergence (~10x improvement) with robust step length control.  
- **Visualization:** Generated plots showing the effect of tolerance on iteration count and convergence rate.  

## Observations
- Smaller tolerance → higher accuracy but increased iterations.  
- Backtracking line search improved step length adaptation and prevented divergence.  
- Newton’s method consistently outperformed gradient descent for the test functions.







