# Toxicity Prediction of Chemicals using ML models.

 Toxicity Prediction is a Machine Learning project that uses data mining and different modelling techniques to make predictions. In this project, datasets containing chemical data are analysed to predict if a chemical is toxic or non-toxic. These predictions are in the form of 1s and 0s, where 1 indicates that the chemical is toxic and 0 indicates the chemical is non-toxic.

## Prerequisties

- This code is implemented in Python3 and it is saved as FINAL.pynb, referring to the python notebook named as FINAL.pynb. To download Python3, please refer to https://www.python.org/downloads/.
- This code is executed on Jupyter Notebook​. Jupyter Notebook​ can be installed at https://jupyter.org/install
- There are a set of libraries that are essential to execute this code successfully. These libraries can be installed via a pip commands as given below:
```sh
pip install numpy 
pip install rdkit 
pip install pandas 
pip install sklearn 
pip install xgboost 
pip install lightgbm 
pip install catboost
```
## Execution Steps
- Clone the given github repository on your local machine while ensuring that all the files are in a single folder.
- The following files need to be in a single folder:
```sh
FINAL.pynb
train_with_descriptors.csv
test_with_descriptors.csv
train_II.csv
test_II.csv
```
- Open the FINAL.ipynb file on Jupyter notebook and after ensuring the code is properly implemented, click "Run All"  which is located on the top menu of that page. Doing this will execute each cell from top to bottom of the code. 
- Each cell that is successfully run will be indicated with a change in the * symbol adjacent to that cell. The * will change to a number on proper execution. If there is any error in a cell, the program will halt at that cell and not proceed further. Therefore, the cells below the "error cell" will not get executed.
- After the successful execution, the output of the program would be a csv file containing chemical ID​s​ and their respective predictions. If a chemical is toxic, it is indicated as 1 in the Prediction column, else as 0. 



| Plugin | README |
| ------ | ------ |
| GitHub | [https://github.com/kevkev123456/ToxicityPrediction/README.md] 

