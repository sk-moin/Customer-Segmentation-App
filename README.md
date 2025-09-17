# Customer-Segmentation-App
# 🛍️ Customer Segmentation with K-Means

This project applies K-Means clustering to segment customers based on demographic and purchasing behavior. The final model is deployed as an interactive Streamlit web app that predicts a customer’s segment from input features.

# 📂 Project Structure
├── customer_segmentation.csv   # Raw dataset
├── EDA_Model.ipynb             # Exploratory Data Analysis & model training notebook
├── kmeans_model.pkl            # Trained K-Means clustering model
├── scaler.pkl                  # Pre-fitted StandardScaler for preprocessing
├── segmentation.py             # Streamlit app for customer segmentation
└── README.md                   # Project documentation

# 🚀 Features

* Exploratory Data Analysis (EDA):

Data cleaning, feature engineering, visualization of customer patterns.

* Modeling:

K-Means clustering to group customers into meaningful segments.

StandardScaler used for feature scaling.

* Deployment:

Streamlit app (segmentation.py) for real-time customer segment prediction.

# 📊 Dataset

The dataset (customer_segmentation.csv) contains demographic and transactional features such as:

Age

Income

Total Spending (sum of purchases)

Number of Web Purchases

Number of Store Purchases

Number of Web Visits per Month

Recency (days since last purchase)

# 🧠 Model

Algorithm: K-Means Clustering

Preprocessing: StandardScaler normalization

Outputs: Customer segment (Cluster 0, Cluster 1, …)

# 💻 Streamlit App

Run the app locally:

# Install dependencies
pip install -r requirements.txt

# Start the app
streamlit run segmentation.py

# App Workflow

Enter customer details (age, income, spending, purchases, visits, recency).

Click Predict Segment.

The app displays the predicted customer cluster.

# 📦 Requirements

Python 3.8+

pandas

numpy

matplotlib

seaborn

scikit-learn

joblib

streamlit

(Install with pip install -r requirements.txt)

# 📈 Example Use Case

A retail company can use this segmentation model to:

Identify high-value customers.

Personalize marketing campaigns.

Optimize product recommendations.

# 🔮 Future Improvements

Add visualizations of customer clusters in the app.

Test different clustering algorithms (DBSCAN, Gaussian Mixtures).

Deploy on Streamlit Cloud or Dockerize the app for production.
