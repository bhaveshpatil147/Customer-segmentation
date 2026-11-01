# Customer Segmentation using K-Means Clustering

## Project Overview
This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to segment mall customers based on their annual income and spending score.

The main objective is to identify different customer groups so businesses can better understand customer behaviour and develop targeted marketing strategies.

## Dataset
- **Dataset:** Mall Customer Segmentation Dataset
- **Total Records:** 200 customers
- **Features used:** Annual Income (k$), Spending Score (1–100)
- **Target variable:** Not applicable (unsupervised learning)

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Loaded and explored the dataset.
2. Checked for missing values and duplicate records.
3. Performed Exploratory Data Analysis (EDA).
4. Selected Annual Income and Spending Score as clustering features.
5. Applied StandardScaler for feature scaling.
6. Used the Elbow Method to analyse the optimal number of clusters.
7. Used Silhouette Score to evaluate cluster separation.
8. Applied K-Means Clustering with 5 clusters.
9. Visualized the customer segments.
10. Analysed the average characteristics of each cluster.

## Model Evaluation
The optimal number of clusters was selected using the Elbow Method and Silhouette Score.

- **Optimal Clusters:** 5
- **Silhouette Score:** 0.5547

## Customer Segments

| Cluster | Customer Segment | Customers |
|---|---|---:|
| 0 | Average Income, Average Spending | 81 |
| 1 | High Income, High Spending | 39 |
| 2 | Low Income, High Spending | 22 |
| 3 | High Income, Low Spending | 35 |
| 4 | Low Income, Low Spending | 23 |

## Key Findings
- Identified five distinct customer segments.
- Cluster 0 is the largest group, containing 81 customers.
- Cluster 1 represents high-income customers with high spending scores.
- Cluster 3 represents high-income customers with low spending scores.
- The clustering results can help businesses plan targeted marketing campaigns and customer engagement strategies.

## Repository Contents
- `Customer_Segmentation.ipynb` – Google Colab/Jupyter Notebook containing the complete project code and analysis.
- `README.md` – Project documentation.

## Conclusion
K-Means Clustering successfully grouped 200 mall customers into five segments based on annual income and spending score. The project demonstrates how unsupervised machine learning can help identify customer behaviour patterns and support data-driven marketing decisions.
