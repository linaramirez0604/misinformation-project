# misinformation-project
READ ME

LAST UPDATE README: August 18, 2022

PROJECT: Attacking Misinformation from the Demand Side: A Field Experiment on Critical Thinking. 


Data, literature, output, presentations: “dip” Dropbox folder 

Code: “misinformation-project” repository in GitHub

Draft: Max needs to ask Julia for permission 


You need a virtual environment with all the packages installed to be able to run the Jupyter Notebook. Open the terminal and create the virtual environment as follows: 

conda create -n myenv python=3.9 
conda activate myenv
conda install numpy matplotlib scipy pandas statsmodels seaborn jupyterlab
conda install -c conda-forge scikit-learn 

The previous step has to be done only once. 

Every time you want to open your jupyter notebook  you need to run in the terminal: 

conda activate myenv
cd /Users/bfiuser/Documents/GitHub/misinformation-project
jupyter-lab

*Replace cd to where you have the jupyter notebooks. 

Once in the notebooks don’t forget to change the cd to where you have the data (dropbox folder). The latest code is draft1.ipynb. 

Things to be done: 

1. Analyze the data of the diagnostic and see if there is something useful there in terms of critical thinking /data/diagnostic.xlsx 
2. Analyze rounds 2 and rounds 3 (see how many observation merge, and if the results hold). 

