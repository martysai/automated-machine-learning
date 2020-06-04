# Automated Machine Learning
[![AutoML](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/MaratSaidov/automl)

This project contains an overview of main existing methods of automated machine learning:

*    Automated feature engineering based on featuretools;
*    H2O AutoML;
*    AutoKeras;
*    SMAC;

Based on [dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce), the task was to predict a price of an item in e-commerce. The results are provided here:

| **Model Name** | **R Squared** |
| --- | --- |
| [CatBoost Baseline](baselines/automl_gradient_based_approach.ipynb) | 0.749 |
| [CatBoost with AutoFE](automl/https://github.com/MaratSaidov/automl/blob/master/automl/automl_feature_engineering.ipynb) | 0.838 |
| [H2O AutoML](https://github.com/MaratSaidov/automl/blob/master/automl/h2o_automl_handy_feature_enginering.ipynb) | 0.897 |
| H2O AutoML with AutoFE | 0.892 |
| SMAC | 0.802 |
| [AutoKeras on Struct. Data](https://github.com/MaratSaidov/automl/blob/master/automl/automl_autokeras.ipynb) | 0.659 |

# Related Projects

Here's a list of other related projects where you can find inspiration for doing AutoML research:

*    [H2O.ai](https://github.com/h2oai)
*    [AutoKeras](https://github.com/keras-team/autokeras)
*    [featuretools](https://github.com/FeatureLabs/featuretools)
*    [SMAC3](https://github.com/automl/SMAC3)
