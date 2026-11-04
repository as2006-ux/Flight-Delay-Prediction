# Flight Delay and Cancellation Prediction System

## Project Overview
This project explores flight delay prediction using mathematical and machine learning techniques. It applies regression, classification, clustering, dimensionality reduction, and Hidden Markov Models (HMM) to analyze flight delay patterns.

## Objectives
- Analyze flight delay data.
- Build regression and classification models.
- Identify patterns using clustering algorithms.
- Apply PCA and Factor Analysis.
- Study delay patterns using Hidden Markov Models.
- Compare the performance of different algorithms.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Kaggle

## Project Structure
- `unit-2.ipynb` – Regression and Classification
- `unit-3.ipynb` – Clustering, PCA and Factor Analysis
- `unit-4.ipynb` – Hidden Markov Models
- `unit-5.ipynb` – Algorithm Comparison and Project Summary

## Dataset
The project uses flight records containing information about flight schedules and delays. The dataset is not included in this repository.

## How to Run
1. Download or clone this repository.
2. Open the notebooks using Jupyter Notebook or Google Colab.
3. Upload the required dataset.
4. Run the notebook cells in order.

## Author
GitHub: [as2006-ux](https://github.com/as2006-ux)

## Results and Performance Analysis

### 1. K-Means Clustering
The K-Means algorithm was evaluated using silhouette scores for different cluster counts.

| Number of Clusters (K) | Silhouette Score |
|---|---:|
| 2 | 0.1284 |
| 3 | 0.1162 |
| 4 | 0.1335 |
| 5 | 0.1371 |

The highest silhouette score was obtained at K = 5.

### 2. Principal Component Analysis (PCA)
Six principal components were used to explain approximately 100% of the variance in the selected dataset features. Six components were required to cross the 90% explained variance threshold.

### 3. Overall Analysis
The project explores multiple mathematical and machine learning approaches to understand flight delay patterns, including regression, classification, clustering, dimensionality reduction, and Hidden Markov Models.

Detailed results and visualizations are available in the respective Jupyter notebooks.
