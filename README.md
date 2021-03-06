# PCA-for-Visualization-and-Classification
Using Principal Component Analysis and Logistic Regression for predicting parkinson's disease.

You can find **dataset** [here](https://archive.ics.uci.edu/ml/datasets/Parkinsons)

# Objective
My objective is to use PCA and Logistic Regression to predict if person has parkinson's disease.

# What is Principal Component Analysis?
Principle Component Analysis(PCA) is a common dimensionality reduction technique used for visualization and for speeding up machine learning models. If you want to learn more about PCA click [here](https://www.youtube.com/watch?v=FgakZw6K1QQ).

# Features
Dataset consists of 26 features, but with correlation matrix's help I figured out which features affect results the most and chose main 4(spread1, PPE, MDVP:Flo(Hz), MDVP:Fo(Hz)).

# Results

## Visualization
![PCA Plot](https://github.com/handertolium/PCA-for-Visualization-and-Classification/blob/master/PCA_plot.png)

## Prediction
Model got accuracy of 82% which is high considering we used only 4 features and did PCA on them. PCA can lower the accuracy because when lowering dimension space you lose some of the variance(information).


**Paper citations**: 'Exploiting Nonlinear Recurrence and Fractal Scaling Properties for Voice Disorder Detection', Little MA, McSharry PE, Roberts SJ, Costello DAE, Moroz IM. BioMedical Engineering OnLine 2007, 6:23 (26 June 2007).







