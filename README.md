# FEM-POD-Steady_NS
This repository contains a reduced order model using the Proper Orthogonal Decomposition (POD). As an example we chose the standard 2D cavity flow (steady Navier-Stokes equation). The mathematical framework behind the Finite Element Method and the POD method, as well as, some numerical results are stated in the .pdf file. You don't need any data to run the code, since they are generated from the function "nvst" found in the .ipynb file. The main idea of this project was derived from [here](https://www.um.es/freefem/ff++/pmwiki.php?n=Main.POD).
## Installation
The code was implemented using Python 3.10.12 on Ubuntu 22.04. The required dependencies for this project are:
* [NumPy](https://numpy.org/)
* [SciPy](https://scipy.org/)
* [Netgen/NGSolve](https://ngsolve.org/)
* [Jupyter Notebook](https://jupyter.org/)
## References
- [Gruber, A., Gunzburger, M., Ju, L., & Wang, Z. (2022). A comparison of neural network architectures for data-driven reduced-order modeling. Computer Methods in Applied Mechanics and Engineering, 393, 114764.](https://arxiv.org/pdf/2110.03442.pdf)
