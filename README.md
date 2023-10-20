# Heart Disease Prediction
This project aims to predict the presence of heart disease in patients based on various attributes such as age, sex, chest pain type, blood pressure, cholesterol level, etc. The project uses three different machine learning models. The project also evaluates the performance of each model using metrics such as accuracy, precision, recall, and AUC. The project can be direct run on google colab after uploading the dataset to the notebook in colab(dataset is also provided with the notebook).

# Data
The data for this project is taken from the [Heart Disease Prediction] dataset on Kaggle. The dataset contains 303 records of patients with 13 attributes and one binary outcome variable. The attributes are:

Age: age in years
Sex: sex (1 = male; 0 = female)
CP: chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 4 = asymptomatic)
Trestbps: resting blood pressure (in mm Hg on admission to the hospital)
Chol: serum cholesterol in mg/dl
FBS: fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
Restecg: resting electrocardiographic results (0 = normal; 1 = having ST-T wave abnormality; 2 = showing probable or definite left ventricular hypertrophy by Estes’ criteria)
Thalach: maximum heart rate achieved
Exang: exercise induced angina (1 = yes; 0 = no)
Oldpeak: ST depression induced by exercise relative to rest
Slope: the slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 = downsloping)
CA: number of major vessels (0-3) colored by flourosopy
Thal: thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)
The outcome variable is:

Num: diagnosis of heart disease (angiographic disease status) (0 = absence; 1 = presence)

# Libraries
The project uses the following libraries:

Pandas: for data manipulation and analysis
Numpy: for numerical computation and linear algebra
Matplotlib: for data visualization and plotting
Seaborn: for statistical data visualization and aesthetics
Sklearn: for machine learning models and evaluation metrics
Plot Keras History: for plotting the training history of Keras models

The code works best on python 3.7.0

# Models
The project uses three different machine learning and depp learning models to predict the presence of heart disease in patients:

Decision Tree
Logistic Regression
Support Vector Machine(SVM)
Decision Tree
Random Forest
Feedforward Neural Network (FNN)
Artificial Neural Network (ANN)
Gated Recurrent Unit (GRU)
Long Short-Term Memory (LSTM)
