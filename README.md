## E-Commerce Predictor 
A Machine Learning project that predicts Yearly Amount Spent by customers on an e-commerce platform based on their
usage patterns. The model is trained using real-world-style customer data and deployed using Streamlit for interactive
predictions.

## Features
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Scikit-learn modeling pipeline
- Train/test split with scaling
- Multiple regression models (ElasticNet, Linear, Ridge, etc.)
- Streamlit web app for deployment
- 
## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit
- Pickle


## project/
│
├── models/
│   ├── model.pkl            # Trained ElasticNet model
│   └── scaler.pkl           # Scaler used to preprocess features
│
├── app/
│   └── app.py               # Streamlit web app for prediction
│
├── data/
│   └── ecommerce_data.csv   # Dataset
│
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation


##  How the Model Works
Input Features:
- Avg. Session Length
- Time on App
- Length of Membership
Target Variable:
- Yearly Amount Spent

  
## Model:
- ElasticNet Regression with GridSearchCV for hyperparameter tuning.
 Running the Project Locally

## Future Improvements
- Add more features (Time on Website, Location)
- Train on larger or real-world datasets
- Deploy on Streamlit Cloud or Heroku
