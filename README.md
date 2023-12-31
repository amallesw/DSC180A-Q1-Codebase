# DSC180A-Q1-Codebase

## Dataset Access
To get the FER2013 dataset, go to [this drive](https://www.kaggle.com/datasets/msambare/fer2013/) and download the "archive" file. Place this file in the data folder from this GitHub.

The code for preprocessing will not be needed as that creates the `Dartmouth_predictions.csv` file which we already have in the data folder. 




Running the cells within the `FER2013_DeepFace.ipynb` will provide you with the results our model attained from the FER2013 dataset. You will
see the graphs, tables, and confusion matrix.

Running the cells within the `Dartmouth_DeepFace.ipynb` will provide you with the results our model attained from the Dartmouth Children's dataset. You will see the graphs, tables, and confusion matrix.


## Installing Dependencies
Install the required libraries using the following pip commands:

```
pip install pandas numpy deepface seaborn matplotlib scikit-learn
```

These commands will install Pandas, NumPy, DeepFace, Seaborn, Matplotlib, and scikit-learn, which are the needed dependencies for this project.
