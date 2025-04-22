# Predict_Product_Return_202401100300162
🛍️ Product Return Prediction & Clustering
This project aims to analyze product return behavior using classification techniques and optionally perform unsupervised clustering on product-related data. It includes data visualization, feature analysis, model evaluation, and clustering segmentation using Python and popular ML libraries.

📂 Dataset
The dataset used is product_return.csv, which includes features such as:

purchase_amount: Value of the purchase

review_score: Customer review rating

days_to_delivery: Days between order and delivery

returned: Whether the product was returned (Yes/No)

🧠 Tasks Performed
🔍 Classification
If the returned column is present in the dataset, the following are performed:

Exploratory Data Analysis (EDA)

Distribution plots

Boxplots

Correlation heatmaps

Logistic Regression Model

Evaluation Metrics:

Accuracy, Precision, Recall

Classification Report

Confusion Matrix (Raw & Normalized)

ROC Curve & Precision-Recall Curve

Feature Importance Plot

🔀 Clustering (Unsupervised)
If returned is not present, the project performs clustering:

Standardization of numeric features

K-Means clustering (n_clusters=3)

Cluster visualization with pairplots

Cluster centroid analysis

📊 Sample Visuals
Confusion Matrix Heatmaps

Feature Importance Bars

ROC & PR Curves

Clustering Pairplot Visualizations

🛠️ Technologies Used
Python 3.x

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn (LogisticRegression, KMeans, metrics)



📈 Future Improvements
Include more ML models (Random Forest, XGBoost, etc.)

Hyperparameter tuning

Deploy via Streamlit or Flask for interactive prediction

Add dimensionality reduction (PCA/t-SNE)
