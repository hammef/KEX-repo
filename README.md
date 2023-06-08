# KEX-repo
### A Comparative Study on the Effects of Removing the Most Important Feature on Random Forest and Support Vector Machine
#### Authors: Hampus Fridlund and Henrik Åkesson

## Project Overview
Machine learning (ML) for classification is largely regarded as a “black box”, in that it’s difficult to fully understand how the model reached a decision, and how changes to the input affects the output. Therefore, exploring the inner workings of classification models are of interest for expanding the current knowledge base, providing guidelines for choosing a more suitable classification model for a specific problem. In this study we have focused on the effects on the classification performance of two classifiers, Support Vector Machine (SVM) and Random Forest (RF), when removing the feature from two datasets ranked as most important using two different feature importance methods: SHAP for SVM and Gini Impurity for RF. The two models were first trained on the full featured datasets, then on the datasets with the most important feature removed. The results of removing the most important feature from the dataset led to reduced accuracy for both models, but with a greater reduction for the SVM, while RF remained more stable. This may indicate that SVM is more dependent on the most important feature than RF. What was similar in our results as well as in a previous study, was that RF does not vary as much in accuracy as SVM when selecting a subset of features.

### Data Source

The dataset “Rain in Australia” was [downloaded from Kaggle](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) owned by Joe Young. The source of data is originally from the Australian Bureau of Meteorology's [Daily Weather Observations](http://www.bom.gov.au/climate/dwo/). Additional weather data is available at [Bureau of Meteorology](http://www.bom.gov.au/climate/data/). 


The dataset “Adult income dataset” was [downloaded from Kaggle](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset) owned by user “wenruliu”. The source of data is originally from [UCI machine learning repository](http://archive.ics.uci.edu/ml/datasets/adult ) where the dataset is called “adult” and the data extraction was done by Ronny Kohavi and Barry Becker from the 1994 Census database. 
