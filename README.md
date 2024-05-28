# Auto MPG Prediction

## Description:

This repository contains code for predicting automobile fuel efficiency (MPG) using various machine learning methods. Leveraging the UCI ML Repository dataset (source included below), this project employs techniques including Linear Regression, Ridge Regularization, and Random Forest. Additionally, missing values in the 'horsepower' feature are filled using a formula incorporating Power Factor per Cubic Inch (PFCI). Visualizations are provided to illustrate the analysis and model performance.

## Installation and Dependencies:

- _sklearn_ - https://scikit-learn.org/
- _UCIMLRepo_ - https://archive.ics.uci.edu/
- _pandas_ - https://pandas.pydata.org/
- _numpy_ - https://numpy.org/
- _Matplotlib_ - https://matplotlib.org/
- _Jupyter Notebook_ - https://jupyter.org/

## Conclusion:

In conclusion, this project involved creating and training various machine learning methods. The Random Forest model, tuned with optimal parameters, proved to be the most accurate, exhibiting the lowest mean error and standard deviation. Initially, the primary task was to compare the initial approximate value of PFCI (3.84) with the new value (~3.11) calculated based on existing data. Subsequently, methods of learning with error outputs and attempts to incorporate new data were introduced incrementally. In Linear Regression and Ridge Regularization, the differences between training and test data were minimal. However, when predicting MPG for new data, the results were disparate from model standards but aligned closely with real-world observations. Conversely, the Random Forest model exhibited familiarity with new data but was likely applicable only in urban settings. In essence, Linear Regression and Ridge Regularization were better suited for predicting MPG away from urban areas, while Random Forest was tailored for urban cycle MPG, aligning with the project's objectives.

**The data was collected up until the year 2000, representing older vehicle types and technologies.**
