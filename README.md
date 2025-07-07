<h1>Mall customer Segmentation Project using K-means </h1>
This project focuses on performing customer segmentation for a mall using unsupervised machine learning techniques. By analyzing customer data, we aim to identify distinct groups of customers based on their demographic and spending habits. This segmentation can help the mall understand its customer base better, allowing for more targeted marketing strategies, personalized offers, and improved customer experience. <br> <br>
<h2>✨ Features</h2>
<b>Data Loading & Preprocessing:</b> Reads customer data from a CSV file, performs initial data sanity checks (missing values, duplicates), and prepares features for clustering.<br>
<b>Exploratory Data Analysis (EDA):</b> Visualizes the distribution of key customer attributes like Age, Annual Income, and Spending Score using histograms.<br>
<b>Feature Engineering:</b> Transforms categorical features (Gender) using One-Hot Encoding and scales numerical features using StandardScaler to ensure all features contribute equally to the clustering process.<br>
<b>K-Means Clustering:</b> Applies the K-Means algorithm to group customers into distinct segments.<br>
<b>Optimal K Determination:</b> Utilizes the Elbow Method to find the optimal number of clusters for the dataset.<br>
<b>Model Persistence:</b> Saves the trained K-Means model using `joblib` for future use without retraining.<br>
<b>Segment Analysis:</b> Provides insights into the characteristics of each identified customer segment.<br>
<h2>✨  🚀 Technologies Used</h2>
<b>Python:</b> The primary programming language.<br>
<b>Pandas:</b> For data manipulation and analysis.<br> 
<b>NumPy</b>: For numerical operations. Matplotlib: For creating static, interactive, and animated visualizations. Seaborn: For statistical data visualization, built on Matplotlib.<br>
<b>Scikit-learn:</b> <br>
<ul>
  <li>KMeans: For performing customer clustering.</li>
  <li>StandardScaler: For scaling numerical features.</li>
  <li>OneHotEncoder: For encoding categorical features.</li>
  <li>ColumnTransformer: For applying different transformations to different columns.</li>
  <li>Joblib: For saving and loading the trained machine learning model.</li>
</ul>
<h2>💾 Dataset</h2>
The project uses a `mall_cust_segmentation.csv` dataset, which contains the following columns:<br>
<b>Customer ID:</b> Unique identifier for each customer.<br>
<b>Age:</b> Age of the customer.<br>
<b>Gender:</b> Gender of the customer (Male/Female).<br>
<b>Annual Income:</b> Annual income of the customer (in USD).<br>
<b>Spending Score:</b> A score (1-99) assigned by the mall based on customer behavior and spending habits.<br>



