# Machine-Learning-Library-Organisation
The project involves two machine learning algorithms being used to organise books into the appropriate genre based on their summary.

- The following project was to predict the genre of books from summaries. The data is from the CMU Book Summaries Corpus and contains 16559 summaries and includes meta-data about the genre of the books from Freebase. In this project, two models will be created to do the predictive modelling which is logistic regression and naive bayes.
 
 - Firstly, before starting the prediction, the data is cleaned and filtered to only include target genres the model will assess. These genres are children's literature, science fiction, novel, fantasy and mystery.
 
 - Following this, feature extraction is done so that feature vectors can be produced for the predictive models to utilise when performing. When feature vectors are produced, it allows for the information to be suitable for modelling and less redundant.
 
 - After this, the logistic regression model is set up and trained using the train test split method. For the model, the test size is 0.25 and the random state is 1000. The model is then fitted and ready to make predictions. Furthermore, for the naive bayes model the same process was done, with the test size being 0.25 and the random state being 1000. The naive bayes model is also fitted and ready to make predictions.
 
 - The next step is model evaluation, with accuracy, confusion matrix, precision, recall, F1 score and matthew's correlation coefficient being metrics to evaluate each model. Following this, these values are compared against one another with visuals being used to showcase and represent the difference in performance between the two models. Graphs used to represent the two models are barplots, line plots and heatmaps.
