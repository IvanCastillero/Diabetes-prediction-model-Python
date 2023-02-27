# Diabetes-prediction-model-Python
This project aimed to predict the likelihood of a person having diabetes based on several clinical variables. The dataset used in this project contained information on 768 patients and their diabetes status.

The project began by exploring the dataset, which involved checking for missing values, outliers, and distribution of variables. Data preprocessing techniques were employed, such as scaling and encoding categorical variables, before building the models.

This is the correlation table:
![Alt Text](https://github.com/IvanCastillero/Diabetes-prediction-model-Python/blob/main/correlacion.png)

Two models were trained on the data - logistic regression and random forest classifier. The logistic regression model achieved an accuracy of 0.79 on the training set and 0.74 on the test set. Meanwhile, the random forest classifier model achieved an accuracy of 0.85 on the training set and 0.72 on the test set. The random forest classifier model was then further optimized using grid search cross-validation.

Training set confusion matrix:
![Alt Text](https://github.com/IvanCastillero/Diabetes-prediction-model-Python/blob/main/confussion%20matrix%20training.png)

Test set confusion matrix:
![Alt Text](https://github.com/IvanCastillero/Diabetes-prediction-model-Python/blob/main/confusion%20matrix%20test.png)

In conclusion, this project showed that it is possible to predict the likelihood of a person having diabetes based on clinical variables with reasonable accuracy. The random forest classifier model outperformed the logistic regression model and achieved an accuracy of 0.77 on the test set. The project also highlighted the importance of data preprocessing, model selection, and model optimization in achieving better predictive performance.
