The end-to-end pipeline for predicting whether a consumer-loan application will be approved or rejected. The notebook cleans the loan-approval classification dataset, creates numeric + one-hot features, trains five binary-classification models (Logistic Regression, Random Forest, Gradient Boosting, SVM, MLP) and chooses the best model according to metrics (f1, roc-auc, etc.)

Besides, it ranks feature influence to show how strongly income, debt-to-income, credit-history, etc. influence a decision

Furthermore, it analyses fairness by checking whether gender, age or marital-status systematically change approval odds, making sure the policy is neutral.
