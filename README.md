# SC1015-Mini-Project-Movie-Success-Predictor
## Movie Success Predictor:  Unveiling Hits and Flops
### Welcome to movie-success-predictor repository

### About:

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on movies from Netflix TV Shows and Movies in Kaggle Dataset. For detailed walkthrough, please view the source code in order from:

1. Data Cleaning and Preparation
2. Exploratory Data Analysis
3. Data Visualisation
4. Random Forest
5. Logistic Regression

### Contributors

@jovinann- Logistic Regression, Data Cleaning and Preparation,Data Visualisation

@roniathomas - Random Forest,Exploratory Data Analysis, Data Visualisation

### Problem Definition

To build a predictive model that can determine a movie’s potential success using a range of movie characteristics.

### Models Used

1. Random Forest

2. Logistic Regression

### Conclusion

1. **Low Correlation Between Numerical Predictors and Scores**:
   - The correlations between the numerical predictors (gross, runtime, budget, votes) and movie scores were relatively low, with votes having the highest correlation at 0.47. This suggests that these factors alone do not strongly predict movie success, indicating the complexity of factors influencing movie scores.

2. **Random Forest and Overfitting Issues**:
   - The Random Forest model showed signs of overfitting, as indicated by a high R^2 score on the training set compared to the testing set. Even after hyperparameter tuning and outlier removal, the model’s generalization to unseen data did not improve significantly. This suggests that the model is not suited to accurately forecast movie success, underlining the need for alternative modeling approaches that can better represent these relationships.
     
3. **Effectiveness of Logistic Regression**:
   - Logistic Regression showed good performance in classifying movies as successful or not, based on if the score was above 7.2. It demonstrated high accuracy, precision, and consistent F1 scores across both training and testing sets, 

5. **Predictive Model Choice and Application**:
   - Between the two models tested, Logistic Regression was more effective and consistent, suggesting it as a more suitable choice for this particular predictive task. This model's ability to generalize suggests it might be more reliable for practical implementation in predicting movie success.

6. **Future Recommendations**:
   - Considering additional features that might capture more complexity, such as textual data from reviews or social media sentiment analysis, could potentially enhance model performance.
   - Testing other classification algorithms that can handle non-linear relationships and complex interactions (like Gradient Boosting) might also yield better results.


### What did we learn from this project?
- Cleaning: Dropping null values
  
- Random forest:
   1. Hyperparameter Tuning
      
- Logistic Regression
  
- One Hot Encoding
  
- Concepts of F1 score, precision




### References

