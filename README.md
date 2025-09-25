# Customer_Segmentation_using_unsupervised_Learning
Customer segmentation using K-Means on Mall Customers data (Age, Income, Spending Score, Gender). Identifies 5 key personas for targeted marketing. Includes scaling, optimal k selection (silhouette/elbow), and visualizations.
# Mall Customer Segmentation with K-Means

This project performs **unsupervised customer segmentation** on the *Mall Customers* dataset using **K-Means clustering** to identify distinct customer groups based on demographics and spending behavior.

## 📊 Dataset Overview
- **200 customers**
- Features:
  - `Gender` (Male/Female)
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)` – mall-assigned behavioral metric

## 🎯 Objective
Discover natural customer segments to enable:
- Targeted marketing campaigns  
- Personalized promotions  
- Strategic customer engagement  

## 🔧 Methodology
- Preprocessed: Encoded `Gender`, standardized all features
- Selected optimal **k = 5** using **Silhouette Score** and **Elbow Method**
- Applied **K-Means clustering** (`k-means++` initialization)
- Evaluated with **Silhouette Score (~0.55)** and visual validation

## 👥 Identified Segments (Typical Interpretation)
1. **Low Income, Low Spending**  
2. **Low Income, High Spending** (impulsive)  
3. **Mid Income, Mid Spending**  
4. **High Income, Low Spending** (cautious)  
5. **High Income, High Spending** (ideal customers)

## 📈 Outputs
- Cluster labels for each customer  
- 2D & 3D visualizations (Income vs. Spending Score, Age)  
- Cluster summary statistics  

## 🚀 How to Run
1. Clone this repo  
2. Upload `Mall_Customers.csv`  
3. Run the Jupyter Notebook or Python script in **Google Colab** or locally  

## 📦 Dependencies
```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
```

---

💡 **Insight**: This model reveals actionable customer personas—no labels needed! Perfect for retail analytics and CRM strategy.
