Fantasy Football Team Predictions
Introduction
This project aims to forecast successful fantasy football teams using regression with regularization. The predictive models are based on player statistics and leverage both linear and Lasso regression techniques. The goal is to optimize player selection and enhance performance prediction in Fantasy Premier League (FPL).

Project Structure
Notebook: Final_project_Uluka_Prince.ipynb
GitHub Repo: Fantasy-Football-Team-Predictions
Description
Problem Statement
Selecting the optimal fantasy football team in a simulated environment like Fantasy Premier League is challenging. The project addresses this by employing a hybrid ARIMA-RNN model and linear programming to maximize player points.

Methodology
The project follows a hybrid approach, combining time series modeling techniques (ARIMA and RNN) and linear programming for team selection. The linear regression models and Lasso regression models are implemented and compared to predict player performances.

Results
Both linear regression and Lasso regression models are applied to the player dataset.
Mean error scores are used to evaluate the models' performance.
Both models demonstrate similar behavior and mean error rates, indicating successful prediction on the dataset.
Contributions
In addition to linear regression, Lasso regression is implemented to reduce prediction errors. The models are compared based on mean error scores.

Implementation Steps
Import Libraries:

Libraries like pandas, numpy, altair, pulp, and sklearn are imported for data manipulation, visualization, and model implementation.
Predictions:

Linear regression models are trained for each position (goalkeeper, defender, midfielder, forward) based on player statistics.
Predictions are calculated, and mean error scores are computed for each position.
Select Team Functions:

Linear optimization is used to calculate the best legal team for each gameweek.
Teams are selected based on budget constraints, position requirements, and other constraints.
Generate Predictions:

Predictions are generated for a specific gameweek (GW).
The selection range is extended to evaluate performance over multiple gameweeks.
Contribution Code - Lasso Regression:

Lasso regression models are initialized and fit to the training data for each position.
Predictions are made, and prediction errors are calculated using Lasso regression.
Mean error scores for each position are printed and compared with linear regression.
Results and Conclusions
The project successfully implements linear regression and Lasso regression models to predict fantasy football player performances. Both models exhibit similar behavior and mean error rates, indicating their effectiveness on the given dataset.

Learnings
Use of GitHub repository for project duplication.
Importance of model generalization and avoiding overfitting.
Significance of features in performance prediction.
Assessment of model accuracy using metrics like mean error.
Limitations
Balancing testing and training data is crucial to prevent overfitting.
Shrinking coefficients towards zero in Lasso regression may impact less significant features.
Future Work
Apply models to larger datasets for improved accuracy.
Explore advanced algorithms for predictions.
References
Interactive Tools for Fantasy Football Analytics and Predictions using Machine Learning - Neena Parikh 2014
Time Series Modelling for Dream Team in Fantasy Premier League - Akhil Gupta 2017
Han J, Kamber M, Pei J. Data Preprocessing. Data Mining Concepts and Techniques 2011.
Shivani, K. S. Sandhu and A. Ramachandran Nair, "A Comparative Study of ARIMA and RNN for Short Term Wind Speed Forecasting," 2019 10th International Conference on Computing, Communication and Networking Technologies (ICCCNT), Kanpur, India, 2019.
Acknowledgments
The project was developed by Uluka Prince.
GitHub repository: Fantasy-Football-Team-Predictions
