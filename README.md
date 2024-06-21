# Heart Failure Prediction Model

This repository contains a complete workflow for training a heart failure prediction model using a dataset from Kaggle. The dataset contains various features related to heart disease, and the model is built using TensorFlow and Keras.

## Dataset

The dataset is taken from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) and contains the following attributes:

- **Age**: Age of the patient [years]
- **Sex**: Sex of the patient [M: Male, F: Female]
- **ChestPainType**: Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- **RestingBP**: Resting blood pressure [mm Hg]
- **Cholesterol**: Serum cholesterol [mg/dl]
- **FastingBS**: Fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- **RestingECG**: Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality, LVH: showing probable or definite left ventricular hypertrophy]
- **MaxHR**: Maximum heart rate achieved [Numeric value between 60 and 202]
- **ExerciseAngina**: Exercise-induced angina [Y: Yes, N: No]
- **Oldpeak**: Numeric value measured in depression
- **ST_Slope**: The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- **HeartDisease**: Output class [1: heart disease, 0: Normal]

## Technology used

- **Tensorflow Keras**: For creating, training Deep Neural Network.
- **Scikit**: For Data Pre-processing.
- **Pandas**: For handling Dataset which is in .csv format.


## Conclusion

The model has been developed using Deep Neural Networks to predict Heart Failure.
The Model achieved:
- **Loss**: 0.3425
- **Accuracy**: ~87%
