# module17
repository to answer questions regarding module 17.

### Insights
#### Best Overall Performance (Balanced Metrics):

- **Logistic Regression and Decision Tree/SVM** have **similar test accuracy and F1 scores**.
- **SVM and Decision Tree have the highest AUC**, indicating strong classification performance.

#### Efficiency:

**Decision Tree is the fastest to train**, making it ideal for quick iterations.
**SVM has the longest training time**, which may be impractical for large datasets or frequent retraining.

#### Overfitting Risk:

KNN shows high train accuracy but lower F1 score and AUC, suggesting potential overfitting or poor generalization.

#### Trade-offs:

**Logistic Regression offers a good balance between performance and training time**.
**Decision Tree** is nearly as accurate as Logistic Regression but **faster**.
**SVM** matches Decision Tree in performance but is **computationally expensive**.



### Recommendation
For practical use, where training time matters, **Decision Tree or Logistic Regression are strong choices**.
