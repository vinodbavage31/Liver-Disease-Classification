# Liver Disease Prediction System

## 1️⃣ Project Title
**Liver-Disease-Prediction**  
*An end-to-end machine learning solution for clinical diagnosis.*

## 2️⃣ Short Description
This project develops a predictive model to identify liver disease based on biochemical markers (such as Albumin, Bilirubin, and Enzymes). It includes a full data preprocessing pipeline, a comparison of multiple classification algorithms, and an interactive Streamlit web application for real-time patient assessment.

## 3️⃣ Features / Functionality
- **Automated Data Cleaning**: Handles missing clinical data using mean and mode imputation.
- **Multi-Model Training**: Compares Logistic Regression, Decision Trees, and Random Forest classifiers.
- **Statistical Evaluation**: Comprehensive metrics including Cross-Validation Accuracy, Precision, Recall, and F1-score.
- **Interactive Dashboard**: A user-friendly Streamlit interface allowing health professionals to input patient data and receive instant predictions.
- **Model Persistence**: Saves the best-performing model (Logistic Regression) for production use.

## 4️⃣ Tech Stack
- **Language**: Python 3.12
- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (StandardScaler, LabelEncoder, RandomForest)
- **Visualization**: Matplotlib, Seaborn
- **Web Framework**: Streamlit
- **Deployment Tools**: Joblib (Serialization), Pyngrok (Tunneling)


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## 5️⃣ Project Structure
```text
├── project-data.csv          # Clinical dataset
├── liver_analysis.ipynb      # Main Jupyter/Colab notebook
├── app.py                    # Streamlit web application script
├── best_model.pkl            # Trained model file (serialized)
├── logistic_regression_model.pkl
├── decision_tree_model.pkl
└── random_forest_model.pkl
```

## 6️⃣ Setup / Installation Instructions
1.  **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/liver-disease-prediction.git
    cd liver-disease-prediction
    ```
2.  **Install Dependencies**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn streamlit joblib pyngrok
    ```
3.  **Download the Dataset**
    Ensure `project-data (1) (1).csv` is in the project root directory.

## 7️⃣ Usage
1.  **Train and Save Model**
    Run the analysis script or notebook to generate the `.pkl` model files.
2.  **Run the Web Application**
    ```bash
    streamlit run app.py
    ```
3.  **Input Data**
    Enter biochemical values like Albumin, Alkaline Phosphatase, and Bilirubin in the sidebar to see the prediction result.

## 8️⃣ Future Improvements
- **Class Imbalance Handling**: Implement SMOTE or oversampling to improve detection of rare disease categories.
- **Deep Learning**: Integration of Neural Networks to compare against traditional ensemble methods.
- **Feature Engineering**: Incorporate domain-specific ratios (e.g., AST/ALT ratio) to increase model sensitivity.
- **Cloud Deployment**: Host the app on Streamlit Community Cloud or Heroku for permanent access.

## 9️⃣ Author / Contribution
**Developed by REVANSIDDAPPA**

### Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
