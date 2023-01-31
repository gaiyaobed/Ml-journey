# student_predict
A Machine learning model to Predict students' dropout and academic success, 

I built the model using LogisticsRegression,  DecisionTreeClassifier ,RandomForestClassifier, at the end RandomForestClassifier and Support Vector Machine (SVM) 
AT the end  RandomForestClassifier model appears to have an accuracy of 76.27%. The precision for class 0 is 0.85, meaning that 85% of the time when the model predicts class 0, it is correct. The recall for class 0 is 0.77, meaning that the model correctly identifies 77% of the total positive cases for class 0. The f1-score is a balance between precision and recall, and is calculated as 0.81 for class 0. The results for the other classes can be similarly analyzed. It's important to consider the confusion matrix, the classification report, and the accuracy together to get a comprehensive understanding of the model's performance.

```

Accuracy: 0.768361581920904
Confusion Matrix:
 [[237  23  56]
 [ 32  49  70]
 [  9  15 394]]
Classification Report:
               precision    recall  f1-score   support

           0       0.85      0.75      0.80       316
           1       0.56      0.32      0.41       151
           2       0.76      0.94      0.84       418

    accuracy                           0.77       885
   macro avg       0.72      0.67      0.68       885
    macro avg       0.72      0.67      0.68       885
weighted avg       0.76      0.77      0.75       885

```
