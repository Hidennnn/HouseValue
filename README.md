# houseValue

## Technology
|    **Name**    | **Version** |
|:--------------:|:-----------:|
|    `Python`    |   3.10.12   |
| `scikit-learn` |    1.2.2    |
|    `pandas`    |    1.5.3    |
|    `numpy`     |   1.25.0    |
|  `matplotlib`  |    3.7.1    |
|   `seaborn`    |   0.12.2    |
|    `scipy`     |   1.9.13    |

## Description
Thanks to the project I learn about made regression
models and about filling NaN values.

## Database
In the project I worked with the California Housing Prices database.
Project's goal was prediction of mean value of 
houses in area.

**Link to database:**
https://www.kaggle.com/datasets/camnugent/california-housing-prices

## Results

RandomForestClassifier achieved the best results.

**Params**:

|      **Name**       | **Value** |
|:-------------------:|:---------:|
|    `n_estimator`    |    250    |
|     `criterion`     |  poisson  |
|     `max_depth`     |    600    |
| `min_samples_leaf`  |     2     |
| `min_samples_split` |    15     |
|  `max_leaf_nodes`   |    550    |

**MSE:** 0.0156

## Summary
Target values were scaled between 0 and 1. That's
mean the error value is ~1.5% which is quite good result.
I think the biggest problem is small number of feature

