# Bayesian Methods for Heart Attack Prediction

This project aims to predict the risk of heart attack in individuals using Bayesian statistical methods. The dataset used in this project is obtained from Kaggle, containing information about the medical history of individuals, such as age, gender, blood pressure, cholesterol levels, and more.

The project uses various statistical techniques, including data cleaning, exploratory data analysis, feature selection, and model building. The results of the project are presented in the form of forest plots and accuracy scores, which show the association between different features and the risk of heart attack.

The code written in `capstone_LKhachatryan_code.ipynb` uses the Python programming language and Python packages such as pymc. 

## Metadata

* **Name:** Lilit Khachatryan 
* **GitHub Username:** lilit07 
* **Project Name:** Bayesian Methods for Heart Attack Prediction


### Running Code

After downloading this repository, open and run the file `capstone_LKhachatryan_code.ipynb`.

### Required Python Packages

To run the file `capstone_LKhachatryan_code.ipynb`, you must have these Python Packages installed:

* `warnings`
* `pymc`
* `pymc_bart`
* `sklearn`
* `numpy`
* `pandas`
* `seaborn`
* `matplotlib`
* `arviz`

## Notes

To install on Windows OS you should first create a separate environment (for example pymc_env) and then proceed with the following commands on Anaconda prompt: 

* `conda create -c conda-forge -n pymc_env "pymc>=4"`
* `conda activate pymc_env`
* `conda install pymc`
* `conda install -c anaconda ipykernel`
* `python -m ipykernel install --user --name=pymc_env`
Within Jupyter (a restart may be required), select the new kernel named 'pymc_env'

All other packages must be installed through the Anaconda prompt to avoid any version incompetences. 

"# capstone" 
