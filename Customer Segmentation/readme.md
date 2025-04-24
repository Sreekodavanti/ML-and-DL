# Customer Segmentation using K-Means Clustering

This project applies unsupervised machine learning techniques to segment a customer base using K-Means clustering. 
The objective is to group similar customers together to enable more targeted marketing strategies and better business decisions.

## 📁 Dataset

The dataset `customer_segmentation.csv` contains information on **10,127** customers with the following features:

- Demographics (e.g., age, gender, education level, marital status)
- Financial metrics (e.g., estimated income, credit limit, transaction amount)
- Behavioral metrics (e.g., months on book, total relationship count, utilization ratio)

## 🔍 Exploratory Data Analysis (EDA)

- Visualized the distribution of numeric features using histograms.
- Plotted a correlation heatmap for variables with moderate to strong correlations (|correlation| > 0.30).
- Identified potential multicollinearity and trends among features.

## 🛠️ Feature Engineering

- Converted categorical columns (`gender`, `education_level`, `marital_status`) into numeric format.
- Applied one-hot encoding to `marital_status`.
- Removed unnecessary identifiers like `customer_id` before clustering.

## ⚙️ Clustering Process

- Standardized the features using `StandardScaler` to ensure all variables contribute equally to the clustering process.
- Used the **K-Means** clustering algorithm to segment the customers.
- Explored a range of clusters from 1 to 12 to determine the optimal number of clusters using the **elbow method**.
- Finally, chose **10 clusters** for the final segmentation.

## 📊 Visualizations

- Histograms to observe feature distributions.
- Correlation heatmap to evaluate relationships among numerical variables.

## ✅ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook for analysis and visualization

## ⚠️ To-Do (Final Explanation)

The project currently ends after clustering. 
The next steps to complete the analysis include:

- **Labeling clusters** based on dominant features in each group.
- **Profiling customer segments** (e.g., high-income frequent users vs. low-income inactive users).
- **Providing business recommendations** for marketing or customer service strategies based on segment insights.

-----

✨🎉 Happy Coding! 💻😊🚀
