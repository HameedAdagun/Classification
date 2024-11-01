# Classification

The goal of this project is to to develop machine learning (ML) models for a classification task. I trained two ML models for classification and explored the impact of different hyperparameter values on the accuracy achieved by my models. I
also prepared a short .pdf report discussing my findings.

A dataset called wildfires has been split into separate training and test sets: wildfire_training.csv and wildfire_test.csv which can be seen in the repository. The data is supplied in comma separated values format. Each row describes one instance in the dataset. The attributes are in columns in the following order: fire, year, temp, humidity, rainfall, drought_code, buildup_index, day, month, wind_speed. The goal of my classification models is to predict the value of the target attribute fire (which may be one of two classes: yes or no) based on the values of other attributes.

I selected decision tree and support vector machine as my classification algorithms from the scikit-learn package, and then apply them to this dataset to train predictive models. 

A list of available scikit-learn classifier implementations can be found at:
https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html

The models that I developed was trained on the supplied training set only. I reported accuracy results for each model on both the training set and the test set independently. I presented results foreach model using the default hyperparameter settings in scikit-learn, and results achieved when attempting to tune two of the available hyperparameters for each model. For each model, I choose any two
available hyperparameters to tune. I did not use any automated hyperparameter tuning methods (e.g., the scikit-learn GridSearchCV class) for this project.
