# Machine Learning Homework - Exoplanet Exploration - Models Summary


### Random Forest - Best Model
Test Score Before GridSearch 0.8890160183066361

Test Score After GridSearch  0.8949099105654967

#### Final Classification Report - After Parameter Tuning using GridSearch

                    precision    recall  f1-score   support

     CANDIDATE           0.82      0.76      0.79      422
     CONFIRMED           0.81      0.83      0.82      450
     FALSE POSITIVE      0.97      1.00      0.98      876

     accuracy                                0.89      1748
     macro avg           0.87      0.86      0.86      1748
     weighted avg        0.89      0.89      0.89      1748

- - -

### Decision Tree
Test Score Before GridSearch 0.8501144164759725

Test Score After GridSearch  0.8857523341022713

#### Final Classification Report - After Parameter Tuning using GridSearch

                    precision    recall  f1-score   support

     CANDIDATE           0.84      0.69      0.76       422
     CONFIRMED           0.75      0.85      0.80       450
     FALSE POSITIVE      0.98      1.00      0.99       876

     accuracy                                0.89      1748
     macro avg           0.86      0.85      0.85      1748
     weighted avg        0.89      0.89      0.88      1748

- - -

### SVM
Test Score Before GridSearch 0.8415331807780321

Test Score After GridSearch  0.8847997729571603

#### Final Classification Report - After Parameter Tuning using GridSearch

                     precision    recall  f1-score   support

     CANDIDATE            0.84      0.69      0.76       422
     CONFIRMED            0.75      0.85      0.80       450
     FALSE POSITIVE       0.98      1.00      0.99       876

     accuracy                                 0.89      1748
     macro avg            0.86      0.85      0.85      1748
     weighted avg         0.89      0.89      0.88      1748
