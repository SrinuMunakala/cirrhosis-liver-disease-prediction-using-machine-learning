# Cirrhosis Liver Disease Prediction Using Machine Learning

This project aims to predict the survival status of patients with liver cirrhosis using machine learning techniques. It uses a dataset of clinical features to build a classification model and provide insights through data visualization and evaluation metrics.

## 📁 Dataset

The dataset `cirrhosis.csv` contains 418 records and 19 features, including:

- **Age, Sex, Ascites, Hepatomegaly, Spiders, Edema**
- **Laboratory test results**: Bilirubin, Cholesterol, Albumin, Prothrombin Time, etc.
- **Target variable**: `Status` (Censored, Died)

> Some features are binary (Yes/No), while others are continuous. Missing values are handled during preprocessing.

## ⚙️ Technologies Used

- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  
- **Jupyter Notebook**

## 🧠 Machine Learning Workflow

1. **Data Cleaning**  
   - Removed null values and encoded categorical variables.
   
2. **Exploratory Data Analysis (EDA)**  
   - Visualized correlations and distributions using `seaborn` and `matplotlib`.

3. **Model Building**  
   - Used classification models like Logistic Regression, Decision Tree, and Random Forest.
   - Evaluated using accuracy, precision, recall, and confusion matrix.

4. **Model Evaluation**  
   - Compared performance across models.
   - Selected the best-performing model based on accuracy and F1-score.

## 📊 Sample Visualizations

- Heatmaps to show correlation between features  
- Bar plots for survival analysis  
- Confusion matrix of prediction results

## 🧪 How to Run

1. Clone the repository  
```bash
git clone https://github.com/your-username/cirrhosis-liver-disease-prediction.git
cd cirrhosis-liver-disease-prediction

2. Install dependencies
pip install -r requirements.txt

3. Open the notebook
jupyter notebook "project (2).ipynb"

4. Run all cells to train and evaluate the model.
