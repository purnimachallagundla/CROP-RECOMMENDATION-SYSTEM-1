# 🌾 Crop Yield Prediction using Machine Learning
This project predicts **crop yield** using a **Random Forest Regressor** trained on the [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset).  
It includes data preprocessing, model training, evaluation, and visualization of results.

## 📌 Features
- Preprocessing: missing value imputation, scaling, and one-hot encoding  
- Random Forest regression for yield prediction  
- Evaluation with MAE, RMSE, and R² score  
- Visualizations:
  - Correlation heatmap  
  - True vs Predicted scatter plot  
  - Residuals histogram  
  - Top 10 feature importances  

## 🛠️ Installation
Clone the repository and install required dependencies:
```bash
git clone https://github.com/your-username/crop-yield-prediction.git
cd crop-yield-prediction
pip install -r requirements.txt
🚀 Usage
Run the script with:
bash
Copy code
python crop_recommendation_system.py
Make sure Crop_recommendation.csv is in the same directory or update the path in the script.

📊 Example Output
Model Performance (example):
yaml
Copy code
MAE  : 3.91
RMSE : 4.96
R²   : 0.97

Graphs Generated:
Correlation Heatmap
True vs Predicted Scatter Plot
Residuals Histogram

Feature Importances
📂 Project Structure
bash
Copy code
├── crop_recommendation_system.py   # Main script
├── Crop_recommendation.csv         # Dataset (not included in repo, download separately)
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation

📦 Requirements
Python 3.7+
pandas
numpy
matplotlib
seaborn
scikit-learn

Install via:
bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn

🙌 Acknowledgements
Dataset: Kaggle - Crop Recommendation Dataset
Scikit-learn for ML models and preprocessing
