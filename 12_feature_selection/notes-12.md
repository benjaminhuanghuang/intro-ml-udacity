
A classic way to overfit an algorithm is by using lots of features and not a lot of training data.

## Add new feature
- use human intuition
- code up the new feature
- visualize
- repeat


## Getting rid of feature
- Noisy
- Causes overfitting
- It is strongly related (highly correlated) with a feature that's already present
- Additional features slow down training/testing process

## Feature selection tools in sklearn
- SelectPercentile selects the X% of features that are most powerful (where X is a parameter)
- SelectKBest selects the K features that are most powerful (where K is a parameter).

## Bias vs Variance
    High bias: over simplied, few features uese
    High variance: many features, overfits, minimize SSE (sum of squared error)

## Refernce 
    https://jefflirion.github.io/udacity/Intro_to_Machine_Learning/Lesson11.html