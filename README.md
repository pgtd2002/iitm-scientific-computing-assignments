# IIT Madras — Python & Scientific Computing Assignments

A collection of Jupyter notebooks documenting programming and computational methods explored through coursework at the **Indian Institute of Technology Madras (IIT Madras)**. The assignments cover introductory Python, floating-point accuracy, numerical methods, scientific visualization, linear algebra, differential equations, stochastic simulation, and Fourier-based signal analysis.

> **Academic context:** These notebooks document course-based assignment work. They are a personal learning portfolio, not official course solutions or independent research projects. Please follow the relevant course policies and sharing rules when viewing, reusing, or distributing coursework solutions.



| No. | Course / problem set | Topics covered | Notebook |
|---:|---|---|---|
| 01 | PH5720 · Problem Set 1 · Jan–May 2025 | Python functions, radians-to-degrees conversion, decimal-to-binary conversion, arithmetic operations, simple interest, string manipulation, factorial, recursive Fibonacci | [01 — Python Fundamentals](notebooks/01-python-fundamentals.ipynb) |
| 02 | PH5720 · Problem Set 2 · Jan–May 2025 | Floating-point limits, numerical cancellation and stability, recurrence error, order-dependent summation, electric-field plots, wave superposition, pendulum energy contours | [02 — Floating-Point Arithmetic and Visualization](notebooks/02-floating-point-and-visualization.ipynb) |
| 03 | PH5720 · Problem Set 3 · Jan–May 2025 | Series approximations for sine and exponential functions, truncation and relative error, recursive evaluation, logistic map, bifurcation and chaotic behavior | [03 — Series Methods and Nonlinear Dynamics](notebooks/03-series-methods-and-nonlinear-dynamics.ipynb) |
| 04 | PH5720 · Problem Set 4 · Jul–Nov 2024 | Two-point linear interpolation, file-based data input, Lagrange interpolation, polynomial interpolation, cubic splines, comparison of interpolation methods | [04 — Interpolation Methods](notebooks/04-interpolation-methods.ipynb) |
| 05 | PH5720 · Problem Set 5 · Jan–May 2025 | Forward, backward and central finite differences, derivative error versus step size, second derivatives, numerical energy estimation for a particle in a box | [05 — Numerical Differentiation](notebooks/05-numerical-differentiation.ipynb) |
| 06 | PH5720 · Problem Set 6 · Jan–May 2025 | Least-squares fitting, curve fitting, polynomial fitting, trapezoidal and Simpson’s rules, Gaussian quadrature, two-dimensional integration, adaptive integration and error convergence | [06 — Data Fitting and Numerical Integration](notebooks/06-data-fitting-and-integration.ipynb) |
| 07 | PH5720 · Problem Set 7 · Jan–May 2025 | Bisection, Newton–Raphson and secant methods, convergence and initial guesses, reciprocal iteration, root finding for a deuteron bound-state equation | [07 — Root-Finding Methods](notebooks/07-root-finding-methods.ipynb) |
| 08 | PH5720 · Problem Set 8 · Jan–May 2025 | Euler, second-order Runge–Kutta and fourth-order Runge–Kutta methods, projectile trajectories, coupled ODEs, oscillator phase space, energy conservation and a double-well potential | [08 — ODE Solvers and Phase-Space Analysis](notebooks/08-ode-solvers-and-phase-space.ipynb) |
| 09 | PH5720 · Problem Set 9 · Jan–Nov 2024 | Diagonal dominance, Gauss–Seidel iteration, Gaussian elimination and LU decomposition for linear systems | [09 — Linear-System Solvers](notebooks/09-linear-system-solvers.ipynb) |
| 10 | PH5720 · Problem Set 10 · Jan–May 2025 | One-dimensional random walks, displacement statistics, Monte Carlo estimation of π and integrals, statistical uncertainty, radioactive-decay simulation | [10 — Random Walks and Monte Carlo Methods](notebooks/10-random-walks-and-monte-carlo.ipynb) |
| 11 | PH5720 · Problem Set 11 · Jan–May 2025 | Sampling and DFT frequency spacing, an 8-point FFT, FFT-based high-pass filtering, and single- and double-slit diffraction patterns | [11 — FFT, Signal Processing and Diffraction](notebooks/11-fft-signal-processing-and-diffraction.ipynb) |

## Main Learning Areas

- **Python programming:** functions, recursion, number conversion, strings and basic algorithm implementation.
- **Numerical accuracy:** floating-point representation, cancellation, finite-precision effects, convergence and error analysis.
- **Numerical methods:** interpolation, finite differences, numerical integration, root finding and ordinary differential equations.
- **Linear algebra:** diagonal dominance, iterative methods, Gaussian elimination and LU decomposition.
- **Scientific visualization:** plotting functions, data, numerical errors, trajectories, phase space and bifurcation diagrams.
- **Stochastic computation:** random walks, Monte Carlo integration, sampling variability and radioactive-decay simulation.
- **Fourier methods:** DFT/FFT, frequency resolution, frequency-domain filtering and diffraction calculations.

## Repository Structure

```text
IITM-Scientific-Computing-Assignments/
├── README.md
└── notebooks/
    ├── 01-python-fundamentals.ipynb
    ├── 02-floating-point-and-visualization.ipynb
    ├── 03-series-methods-and-nonlinear-dynamics.ipynb
    ├── 04-interpolation-methods.ipynb
    ├── 05-numerical-differentiation.ipynb
    ├── 06-data-fitting-and-integration.ipynb
    ├── 07-root-finding-methods.ipynb
    ├── 08-ode-solvers-and-phase-space.ipynb
    ├── 09-linear-system-solvers.ipynb
    ├── 10-random-walks-and-monte-carlo.ipynb
    └── 11-fft-signal-processing-and-diffraction.ipynb
```

## Tools

- Python
- Jupyter Notebook (`.ipynb`)
- Scientific computing and plotting libraries as used in the individual notebooks

Each notebook should describe its problem context, approach, implementation, and representative output. Where relevant, include brief explanations of numerical behavior and limitations rather than code alone.

## Reproducibility and Use

- Run notebooks from top to bottom to verify that code and outputs are consistent.
- Avoid machine-specific file paths; include any required data files and explain how to use them.
- Identify external sources or libraries where applicable.
- Do not present coursework exercises as independent projects, and make sure public sharing is consistent with course rules.
