## Classification of physical performance

The goal of this project is to train several classification models and select the best one to predict the level of physical performance of the participants based on few exercises, their body measurments and personal demographics to further enhance their fitness journey and avoid injuries. We started approaching the goal with EDA of the dataset from kaggle.com to fully understand the features and the distribution of the dataframe.

![Screen Shot 2021-12-15 at 8 39 46 PM](https://user-images.githubusercontent.com/32347958/146240853-317944ac-a9a7-41ba-aeea-bfaa8a984823.png)

The figure simply shows a full classification report of the decision tree model, which has an accuracy of 0.574 and aiming to improve it more if possible.
In addition, we tried training logistic regression (performed poorly because of the multiple traget classes), KNN, XGBoost. We are still working on tunning the hyper parameters for each model to choose the best baseline model at the end.
