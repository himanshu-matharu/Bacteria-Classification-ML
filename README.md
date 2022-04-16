# Bacteria Species Classification using Machine Learning Algorithms

As Machine learning has taken the world by a storm, how can the field of Microbiology be left behind? The advent of Machine learning became a boon in this field, as antibiotics were failing in front of ever-evolving bacteria. The processes which used to take days and even months, resulting in skyrocketing mortality rates due to delays, can now be solved within hours using the prediction, classification, and feature selection approach. This report analyzes the accuracy of different Machine learning algorithms to process data from a novel spectroscopic diagnostic device and in identifying the bacterial species by drawing a comparison to the available DNA sequences.

We select different supervised machine learning models and test their performance by training for the classification problem at hand. We also tune the hyperparameters of the models to increase performance. This study will be able to discern if machine learning models are accurate enough to be used for bacteria classification tasks and thus, ultimately be used for preliminary analysis and fast decision making in the medical field.

## Implementation

The notebook contains the code for training Machine Learning Algorithms for classification of bacteria species on the basis of the ATCG BOC in 10-mer DNA samples.

[Bacteria Classification Main.ipynb](https://github.com/himanshu-matharu/Bacteria-Classification-ML/blob/main/Bacteria%20Classification%20Main.ipynb)
### Dataset used: [data.csv](https://drive.google.com/file/d/1SICwgX0UOLSM3BKGpWb1Sf1JqMj54STW/view?usp=sharing)

## Machine Learning Algorithms Used

- Logistic Regression
- Random Forest Classifier
- XGBoosting Classifier
- Extra Trees Classifier
- Neural Network

## Requirements

- Python 3.5
- [tensorflow](https://www.tensorflow.org/install/pip)
- [scikit-learn](https://scikit-learn.org/stable/install.html)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [plotly](https://plotly.com/python/getting-started/#installation)
- [xgboost](https://xgboost.readthedocs.io/en/latest/install.html)
