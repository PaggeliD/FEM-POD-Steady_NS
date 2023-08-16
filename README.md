# FEM-POD-Steady_NS
This repository contains a reduced order model using the Proper Orthogonal Decomposition (POD). As an example we chose the standard 2D cavity flow (steady Navier-Stokes equation). The problem states as follows: Find $(\mathbf{u},p)$ such that:
\begin{align}
   \mathbf{u}\cdot\nabla\mathbf{u} - \nu\Delta\mathbf{u} 
      + \nabla p &= 0  \\
   \nabla\cdot u &= 0
\end{align}
