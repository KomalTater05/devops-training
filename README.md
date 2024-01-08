# Median housing value prediction

The housing data can be downloaded from https://raw.githubusercontent.com/ageron/handson-ml/master/. The script has codes to download the data. We have modelled the median house value on given housing data. 

The following techniques have been used: 

 - Linear regression
 - Decision Tree
 - Random Forest

## Steps performed
 - We prepare and clean the data. We check and impute for missing values.
 - Features are generated and the variables are checked for correlation.
 - Multiple sampling techinuqies are evaluated. The data set is split into train and test.
 - All the above said modelling techniques are tried and evaluated. The final metric used to evaluate is mean squared error.

## To excute the script
 ### Conda environment creation
    - conda create --name devops-dev python=3.9
    - conda activate devops-dev
    - conda insatll panda numpy matplotlib scikit-learn


 ### Running the python code
    - python nonstandardcode.py


 ### Exported conda environment to create te env.yml
    - conda env export --name devops-dev > env.yml


 ### Create the conda environment
    - conda env create -f env.yml

