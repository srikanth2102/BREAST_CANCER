# BREAST CANCER DIAGNOSIS

## MOTIVATION:
* In India one in every 28 women has a possiblity of getting Breast Cancer. 
* If left un diagnoised it could be fatal.
* So efficient diagnositc methods are required.
* In this project we will try to make diagnois using Machine Learning.

## TASK:
* So in this project we try to predict whether a lump is benign or Malignant.

## DATASET:
* The dataset can be downloaded [here](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)

## FEATURES:
|FEATURES                              |DESCRIPTION                                  |
|               ---                    |               ---                           |
|* MEAN_RADIUS                         |  Radius of the lump formed                  |  
|* MEAN_TEXTURE                        |  The texture of the lump formed             |
|* MEAN_PERIMETER                      |  perimeter of the lump                      |
|* MEAN_AREA                           |  Total area occupied by the lump            |
|* MEAN_SMOOTHNESS                     |  Smoothness of the lump                     |

## LABEL:
* Given the above features we have to diagnois whether the lump is cancerous or not.
* Benign(0) or Malignant(1).

## MODELS USED:
* Logistic Regression
* Decision Tree
* Support Vector Machine
* Random Forest
* Boosting(using decision tree)
* MLP Classfier

## MODEL SELECTION:
 
* The model with the best F1_score was Boosting using decision tree.
* However the chosen model is Logistic Regression.
* The reason is that the F1_score of Logistic regression is that it is way faster than that of the Boosting.
* As well as the F1_score of the Logistic Regression is nearly equal to that of the Boosting.
