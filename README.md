# Penguin-Prediciton
A data science project for penguin prediction
This project contains Data analysis and then the comparison of various models fitted to the [penguin database](https://www.kaggle.com/code/parulpandey/penguin-dataset-the-new-iris). 
### AIM
To build a model to predict penguin species based on its physical features. 
### Flow of project
We dive into data science essentials, of cleaning the data( by finding and removing irrelevant fields to predict species, finding outliers, imputing missing values using KNN ).
We then visualize various fields (physical features) with respect to each other, showcasing very high variance w.r.t each other.
Then we split the data into 4:1 ratio to train and test various models.
Moving forward, as this was a classification problem, I trained the data on four different models popular for classification problems, namely KNN classifier, Logistic regression, Naive Bayes( Gaussian), and Random forest classifier.
As you'll see in the project, KNN classification gave the best results.
### Final words
Such a project made on large scale (with larger datasets )can help scientists with predicting the species of penguins, whose species classification seems to be highly dependent on the sizes of their various body parts(can be seen in the project).
This could have been an interactive project, where the user inputs known physical features and our program imputes whatever data is missing, and predicts the species. I didn't take that path because I the main theme of the project was data science, so I stuck to that. I learned a lot while making this project and would love to make more such projects in future.
