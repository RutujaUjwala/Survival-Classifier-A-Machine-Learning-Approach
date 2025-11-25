# Survival Classifier: A Machine Learning Approach

This project aims to predict the survival of lung cancer patients using machine learning techniques. Given patient medical histories, demographics, and health records, the model performs binary classification to forecast whether a patient will survive post-treatment.

<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/24774e38-5054-4d59-b536-dea1d0fd7283" />


## 🩺 Project Objective

- Build a predictive system for lung cancer patient survival based on diagnosis data.
- Explore clinical and demographic features to determine their influence on survival.
- Deploy a robust machine learning pipeline for binary classification (Survived/Not Survived).

## 🗂️ Dataset

The dataset (`dataset_med.csv`) contains the following features:

- Demographics: `age`, `gender`, `country`
- Diagnosis: `diagnosis_date`, `cancer_stage`, `family_history`, `smoking_status`
- Medical details: `bmi`, `cholesterol_level`, `hypertension`, `asthma`, `cirrhosis`, `other_cancer`
- Treatment: `treatment_type`, `end_treatment_date`
- Target: `survived` (`1` if survived, `0` if not)

## 📝 Approach

1. **Data Collection & Preparation:**
    - Import and inspect the dataset for completeness and correctness.
    - Identify categorical and numerical features.
    - Encode categorical variables and normalize/standardize data as needed.
2. **Exploratory Data Analysis:**
    - Discover relationships between features and the survival outcome.
    - Visualize distributions and correlations.
3. **Modeling:**
    - Employ supervised learning algorithms suitable for binary classification (e.g., Logistic Regression, Random Forest, SVM).
    - Split the data into train and test sets.
    - Evaluate model performance with metrics like Accuracy, Precision, Recall, F1-score, and ROC-AUC.
4. **Interpretation:**
    - Investigate feature importance to understand key predictors of survival.
5. **Deployment (optional):**
    - Prepare a pipeline for model inference or an interactive web app.

## 🚀 Usage

Clone the repository and open the `Lung _cancer_project.ipynb` notebook in Jupyter or compatible editor for step-by-step implementation.

```bash
git clone https://github.com/RutujaUjwala/Survival-Classifier-A-Machine-Learning-Approach.git
cd Survival-Classifier-A-Machine-Learning-Approach
# Open the notebook in JupyterLab or your preferred tool
```

## 🔧 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the dependencies with:

```bash
pip install -r requirements.txt
```

## 📁 Repository Structure

- `.github/workflows/main.yml`: GitHub Actions workflow configuration.
- `Lung _cancer_project.ipynb`: Main analysis, model development, and results.
- `dataset_med.csv`: Patient data (not included in the repo for privacy).
- `README.md`: This file.

## ❓ FAQ

- **Q: What is the target variable?**  
  A: `survived`, which is 1 if the patient survived, 0 otherwise.

- **Q: Can I use another dataset?**  
  A: Yes, ensure its format matches or preprocess accordingly.

- **Q: How do I contribute?**  
  A: Fork the repo, commit changes to a branch, and open a Pull Request.

---

## 📜 License

See the [LICENSE](LICENSE) file for license rights and limitations.

---

**Contact:**  
For questions or feedback, please open an issue or contact [@RutujaUjwala](https://github.com/RutujaUjwala).


