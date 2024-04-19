# SC1015-Mini-Project-Movie-Success-Predictor
## Movie Success Predictor:  Unveiling Hits and Flops
### Welcome to movie-success-predictor repository

### About:

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on movies from Netflix TV Shows and Movies in Kaggle Dataset. For detailed walkthrough, please view the source code in order from:

1. [Data Cleaning and Preparation](./DataCleaningAndPreparation.ipynb)
2. Exploratory Data Analysis
3. Data Visualisation
4. Random Forest
5. Logistic Regression

### Contributors

@jovinann - Logistic Regression, Data Cleaning and Preparation,Data Visualisation

@roniathomas - Random Forest, Exploratory Data Analysis, Data Visualisation

@Afzaana512 - Problem Definition


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
1. **Cleaning: Dropping null values**

      Learned how to remove missing data points to enhance the reliability and accuracy of the dataset for subsequent analyses.
2. **Random forest**

   Gained understanding of this model that builds a multitude of decision trees during the training phase and then combines its predictions to obtain more accurate results.

   - Hyperparameter Tuning:
        Acquired skills in optimizing the parameters of machine learning models to maximize their performance on specific datasets.
3. **Logistic Regression**

   Studied this statistical model used for binary classification tasks and how model learns optimal parameters through training, creating a decision boundary to classify new data points.

4. **One Hot Encoding**

   Mastered the technique of converting categorical variables into binary vectors necessary for model processing and improving performance.
   
5. **Concepts of F1 score, precision**

   Learned to evaluate model performance using precision (accuracy of positive predictions) and F1 score (harmonic mean of precision and recall)




### References

https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies

https://www.analyticsvidhya.com/blog/2021/08/conceptual-understanding-of-logistic-regression-for-data-science-beginners/

https://saturncloud.io/blog/how-to-delete-rows-with-null-values-in-a-specific-column-in-pandas-dataframe/#:~:text=Deleting%20rows%20with%20null%20values%20in%20a%20specific%20column%20can,values%20in%20the%20specified%20column.

https://towardsdatascience.com/logistic-regression-and-decision-boundary-eab6e00c1e8

https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9








