# B3_Group4_UCE2023562_UCE2023567_UCE2023570
Sleep Health &amp; Lifestyle Predictor Project



Sleep Quality Predictor


Personalized Sleep Quality Predictor

Objective

The goal of this project is to predict an individual's quality of sleep based on their lifestyle and health parameters such as age, gender, BMI, physical activity, stress levels, heart rate, daily steps, blood pressure, and sleep disorders.
It also provides personalized suggestions to improve sleep quality.

Dataset Details

Dataset used: Sleep_health_and_lifestyle_dataset.csv

Columns include:

Gender

Age

BMI Category

Sleep Disorder

Sleep Duration

Physical Activity Level

Stress Level

Heart Rate

Daily Steps

Blood Pressure

Target: Quality of Sleep

Preprocessing:

Categorical data (Gender, BMI, Sleep Disorder) encoded as numeric values

Blood Pressure split into Systolic and Diastolic

Missing numeric values filled with column mean

Algorithm / Model Used

Decision Tree Classifier (primary model)

Random Forest Classifier (comparison)

Both models from scikit-learn

Features used for prediction:

Gender, Age, Sleep Duration, Physical Activity Level, Stress Level, BMI Category, Heart Rate, Daily Steps, Sleep Disorder, Systolic BP, Diastolic BP

Accuracy Results

Decision Tree

Accuracy: (from train_and_save.py output, e.g., 0.85)

Detailed classification report and confusion matrix printed

Random Forest

Accuracy: (from train_and_save.py output, e.g., 0.88)

Detailed classification report and confusion matrix printed

Note: Replace the values above with actual accuracy after running train_and_save.py.

Conclusion

The Decision Tree model provides a simple and interpretable prediction of sleep quality.

Random Forest shows higher accuracy due to ensemble learning but is more complex.

Users can enter their personal data and get predicted sleep quality, along with actionable suggestions to improve sleep hygiene.

All records are saved locally for tracking sleep trends over time.

Future Scope

Integrate with wearable devices to automatically fetch health metrics.

Add more advanced ML models like XGBoost or Neural Networks for higher prediction accuracy.

Provide long-term sleep trend analysis and personalized recommendations.

Add visualization dashboards for better user insights.

References

Md. Atiqur Rahman, Israt Jahan, et al., “Improving Sleep Disorder Diagnosis Through Optimized Machine Learning Approaches,” IEEE Access, 2025.
D. R. Sahu and R. K. Gupta, "Machine Learning Techniques for Sleep Disorder Classification and Sleep Quality 

Assessment," 2024 Asian Conference on Intelligent Technologies (ACOIT), KOLAR, India, 
