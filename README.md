# Test several regression algorithms on Washington bike sharing demand data

This R notebook shows a way to tackle a regression task in R. The data under consideration is the bike sharing demand challenge hosted by kaggle in 2015 (https://www.kaggle.com/c/bike-sharing-demand/). The train and test data is also available at the given URL.

A special focus of this notebook lies on feature engineering and ensemble learning, i.e. finding an optimal linear combination of different models. You will find sections on the following topics:

* **Feature engineering** guided by some ggplots
* Comparison of very different **regression** models
* Hyperparameter tuning especially for **xgboost and SVMs**
* **Ensemble learning**: Finding a good linear combination of 5 models using nonlinear optimization

## Findings

* Hyperparameter tuning improves accuracy significantly.
* As a single model xgboost outperforms (once again) the other models in terms of accuracy and computational time.
* For moderate size of data nonlinear kernel SVMs are still quite competitive.
* The linear combination of models outperforms all single models. The best solution scores at rank 99 (from > 3000 public scores).

For an improved view please use the following nbviewer URL:


