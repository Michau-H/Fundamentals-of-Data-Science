# Fashion-MNIST Analysis Project

This project involves analysis and classification of the **Fashion-MNIST** dataset as part of a machine learning/data science workflow. The dataset contains grayscale images of clothing items categorized into 10 classes.  

In several steps of the project, **CUDA technology** was utilized to accelerate computations, particularly during dimensionality reduction, clustering, and model training. 
However, due to the lack of a supported graphics card, **I used Google Colab with limited time on GPU** for these tasks, which provided a temporary solution for GPU acceleration.

---

## 📌 What Was Done

- **Data summary**:  
  Basic statistics were collected and class distributions were visualized. Example images were displayed.

- **Dimensionality reduction**:  
  Applied PCA for feature reduction and t-SNE for visualization.

- **Visualization**:  
  The reduced data was visualized using UMAP in 2D and 3D with true labels as colors to examine class separability.

- **Clustering**:  
  Used K-Means and DBSCAN. Results were compared with true labels using clustering metrics. Outliers and cluster quality were analyzed.

- **Train/Test split**:  
  Dataset was split using stratified sampling to maintain class balance.

- **Classification**:  
  Model KNeighborsClassifier was trained and evaluated (including cross_val). Metrics included accuracy, F1-score, and confusion matrix.

- **ChatGPT comparison**:  
  Each step was discussed with ChatGPT. Differences between initial assumptions and AI-suggested methods were noted and discussed in the final report.

---

## 🛠️ Tools

Python, NumPy, Pandas, Scikit-learn, Matplotlib, t-SNE, PCA, UMAP, CUDA
