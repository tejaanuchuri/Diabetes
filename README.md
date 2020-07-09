# diabetes-using-machine-learning
Implementation : Our implementation is mainly divided into five steps:
1. Exploring the Data:
Exploring the Data using jupyter notebook and verify we need to data preprocessing or not.For this dataset there is no need to data preprocessing. Before split into train and test data check outcome balanced or in balance.whether it is in balanced then we used f1_score.
2. Split into train and test: 
In this we will use `train_test_split` which is available in `sklearn.model selection'. Where we will be dividing the data into train 80% and test splits of 20%.
3. Benchmark model vs other models:
We can choose our benchmark model as LogisticRegression. Because it is simple and easy to implement.We will apply a series of classification algorithms like Logistic
Regression, Decision Trees, Random forests etc.The next step is to find and compare f1_scores of all the models
against the benchmark model.
4. Apply Grid Search Optimization:
Since we can observe that the model with f1_score is Random Forests with an f1_score of 97.65%.We can select Random forest for further optimizing it by applying the
same algorithm on a different set of parameters to find the one with the best f1_score.
5. Display results
Here we will apply many supervised learning algorithms and decide which algorithm is best suited for our dataset. We can apply the grid search on some chosen algorithms to decide the best parameters among many.Finding gridsearchcv optimal f1_score changing parameters to get best optimal f1_score.gridsearchcv (parameters like n_estimator,max_depth..etc)
to get best f1_score for this best classification model using gridsearchcv. I faced some more extra time taken to find best f1_score to change parameters to this diabetes machine learning project.


* External Libraries used:
1. SciKit Learn
2.Numpy
3.Matplotlib
4.Pandas
* Data:
1.Diabetes Dataset available from Kaggle here https://www.kaggle.com/johndasilva/diabetes
2.Also included in directory of repository in original form 
  

