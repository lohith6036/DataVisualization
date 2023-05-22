# DataVisualization


This is a review accuracy prediction model that gives us the accuracy of the predicted ratings for the reviews. 

Here we are taking a website goodread reviews which provide reviews for books. 

I am taking a dataset from kagel and split the dataset into 80% train and 20% test data. 

Now I am fetching some analysis results of the data like 
  - Dates on which we had most reviews
  - Which day of the week had most of the reviews
  - Which month had most number of reviews
  - number of ratings with each score (0 to 5)

I also cleaned the data before training the model to find out accuracy.
  - remove stop words
  - remove few common words that might affect the accuracy


Now trained few models and tried to find the accuracy.

In conclusion, Based on the results of the models trained on the dataset, 
the logistic regression model performed the best with an accuracy of 0.485. 
The random forest model also performed relatively well with an accuracy of 0.476. 
However, the other models, including the decision tree, support vector machine, and naive Bayes models, 
performed poorly with accuracies ranging from 0.376 to 0.453. 
It is important to note that the performance of the models may be improved by adjusting the hyperparameters 
or by using more advanced techniques such as neural networks. Overall, the project highlights the importance 
of using natural language processing and machine learning techniques to analyze and classify reviews.
