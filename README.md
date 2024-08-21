## Consumer Behavior Analysis using Customer Data

This project involves analyzing consumer behavior using wholesale customer data. The analysis includes feature scaling, dimensionality reduction, clustering, and classification to identify patterns and predict customer segments. Various machine learning techniques are applied to uncover insights and make data-driven decisions.

### Project Overview:

1. **Objective:**
   - The primary goal is to analyze customer behavior data and apply machine learning techniques to identify significant patterns and classify customer segments effectively.

2. **Exploratory Data Analysis (EDA) and Data Cleaning:**
   - **Initial Data Exploration:** Understanding the dataset by exploring distributions, identifying missing values, and determining data types.
   - **Feature Scaling:** Implementing `StandardScaler` and `MinMaxScaler` to normalize the features, making them suitable for machine learning algorithms.
     - **MinMaxScaler:** Scales the data to a fixed range, typically [0, 1], preserving the shape of the original distribution.
     - **StandardScaler:** Standardizes features by removing the mean and scaling to unit variance, making it suitable for models that assume normally distributed input features.

3. **Optimal Feature Selection:**
   - **Recursive Feature Elimination with Cross-Validation (RFECV):** 
     - RFECV is applied to determine the optimal number of features for the classification task. This method helps in selecting the most relevant features while improving model performance.
     

4. **K-Means Clustering:**
   - **Elbow Method for Optimal K:** 
     - The Elbow method is used to identify the optimal number of clusters in the dataset. This helps in segmenting customers into distinct groups based on their behavior.
     

5. **Principal Component Analysis (PCA):**
   - **Dimensionality Reduction:** 
     - PCA is applied to reduce the dimensionality of the dataset, making it easier to visualize and understand the variance explained by the principal components.
     - The data is projected onto the first two principal components to visualize the clusters.

6. **Classification:**
   - **Implementing XGBoost:** 
     - An XGBoost classifier is applied to the scaled data to predict customer segments. The model's performance is evaluated to ensure it generalizes well to new data.

7. **Conclusion:**
   - The analysis identified significant variance in consumer behavior, allowing for effective segmentation and targeted marketing strategies. The combination of scaling, feature selection, clustering, and classification provided a comprehensive understanding of customer data.

### How to Use:

1. **Clone the Repository:**
   - Clone this repository to your local machine using `git clone`.
   
2. **Install Dependencies:**
   - Install the required Python packages using `pip install -r requirements.txt`.

3. **Run the Notebook:**
   - Open the notebook in Jupyter and execute the cells in sequence to perform the analysis and generate the plots.


### Conclusion:

This project demonstrates the effective use of machine learning techniques to analyze customer behavior data. By applying feature scaling, dimensionality reduction, clustering, and classification, valuable insights were gained, enabling data-driven decisions for customer segmentation and targeted marketing strategies.
