🍄 Mushroom Classification
This project focuses on classifying mushrooms as edible or poisonous using machine learning algorithms. The goal is to build a highly accurate model that ensures safe mushroom identification based on physical features.

📚 Dataset
Source: UCI Machine Learning Repository: Mushroom Data Set

Description: Mushroom characteristics were used to predict their edibility.

🔧 Data Preprocessing
Converted the target variable into binary (0 = edible, 1 = poisonous).

Applied one-hot encoding for categorical features.

🤖 Models Used
Logistic Regression (Baseline)

Naive Bayes

Random Forest

Support Vector Classifier

XGBoost Classifier

🏆 Results
Random Forest Classifier achieved the best results:

100% accuracy on training and test sets.

96.85% accuracy with 10-fold cross-validation.

Zero false negatives, ensuring reliable poisonous mushroom detection.

🚀 Conclusion
Random Forest was the most reliable model, offering high accuracy and safety when predicting mushroom edibility.

🔮 Future Improvements
Hyperparameter tuning for even better performance.

Feature engineering and expanded datasets.

🎯 Benefits
Safety: Helps accurately identify poisonous mushrooms.

Automation: Quickly predicts mushroom classes without expert knowledge.

Educational: Demonstrates the power of machine learning in real-world applications.
