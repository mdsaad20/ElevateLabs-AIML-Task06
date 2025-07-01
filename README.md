# K-Nearest Neighbors (KNN) Classification with Iris Dataset

This project demonstrates the implementation of a K-Nearest Neighbors (KNN) classifier on the famous Iris dataset using Python and scikit-learn.

## Project Overview

The goal is to classify iris flowers into three species (setosa, versicolor, virginica) based on four features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib

Install requirements with:
```
pip install pandas numpy scikit-learn matplotlib
```

## Implementation Steps
1. Data Loading & Preprocessing:

    - Load the Iris dataset
    
    - Split into features (X) and target (y)
    
    - Normalize features using StandardScaler
    
    - Split into training and test sets (80-20)

2. KNN Classification:
    - Initialize KNeighborsClassifier
    
    - Train the model

    - Make predictions on test set

3. Evaluation:

    - Calculate accuracy score

    - Generate confusion matrix

    - Test different k values (1-20)

    - Plot accuracy vs k value

4. Visualization:

    - 2D decision boundary plot (using sepal length and petal length)

## Results
The classifier achieves approximately 96-100% accuracy with optimal k values (typically 3-10). The confusion matrix shows how well each species is classified.

## Visualizations
#### The script generates two plots:

- Accuracy vs K value - helps select optimal k

- 2D decision boundaries - shows classification regions