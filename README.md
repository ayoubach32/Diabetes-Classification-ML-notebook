
1. Start by preparing the data using a technique called SMOTE to handle any
imbalances.
2. Train four different machine learning models: Random Forest, SVM, KNN,
and Logistic Regression.
3. Test each model’s accuracy. Keep only models that score better than 80%.
4. The Logistic Regression model performs poorly, so exclude it from further
consideration.
5. Combine the remaining high-performing models (Random Forest, SVM, and
KNN) into an ensemble learning system.
6. When making predictions, all models in the ensemble "vote" on the outcome.
7. Instead of a simple majority vote, use soft voting where each model provides
a probability score.
8. Average these probability scores to create the final prediction.

  
<img width="366" alt="diag02" src="https://github.com/user-attachments/assets/41a21848-76c8-4546-8f93-2cbe667961e5" />
   - Workflow Diagram of the Proposed Diabetes Classification System - 
