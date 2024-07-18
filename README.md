# Heart-Attack-Prediction
This repository contains a machine learning project to predict heart attack risks using health indicators. It includes data cleaning, feature engineering, and model training with Python libraries like Pandas, Scikit-Learn, and Matplotlib. The goal is to develop an effective predictive model for heart attack risk assessment.

# Column details
1. **age**: This refers to the age of the patient, typically measured in years. Age is an important factor in heart health, as certain heart conditions and risks are more common at different stages of life.

2. **sex**: This indicates the biological sex of the patient, typically encoded as binary values (0 or 1) where 0 represents female and 1 represents male. Sex is a significant factor in heart disease, as certain conditions may be more prevalent or present differently in different sexes.

3. **cp**: This stands for "chest pain type." It represents the type of chest pain the patient is experiencing and is categorized into four levels:
   - 0: Typical angina (chest pain related to reduced blood flow to the heart muscle)
   - 1: Atypical angina
   - 2: Non-anginal pain
   - 3: Asymptomatic

4. **trestbps**: This is the resting blood pressure of the patient, measured in mmHg (millimeters of mercury). Blood pressure is an essential indicator of heart health, as high blood pressure (hypertension) can strain the heart and blood vessels.

5. **chol**: This represents the serum cholesterol level of the patient, measured in mg/dL (milligrams per deciliter). Cholesterol is a type of fat in the blood, and high cholesterol levels can contribute to the formation of plaque in the arteries, increasing the risk of heart disease.

6. **fbs**: Fasting blood sugar level, measured in mg/dL. This indicates the patient's blood glucose level after fasting for a specific duration. Elevated fasting blood sugar may be associated with diabetes, which is a risk factor for heart disease.

7. **restecg**: This stands for "resting electrocardiographic results." It represents the results of an electrocardiogram (ECG or EKG) performed while the patient is at rest. It may be encoded into several levels, indicating different ECG patterns.

8. **thalach**: This refers to the maximum heart rate achieved by the patient during an exercise test, measured in beats per minute (bpm). The maximum heart rate is an important parameter during exercise stress testing and can provide insights into the patient's cardiovascular fitness.

9. **exang**: This is short for "exercise-induced angina" and is binary (0 or 1) data. It indicates whether the patient experiences chest pain (angina) during exercise (1) or not (0).

10. **oldpeak**: This represents the ST depression induced by exercise relative to rest. It is a measurement on an ECG and helps assess the severity of exercise-related changes in the heart's electrical activity.

11. **slope**: This refers to the slope of the peak exercise ST segment, also measured on an ECG. It provides information about the ST segment's trajectory during exercise and can be categorized into three levels.

12. **ca**: This stands for the number of major vessels colored by fluoroscopy. It represents the number of blood vessels in the heart that were visualized during a diagnostic test.

13. **target**: This is the target attribute or the label, which indicates the presence (1) or absence (0) of heart disease in the patient. It is the variable that the model aims to predict based on the other attributes in the dataset.
