🏠 House Price Prediction (Kaggle)
This project predicts house prices using the Kaggle House Prices: Advanced Regression Techniques dataset.

📌 Project Overview
Uses a simple Linear Regression model
Handles missing values using SimpleImputer
Selected features:
OverallQual (Overall material and finish quality)
GrLivArea (Above ground living area in square feet)
GarageCars (Garage capacity in cars)
TotalSF (Basement + 1st + 2nd floor square feet)
Outputs predictions in submission.csv ready for Kaggle submission
📂 Project Structure
house_price_prediction/
├── train.csv
├── test.csv
├── house_price_prediction.ipynb
├── requirements.txt
├── README.md
└── submission.csv (generated after running notebook)
🚀 How to Run
Clone this repo or download files
Install dependencies:
pip install -r requirements.txt
Open Jupyter Notebook:
jupyter notebook house_price_prediction.ipynb
Run all cells → generates submission.csv
📊 Example Results
R² Score: ~0.74 (on validation set)
MSE: ~1.1e+10
