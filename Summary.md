### CHAPTER 1
+ Deep learning is a kind of Machine Learning, and Machine Learning is a kind of Artificial Intelligence.
+ The process used to make the model performance regardless of the training data or the input data is called generalization. The successof Machine Learning relies heavily on how well the generalization is accomplished.
+ One of the primary causes of the curruption of the generalization process is overfitting.
+ If you believe that every element of the training data is correct and fits the model precisely, you will get a model with lower generalizability. This is called overfitting.
+ Reguralization is a numerical method that attempts to construct a model structure as simple as possible. The simplified model can aavoid the effect of overfitting at the small cost of performance.
+ As the data has high delimension, wen can not draw the model and intuitivel evaluate the effects  of overfitting for such data. Therefore, we need another method to determine whether the trained model is overfitted or not. This is where **validation** comes into pplay.
+ The **validation** is a process that reservers a part of the trainning data and uses it to monitor the performance. The validation set is not uesd for the training process. Because the modeling error of the training data fails to indicate overfitting, we use some of the training data to check if it is overfitted.
+ Cross-validation is a slight variation of the validation process. The difference is that it keeps changing the datasets.The reason for doing this is that the model can be overfitted even to the validation set when it is fixed. As the cross-validation matains the randomness of the validation dataset, it can better detect the overfitting of the model.
+ One of the representative applications of the unsupervised learning is clustering.
