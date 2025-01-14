# CP Tutorials 2025


We use the IBM ILOG CPLEX Optimization Studio software. The solver is installed in /usr/local/insa/ibm_cplex_studio_2211 using Python 3.10. We use Jupyter Notebooks with a Python interface, called DOcplex, to communicate with the solver. We recommend using a virtual environment to install DOcplex and Jupyter. To do so, you can follow these steps (similar to the ones used for CPLEX):

### Create a new venv
$cd
$python3.10 -m venv ./venv
$source ./venv/bin/activate

### Install the python interface
$cd /usr/local/insa/ibm_cplex_studio_2211/cplex/python/3.10/x86-64_linux/
$python setup.py install

### Install docplex
$cd
$pip install docplex ipykernel 

### run jupyter to test the installation file test_installation.ipynb


## Personal Installation
If you want to install the solver in your personal machine, you have to do it __before__ the first session. You'll need to install it with an academic license. To do so, create an account using your institution's email at IBM Academic Initiative (https://www.ibm.com/academic/.). Then, download the solver starting from the aforementioned link. 
