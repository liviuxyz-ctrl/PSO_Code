
# Particle Swarm Optimization

This repository contains two Jupyter notebooks demonstrating different Particle Swarm Optimization (PSO) experiments, along with a simple requirements file:

1. PSO1.ipynb
2. PSO2.ipynb
3. req.txt

----------------------------
1. PSO1.ipynb
----------------------------
- Purpose:
  Benchmarks the performance of Global Best (Gbest) vs. Local Best (Lbest) PSO on classic functions such as Sphere, Rastrigin, Ackley, and Rosenbrock.
- Key Features:
  - Demonstrates hyperparameter tuning using libraries like Optuna.
  - Shows convergence curves and final cost comparisons for both default and optimized settings.
 ![image](https://github.com/user-attachments/assets/05c7b8fd-e482-44b7-9a0a-d0b3bf6fc93d)

    
- Usage:
  1. Open PSO1.ipynb in Jupyter (or JupyterLab).
  2. Run each cell sequentially. 
  3. Results (plots and numerical summaries) appear inline. You can modify code cells to save figures if desired.

----------------------------
2. PSO2.ipynb
----------------------------
- Purpose:
  Extends the first approach by exploring advanced PSO variants or configurations, again focusing on both Gbest and Lbest topologies.
- Key Features:
  - Visualizes final swarm positions on 2D contours, illustrating how each topology converges.
  - Compares convergence speed, final costs, and swarm distribution.
![image](https://github.com/user-attachments/assets/c49dfe98-1b06-4e05-bd6b-b7e6ae5ea0cf)


- Usage:
  1. Open PSO2.ipynb in Jupyter.
  2. Execute the cells to observe convergence plots and swarm position plots.
  3. Adjust parameters (particle count, iterations, etc.) as needed for additional experiments.

----------------------------
3. req.txt
----------------------------
Lists the Python libraries required to run both notebooks:
  numpy
  matplotlib
  pyswarms
  optuna
  pandas

You can install them with:
  pip install -r req.txt


