# 🧠 Customer Behavior Analytics Project

## 📌 Project Objective
The goal of this project is to **analyze customer behavior** using data-driven techniques to help businesses understand purchasing patterns, identify key customer segments, and design targeted marketing strategies.  

By applying **data cleaning, exploratory data analysis (EDA), and clustering (K-Means)**, this project demonstrates how analytics can uncover valuable insights from customer transaction data.

---

## 📊 Dataset Description
The dataset used in this project contains information about customers, including:
- **Customer ID** — unique identifier for each customer  
- **Gender** — male/female  
- **Age** — customer’s age  
- **Annual Income (k$)** — income range of the customer  
- **Spending Score (1–100)** — score assigned based on spending patterns and behavior  

📁 **Source:** A publicly available dataset (Mall Customers Data) or synthetic company data.  
📈 **Size:** ~200 rows × 5 columns  

This dataset helps identify patterns between customer demographics and spending habits.

---

## ⚙️ Methodology Summary
### Step 1: Data Collection
- Imported customer data from a CSV file.  
- Queried and explored data using SQL for basic insights.  

### Step 2: Data Cleaning & Preprocessing
- Removed duplicates and handled missing values.  
- Encoded categorical variables (e.g., Gender).  
- Scaled numerical variables (Income, Spending Score) for clustering.

### Step 3: Exploratory Data Analysis (EDA)
- Used Python libraries (`matplotlib`, `seaborn`) to visualize distributions.  
- Analyzed correlations between age, income, and spending score.  

### Step 4: Customer Segmentation (Clustering)
- Applied **K-Means Clustering** to group customers.  
- Used the **Elbow Method** to determine the optimal number of clusters (k=4).  
- Visualized clusters using scatter plots and cluster centroids.  

### Step 5: Insights Visualization (Power BI)
- Built an interactive **Power BI dashboard** to visualize:
  - Cluster-wise customer distribution  
  - Spending behavior and revenue trends  
  - Gender and age demographics  

---

## 🔑 Key Findings
- **Cluster 1:** High-income, high-spending customers — best for loyalty programs.  
- **Cluster 2:** Medium-income, average-spending customers — growth potential.  
- **Cluster 3:** Budget-conscious customers — respond well to discounts.  
- **Cluster 4:** Low-income, low-spending group — focus on retention strategies.  
- Majority of high-spending customers are aged **25–35**.  

These findings help businesses design **personalized marketing campaigns** and optimize sales strategies.

---

## 🧮 Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn) |
| Data Querying | SQL (MySQL / SQLite /POSTGRESQL) |
| Visualization | Power BI (v2.130 or above) |
| Development | Jupyter Notebook |
| Version Control | Git & GitHub |



