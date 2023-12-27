# Wine Quality Prediction Project

## Problem Statement

***Wine is the most healthful and most hygienic of beverages***
– Louis Pasteur

All over the world wine is so popular among people, and only 5% of the population doesn’t know what is wine? Sounds good.

It definitely comes across the fruit graphs, which is so sweet on the test but graphs are not just to eat, they are used to make different types of things. Wine is one of them Wine is an alcoholic drink that is made up of fermented grapes. It would be noticed that wine has also their type they are red and white wine this was because of different varieties of graphs.

The worldwide distribution of wine is 31 million tonnes which were huge in number.

What if thinking about the quality of wine, how can people differentiate the wine according to their quality? The big question arises.

According to experts, the wine is differentiated according to its smell, flavor, and color, but not everyone is a wine expert to say that wine is good or bad. What will people do then? Here’s the use of Machine Learning comes, yes using machine learning to check and predict wine quality. ML have some techniques that will be discussed below.


## Approach 

The problem was divided into several steps:

1. **Data Collection:** Data was collected from the UC Irvine Machine Learning Repository [website](https://archive.ics.uci.edu/dataset/186/wine%252Bquality).

#### Data description

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult on [the website](http://www.vinhoverde.pt/en/) or the reference [Cortez et al., 2009].  Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks.  The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, it is not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

The following files were used in the project:

```
winequality-red.csv
winequality-white.csv
```

2. **EDA:** Extensive data visualisation and summary statistics were used to extract insights and pattern from the various datasets. The facts and trivia behind wine features were narrated through data.

3. **Machine Learning:** Logistic Regression, KNN Classifier, SVC, Decision Tree Classifier, Random Forest Classifier, GaussianNB, Gradient Boosting Classifier and Xgboost Classifier were trained on the feature engineered dataset to predict wine quality respectively. Their feature importances were noted to gain insights into what factors influence the quality of wine.


## Final Results 

Random Forest Classifier will be used because it was the only ML model that gives the 88.4% accuracy which was considered as the best accuracy.


## Repository Structure

1. **wine_prediction.ipynb:** The Jupyter notebook containing code for the recommendation engines.

2. **image_result:** The folder containing all EDA images.

3. **wine_quality.sav:** Machine Learning model saved file

