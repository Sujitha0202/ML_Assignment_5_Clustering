ML Assignment 5 – Clustering Algorithm
This project demonstrates the application of **unsupervised learning** techniques using **K-Means** and **Hierarchical Clustering** on the **Iris dataset**.  
It is developed as part of the **Machine Learning module assignment** to evaluate understanding of clustering algorithms.

---

## Objective
The objective of this assessment is to evaluate your understanding and ability to apply clustering techniques to a real-world dataset.

---

## Dataset
**Dataset Used:** Iris dataset (from `sklearn.datasets`)  
- Features: Sepal Length, Sepal Width, Petal Length, Petal Width  
- Total Samples: 150  
- Target column (species) was dropped as this is an *unsupervised* learning task.

---

## Steps Performed
### 1. Loading and Preprocessing
- Loaded the Iris dataset using `load_iris()` from sklearn.  
- Dropped the target (species) column.  
- Checked for missing values.  
- Standardized the feature values using `StandardScaler`.

### 2. K-Means Clustering
- Implemented **K-Means Clustering** with 3 clusters.  
- Explained the working principle:
  > K-Means partitions data into K clusters by minimizing the sum of squared distances between each point and its cluster centroid.
- Visualized clusters using Seaborn scatterplots.

### 3. Hierarchical Clustering
- Implemented **Agglomerative (Hierarchical) Clustering**.  
- Explained the working principle:
  > Hierarchical clustering builds a hierarchy (tree) of clusters using a bottom-up approach.
- Visualized dendrogram and cluster formation.

### 4. Visualization
- Plotted both K-Means and Hierarchical clusters using Matplotlib and Seaborn.
- Displayed dendrogram for hierarchical relationships.

### 5. Comparison and Conclusion
- Both methods showed similar patterns of natural clustering in the Iris dataset.
- K-Means is faster for larger datasets, while Hierarchical Clustering provides better interpretability.

---

## Algorithms Used
| Algorithm | Description | Marks |
|------------|--------------|-------|
| **K-Means Clustering** | Partitions data into `K` clusters by minimizing within-cluster variance. | 4 |
| **Hierarchical Clustering** | Builds clusters step-by-step forming a tree structure. | 4 |

**+1 mark** for preprocessing and **+1 mark** for timely submission.

---

## Visual Outputs
- K-Means Clustering Scatter Plot  
- Hierarchical Clustering Dendrogram  
- Agglomerative Cluster Visualization  

*(All visualizations are displayed within the Jupyter Notebook)*

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Scipy

---

## File Included
| File Name | Description |
|------------|-------------|
| `ML_Assignment_5_Clustering.ipynb` | Jupyter Notebook containing all code, explanations, and visualizations |

---

## How to Run the Notebook
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the `.ipynb` file  
3. Click **Runtime → Run All**

---

## Author
**Name:** Sujitha Sudheer TS 

---

## Conclusion
Both **K-Means** and **Hierarchical Clustering** effectively group the Iris dataset into natural clusters.  
The project demonstrates understanding of unsupervised learning and the practical use of clustering algorithms in data science.

---

*If you found this helpful, don’t forget to star the repository!* 
