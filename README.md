tumor
======
A Python package for agent-based Monte Carlo simulations of tumor growth written by [Peter McHale](http://ccbs-76.bio.uci.edu/~petermchale/). The accompanying [Jupyter Notebook](http://ccbs-76.bio.uci.edu/~petermchale/jupyter_notebooks/demonstration.html) illustrates how to 
* simulate the model in Python 3.x
* statistically analyze data generated by the model
* visualize the results of the analysis to maximize insight
<img src="data/tumor.gif">

In the movie above, there are two types of cells - green cells that replicate ('cycle' in biological terms) and red cells that do not (called 'quiescent' by biologists). To run a similar movie on your own computer, download this repository, open `Terminal` (on a Mac), and execute the following commands at the command line:
```
cd <path to repository>/data/animation/
python ../../tumor_package/animate.py
````
