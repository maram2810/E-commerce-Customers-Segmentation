# Customer Segmentation Using Machine Learning  

## 📌 Project Overview  
This project aims to segment customers based on their transactional behavior using unsupervised machine learning. The goal is to identify customer groups and suggest strategies for offering coupons to increase loyalty and satisfaction.  

## 🚀 Key Steps  
1. **Data Preprocessing**: Merged multiple datasets (customers, transactions, cities, etc.).  
2. **Feature Engineering**: Created new features like transaction count, burn rate, etc.  
3. **Clustering**: Used **K-Means** to segment customers into meaningful groups.  
4. **Evaluation**: Used **Silhouette Score** and **Elbow Method** to optimize clusters.  
5. **Cluster Analysis**: Visualized clusters and provided **coupon strategies**.  

## 🔹 Results & Coupon Strategy  
- **Cluster 0:** High transaction customers in urban areas → **Offer VIP discounts & cashback**  
- **Cluster 1:** Low transaction customers in non-urban areas → **Give welcome offers & incentives**  
- **Cluster 2:** Medium transaction customers with steady activity → **Provide loyalty rewards**  
- **Cluster 3:** Inactive or low transaction users → **Send targeted promotions & reminders**  

## 📊 Visualizations  
- **Elbow Method** to determine optimal clusters.  
- **Scatter plots** for transactions & burn rates.  

## 🛠️ Tools & Technologies  
- Python, Pandas, NumPy  
- Scikit-learn (K-Means, clustering metrics)  
- Matplotlib, Seaborn (Data Visualization)  

## 📂 How to Run the Code  
1. Clone this repository:  
