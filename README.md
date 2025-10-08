# 🛍️ Customer segmentation with Clustering
Unsupervised learning project for identifying customer segments based on purchasing behaviour.

## 🌟 Overview
This project builds a customer segmentation pipeline by transforming raw behavioural data into actionable customer segments using feature engineering, dimensionality reduction and clustering. Customer segmentation enables businesses to design targeted marketing strategies and improve customer retention.

## 🎯 Objectives
- Explore and preprocess real-world customer data.
- Conduct feature engineering to create new meaningful variables.
- Determine the optimal number of clusters and apply clustering algorithms to uncover hidden patterns.
- Provide actionable insights to inform business strategies by interpreting the customer profiles derived from the clustering results.

## 🧠 Techniques Employed
1. **Data preprocessing:** cleaning, feature engineering, statistical summaries, and visualisation.
2. **Clustering algorithms:** K-Means clustering and hierarchical clustering.
3. **Cluster evaluation:** Within Cluster Sum of Squares (WCSS) and Silhouette Score for identifying the optimal cluster size.
4. **Visualisation:**
    - Box-plots for identifying the characteristics of each cluster.
    - Principal Component Analysis (PCA) and t-Distributed Stochastic Neighbour Embedding (t-SNE) for dimensionality reduction and 2D cluster visualisation.

## 🔧 Tools
- `Python`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`

## 📊 Results
- Feature engineering reduced the dataset’s dimensionality by creating five meaningful features: frequency, recency, customer lifetime value (CLV), average unit cost, and age.
- Silhouette Scores and WCSS indicated that the optimal number of clusters was five.
- K-Means identified distinct customer segments with clear behavioural differences.
- Hierarchical clustering grouped customers into only two clusters, making it less informative.
- Combining PCA and t-SNE enabled clear cluster separation in 2D visualisations.

## ➡️ Business Applications
The clustering framework can be adapted across different industries:
- **Finance:** financial behaviour and income level can be used to offer personalised financial products like loans, credit cards, and investment portfolios.
- **Technology:** customer segments are used to market products effectively (e.g. software, hardware, and IT services) based on the needs of customers and businesses.
- **Healthcare:** customer segmentation can include patient demographics, medical history, and age to tailor patient care, financial coverage, and marketing of medical products.

## 📄 Licence
This project is licensed under the [MIT License](LICENSE).

## 👨‍💻 Author
**Juan Antonio Jiménez Cobo**  
- [LinkedIn](https://www.linkedin.com/in/juan-antonio-jiménez-cobo)  
- 📧 Email: juananjico@gmail.com
