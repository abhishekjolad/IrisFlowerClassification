# IrisFlowerClassification

## Frame the Problem and Look at the Big Picture

This project aims to learn and find different ML models that can be used to classify flowers into 3 distinct species: virginica, setosa, or Versicolor. The problem is a supervised learning task as there is data from Kagle. As this is a multi-class classification task, performance will be measured based on how accurate the model is when classifying the flowers. We are aiming for an accuracy of at least 85%. 

## Get the Data

The dataset used is from Kaggle.
  Link: https://www.kaggle.com/datasets/arshid/iris-flower-dataset

The dataset is a collection of flower samples that contain statistics on the petal length/width and sepal length/width. The measurements are in centimeters and each sample belongs to one of three species:  Iris-setosa, Iris-versicolor, or Iris-virginica. The dataset has 150 samples, 50 of each species, thus making it well-balanced and a great dataset.

## ML Algorithms

I used 3 different machine learning algorithms using Sci-kit Learn’s library. These models include: Decision Tree, Random Forest Classification, and K Nearest Neighbors Classification.

The Iris dataset has features that can easily split the data into classes, making Decision Trees a good choice, as they can handle both numerical and categorical data.
	
Random Forests are a more robust model that generalizes better to unseen data. Random Forests also handle overfitting well, which can be a problem with Decision Trees.

The KNN doesn’t make any assumptions about the underlying data which is good for the Iris dataset as it doesn’t necessarily follow any known distribution.

## Evaluation Metrics
I used two different evaluation metrics: accuracy score and F1 score.
  
The accuracy score was the base evaluation metric but since it isn’t good to only rely on the accuracy metric, I also used the F1 score metric which is useful in scenarios where false positives and false negatives have similar costs
  
## Final Results
All the models scored extremely well on the test case as they got an accuracy score of 100% and an F1 score of 1.
