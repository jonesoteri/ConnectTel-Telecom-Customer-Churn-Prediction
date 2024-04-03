# ConnectTel-Telecom-Customer-Churn-Prediction

## Table of Contents 
- [Project Objective](#project-objective).
- [Problem Definition](#problem-definition).
- [How will the company benefit](#company-benefit).
- [Exploratory Data Analysis](#EDA).
- [Feature Engineering](#feature-engineering).
- [Model Selection,Training and Validation ](#machine-learning-model).
- [Model Evaluation](#model-evaluationl).
- [Conclusion](#conclusion)

- ## Project Objective
- Leveraging Machine Learning to Reduce Customer Attrition

- ## Problem Definition
- The Challenge of Customer Churn:
   * Customer churn is the loss of customers to competitors.
   * It leads to revenue loss, hinders growth, and threatens sustainability.
   * Existing retention strategies lack precision and effectiveness.
 
-  ## How will the company benefit
- By accurately forecasting customer churn, ConnectTel can:
   *  Reduce Customer Attrition: Implement targeted retention initiatives to prevent churn.
   *  Enhance Customer Loyalty: Retain valuable customers and improve overall  satisfaction.
   *  Maintain a Competitive Edge: Stay ahead in the highly dynamic and competitive telecommunications industry.
 
-  ## Exploratory Data Analysis

-  **Visualizing Relationships**:
     * I Explore how key features (e.g tenure, contract, senior citizen ) relate to the churn label.
     * I Identify patterns or trends that impact customer behavior.

-  **Explore Correlations**:
     * I investigate correlations between features and churn.
     * I uncover potential predictors of churn.
 
-  **Univariate, Bivariate, and Multivariate Analysis**:
     * I analyze individual features (univariate).
     * I examine interactions between features (bivariate).
     * I consider feature combinations (multivariate).

-   ## Feature Engineering
    * Encoding Categorical Variables:
       * I convert categorical features (e.g gender,InternetService,PaymentMethod) into numerical representations.
       * I use techniques like label encoding.

    *  I create new Features by extracting meaningful information from existing features.

-   ## Model Selection,Training and Validation
    * I experiment with at least 3 supervised learning algorithms

   - **Logistic Regression**
   - **Random Forest Classifier**
   - **K-Nearest Neighbours Classifier**
   - **Confusion Matrix**

-   ## Model Evaluation
    * Analyzing the result for Logistic Regression:

      **Accuracy**:
    * The model predicts correctly the outcome for approximately 81.69% of customers compare to Random Forest Classifier and KNeighborsClassifier.

      **Precision**:
    * A precision of 67.8% suggests that the model predicts a positive outcome

      **Recall**:
    * A recall of 58.71% indicates that the model identifies approximately 58.71% of the actual positive customers.

      **F1-score**:
    *  A value of 62.93% suggests a reasonable balance between precision and recall.

      **AUC-ROC**:
    * An AUC-ROC of 74.34% indicates that the model performs reasonably well
 

-    ## Confusion Matrix
     **True Positives (TP)**:
      * There are 219 true positives (correctly predicted positive cases).

     **True Negatives (TN)**:
      * There are 932 true negatives (correctly predicted negative cases).

     **False Positives (FP)**:
      * There are 104 false positives.

     **False Negatives (FN)**:
      * There are 154 false negatives.


-  ## Conclusion
     I think the business should be more focus on minimizing the false Negative compared to the true positive.

    **Reasons**:
    * Missing a customer who is likely to churn (false negative) can result in revenue loss. ConnectTel would need to detect potential churners early to prevent them from leaving.
    * It can result to customer dissatisfaction.
    * It can also result to brand reputation impact.


     






  
