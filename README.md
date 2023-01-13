# Implementation-RandomForest-Classifier

![This is an image](https://miro.medium.com/max/1400/1*rAiSDkkaw0HTyDZ1AQ_mZA.webp)


The Random Forest Classifier simply is a bunch of individual decision trees that work together. Each tree in Random Forest makes a class prediction and the class with the most votes becomes the model’s overall prediction. The reason why random forest works really well is because there is a large number of uncorrelated models (trees) that work as a committee. This committee can outperform any of the individual models.The uncorrelated models are the key to making random forest work so well. The reason for this amazing effect is that the trees protect each other from their individual errors. Some trees might be wrong, but many of the trees will be right, so together the trees can move in the correct direction.In order for the Random Forest Classifier to work well, there needs to be an actual signal in the features so that the models don’t just guess. Also, the predictions made by the individual trees must have a low correlation with each other.

![This is an image](https://www.freecodecamp.org/news/content/images/2020/08/how-random-forest-classifier-work.PNG)

# Why use Random Forest?
Below are some points that explain why we should use the Random Forest algorithm:

* It takes less training time as compared to other algorithms.
* It predicts output with high accuracy, even for the large dataset it runs efficiently.
* It can also maintain accuracy when a large proportion of data is missing

# How does Random Forest algorithm work?
**Random Forest works in two-phase first is to create the random forest by combining N decision tree, and second is to make predictions for each tree created in the first phase.**

**The Working process can be explained in the below steps and diagram:**

* Step-1: Select random K data points from the training set.

* Step-2: Build the decision trees associated with the selected data points (Subsets).

* Step-3: Choose the number N for decision trees that you want to build.

* Step-4: Repeat Step 1 & 2.

* Step-5: For new data points, find the predictions of each decision tree, and assign the new data points to the category that wins the majority votes.

# The working of the algorithm can be better understood by the below example:

>**Example: Suppose there is a dataset that contains multiple fruit images. So, this dataset is given to the Random forest classifier. The dataset is divided into subsets and given to each decision tree. During the training phase, each decision tree produces a prediction result, and when a new data point occurs, then based on the majority of results, the Random Forest classifier predicts the final decision. Consider the below image:**

![This is an image](https://static.javatpoint.com/tutorial/machine-learning/images/random-forest-algorithm2.png)

# Applications of Random Forest
**There are mainly four sectors where Random forest mostly used:**

** Banking: Banking sector mostly uses this algorithm for the identification of loan risk.
** Medicine: With the help of this algorithm, disease trends and risks of the disease can be identified.
** Land Use: We can identify the areas of similar land use by this algorithm.
** Marketing: Marketing trends can be identified using this algorithm.

# Advantages of Random Forest
**Random Forest is capable of performing both Classification and Regression tasks.**
* It is capable of handling large datasets with high dimensionality.
* It enhances the accuracy of the model and prevents the overfitting issue.
# Disadvantages of Random Forest
* Although random forest can be used for both classification and regression tasks, it is not more suitable for Regression tasks.
