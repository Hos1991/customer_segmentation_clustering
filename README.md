# 🛍️ Customer Segmentation using KMeans Clustering

## 📌 Project Overview
This project segments mall customers into different groups using KMeans clustering based on income and spending behavior.

## 📊 Dataset
- Source: [Kaggle - Mall Customer Segmentation Dataset](https://www.kaggle.com/datasets/shwetabh123/mall-customers)
- Goal: Understand different customer groups and provide business insights.

## 🔍 Steps Performed
- Data loading
- Exploratory Data Analysis (EDA)
- Feature selection
- Feature scaling
- Elbow method to choose number of clusters
- KMeans clustering
- Cluster interpretation
- Business insight generation

## ⚙️ Features Used
- Annual Income (k$)
- Spending Score (1-100)

## 🤖 Model Used
- KMeans Clustering

## 📈 Results
The Elbow Method suggested using **5 clusters**.

### Cluster Summary
- Cluster 1: High income / High spending → VIP customers
- Cluster 3: High income / Low spending → Potential customers for targeted campaigns
- Cluster 2: Low income / High spending → Young active spenders
- Cluster 4: Low income / Low spending → Low-value customers
  
## 💡 Key Insights
- Younger customers showed higher spending behavior.
- High income does not always mean high spending.
- Some older high-income customers had low spending scores.
- Customer behavior depends on income, age, and lifestyle patterns.

## 🧠 Business Value
This segmentation can help businesses:
- Target high-value customers
- Design better marketing campaigns
- Personalize offers
- Identify low-engagement customer groups

## ▶️ How to Run
1. Clone the repository
2. Install dependencies:
  pip install -r requirements.txt
3. Download the dataset from Kaggle
4. Place the CSV file in the data/ folder
5. Run the notebook

## 🏗️ Project Structure
```text
customer-segmentation-clustering
│
├── notebook/
├── data/
├── requirements.txt
├── README.md
```
## 👨‍💻 Author
Hossein Fathi
