# Schrodinger PCA

### The hierarchy of files and their uses:

* gaussian/laplace
  * fig: eigenvalues and eigenmodes, as plots
  * results: eigenvalues and eigenmodes, as *.npy files
  * rf.ipynb: produce PCA results (both fine grid and coarse grid)
  * sch_num.ipynb: Schrodinger PCA on the fine grid
  * sch_num-coarse.ipynb: Schrodinger PCA on the coarse grid
  * sch-analytical.ipynb: Schrodinger PCA based on harmonic approximation
  * plot.ipynb: responsible to produce figures in ./fig
* climate
  * se.ipynb: Solve Schrodinger PCA on the sphere





### Dependency (python package)

* numpy
* matplotlib
* scipy
* sklearn