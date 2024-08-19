Predicting Power Consumption in Tetouan City, Morocco

Overview

This project focuses on predicting power consumption in Tetouan City, Morocco, through machine learning models. The work is divided into two main parts:

Reproducing Original Results: The first part replicates the findings from a study on predicting power consumption in Tetouan City using similar features, models, and parameters. This helps validate the original results.

Developing a New Solution: The second part presents an alternative solution that aims to improve or match the original study's performance using new feature selection methods, model optimizations, and innovative machine learning algorithms.

Project Structure

Part 1: Reproducing Original Results

Followed the methods detailed in the original study to replicate the results. sosurce: https://ieeexplore.ieee.org/document/8703007

Used various models, including Linear Regression, Decision Tree, Random Forest, Support Vector Regression (SVR), and Feedforward Neural Network (FFNN).
Results were compared against the original study to assess accuracy and consistency.

Part 2: Developing a New Solution

Designed an ensemble model approach to improve predictive accuracy.
Implemented techniques such as stacking predictions from multiple models (Gradient Boosting Regressor, Random Forest, FFNN) and using Ridge Regression as the final model.
Demonstrated the ensemble model’s performance, particularly in Zones 2 and 3, where it significantly outperformed the original study's models.

Dataset

Data: The dataset includes hourly power consumption data for three different zones in Tetouan City, along with environmental variables such as temperature, humidity, and wind speed.
Preprocessing: The dataset was cleaned, and features were engineered, including datetime extraction to create new time-related features.
Models Used

Part 1: Reproducing Original Results
Linear Regression
Decision Tree
Random Forest
Support Vector Regression (SVR)
Feedforward Neural Network (FFNN)


Part 2: Developing a New Solution
Ensemble Model:
Gradient Boosting Regressor
Random Forest Regressor
Feedforward Neural Network (FFNN)
Final Model: Ridge Regression


Key Results

Reproduced Results: Results from the first part closely matched the original study, validating the accuracy of the reproduction process.
Ensemble Model Performance: The ensemble model outperformed individual models, particularly in Zones 2 and 3, with significant reductions in RMSE and MAE compared to the original study.
Conclusion

The ensemble model developed in Part 2 offers a robust and balanced solution for predicting power consumption across different zones in Tetouan City. It demonstrates the potential for improving accuracy by combining the strengths of multiple models.

Personal Learnings

The importance of model selection and the power of ensemble methods in improving predictive accuracy.
Understanding that more complex models do not always yield better results, and model simplicity can sometimes offer greater interpretability and efficiency.

References

Breiman, L. (2001). Random Forests. Machine Learning, 45(1), 5-32. doi:10.1023/A:1010933404324
Friedman, J., Hastie, T., & Tibshirani, R. (2001). The Elements of Statistical Learning: Data Mining, Inference, and Prediction. Springer.
Geron, A. (2019). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. 2nd Edition. O'Reilly Media
