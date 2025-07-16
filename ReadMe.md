
# Customer Segmentation Using K-Means Clustering

## 🔍 Objective
To segment credit card customers based on their financial behavior and usage patterns using unsupervised machine learning (K-Means clustering). This segmentation helps identify key customer groups for targeted marketing and personalized offers.

## 📂 Dataset Overview
The dataset contains synthetic records of 300 customers with the following features:
- Age, Gender, Annual Income, Credit Limit
- Balance, Min Payment, Payment History
- Number of Late Payments, Tenure

## 🛠 Tools & Libraries Used
- **Python**: Data handling and machine learning
- **Pandas**, **NumPy**: Data preprocessing and wrangling
- **Matplotlib**, **Seaborn**: Visualization
- **Scikit-learn**: KMeans, PCA, StandardScaler

## 🧼 Preprocessing Steps
- Encoded categorical variable 'Gender' (Male=0, Female=1)
- Scaled numerical features using StandardScaler
- Removed identifier column (CustomerID)

## 🔄 Clustering Method
- Used the **Elbow Method** to determine optimal clusters (`k=4`)
- Applied **KMeans** clustering on scaled data
- Reduced dimensions using **PCA** for visualization

## 📊 Key Insights from Clusters
- **Cluster 0**: High income, low balance – Potential for high-ticket offers
- **Cluster 1**: Low income, high late payments – High risk customers
- **Cluster 2**: Mid-income, high usage – Credit heavy users
- **Cluster 3**: Long tenure, stable usage – Loyal customers

## 📈 Visualization
- PCA reduced customer data into 2D for visualization
- Cluster scatter plot colored by assigned group

## 💼 Business Impact
- Identified distinct groups to tailor marketing strategies
- Helped design custom retention offers for loyal and high-value customers
- Reduced churn risk by detecting late-paying and risky users

---

### ✅ Conclusion
This project demonstrates how unsupervised learning techniques like KMeans can uncover hidden patterns in customer behavior. These insights are vital for making data-driven decisions in customer relationship management.

