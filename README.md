# titanic

This project is used as the **week 3** exercise in a Machine Learning course.

Project *titanic* demonstrates using Decision Trees to predict whether a person survived the titanic disaster or not.

## Exercise

First run the notebook as given to see if it loads the data correctly, after that continue with the exercise below. For this exercise you may need to refer to the scikit-learn documentation on Decision Tree Classifier.

### Model complexity

Because the example model is trained with the feature 'Cherbourg', every time we want to make an inference, we have to specify whether the person is from Cherbourg or not. Given that this feature has very little impact on the outcome, it is possible to reduce de model's complexity by removing this feature from training, as well as from inference. Make a new model without the feature 'Cherbourg'. Does the accuracy dwindle much? Why yes/no?

### Iris

Remember the Iris dataset from week 1? Add a section to the notebook in which you apply a Decision Tree to this data set in order to have it classify iris plants. You probably do not need to do any scaling because Decision Trees are not sensitive to non-normalized data. Also, there is no need to do extensive evaluation but do draw the tree. What is your opinion about the drawn tree?

### Hyperparameters

A decision tree has quite a number of hyperparameters that you can set and it will result in a different (shorter or larger) tree, called pruning. Set the parameters `max_depth`, `min_samples_split` and `min_samples_leaf` to something different than their default. What changed? What do you believe is the ultimate goal of this? Write down in your notebook, using a text cell. Compare your answer with a fellow student. Write down their name and what they believed in your notebook as well.