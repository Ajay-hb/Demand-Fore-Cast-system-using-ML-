📊 Demand Forecasting System using Machine Learning
🚀 Overview

This project is a Demand Forecasting Application built using Machine Learning and deployed with Streamlit. It predicts product demand based on key business factors such as pricing, discounts, inventory levels, promotions, and competitor pricing.

The goal of this project is to help businesses optimize inventory, pricing strategies, and supply chain decisions using data-driven insights.

🧠 Features
📈 Predicts demand using trained ML model (XGBoost)
🎯 User-friendly interface with Streamlit
🔄 Handles categorical data using Label Encoding
⚡ Real-time predictions based on user input
📊 Supports multiple business features:
Price
Discount
Inventory Level
Promotion
Competitor Pricing
Category
🏗️ Project Structure
├── Demand_Forecasting.ipynb              # Model training notebook
├── demand_forecasting.csv               # Raw dataset
├── preprocessed_demand_forecasting_data.csv  # Cleaned dataset
├── label_encoders.pkl                   # Saved encoders
├── xgboost_demand_model.pkl             # Trained ML model
├── streamlit_app.py                     # Streamlit application
└── README.md                            # Project documentation
⚙️ Tech Stack
Python 🐍
Pandas & NumPy
Scikit-learn
XGBoost
Streamlit
📊 Model Details
Model Used: XGBoost Regressor
Problem Type: Regression
Target: Demand Prediction
Feature Engineering:
Label Encoding for categorical variables
Data preprocessing and cleaning
💻 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/demand-forecasting.git
cd demand-forecasting
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Streamlit App
streamlit run streamlit_app.py
🖥️ Application Interface

The app allows users to input:

Product Price
Discount Percentage
Inventory Level
Promotion Status (0 or 1)
Competitor Pricing
Category

Then click "Predict Demand" to get results instantly.

🔍 Code Highlights

The core prediction logic from the app:

  prediction = model.predict(input_data[FEATURES])[0]



📈 Use Cases
Retail demand forecasting
Inventory optimization
Pricing strategy analysis
Supply chain planning
🧪 Future Improvements
Add time-series forecasting (LSTM / ARIMA)
Deploy on cloud (AWS / Azure / GCP)
Add visualization dashboards
Improve model accuracy with hyperparameter tuning
🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Ajay Ponnuru

Aspiring Data Scientist & ML Engineer
Passionate about AI, ML, and real-world problem solving
