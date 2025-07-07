# AI-Based-Diabetes-Risk-Prediction-System
This project predicts the likelihood of diabetes using a Machine Learning model trained on the PIMA Indian Diabetes dataset. It helps in early identification of potential diabetes risk using basic health indicators.

##  Dataset
- **Source**: [Kaggle - PIMA Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**: Glucose, BMI, Age, Pregnancies, Insulin, Blood Pressure, etc.
- **Target**: Outcome (0 = No Diabetes, 1 = Diabetes)

##  Tools & Technologies
- **Language**: Python 3.x
- **Libraries**: 
  - `pandas` for data handling  
  - `matplotlib` & `seaborn` for visualization  
  - `scikit-learn` for machine learning  
- **IDE**: Jupyter Notebook / Google Colab

##  ML Pipeline
1. Load and clean data
2. Feature scaling using `StandardScaler`
3. Split data into training and testing sets
4. Train model using **Logistic Regression**
5. Evaluate using accuracy, confusion matrix, and classification report

##  Results
- **Model Accuracy**: ~78%
- **Evaluation**: Confusion matrix showed good classification of both diabetic and non-diabetic cases.
- ![Confusion Matrix](confusion_matrix.png) *(Add your actual image here)*

##  Deployment
- Deployment to Azure ML Studio was skipped due to subscription limitations.
- Model currently runs locally in Python.

##  Future Scope
- Deploy as web or mobile app
- Use advanced models (Random Forest, XGBoost)
- Integrate with real-time data or wearable devices
- Add support for local languages and lifestyle-related features

##  References
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
  

