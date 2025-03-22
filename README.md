# 🔷 Diamond Cut Classification with KNN, PCA, and t-SNE

This project explores how to classify diamonds with an **Ideal cut** using **K-Nearest Neighbors (KNN)** combined with dimensionality reduction techniques such as **PCA** and **t-SNE**.

---

## 📊 Project Objectives

- Classify diamonds based on physical features using:
  - **KNN with polynomial features**
  - **KNN + PCA (Principal Component Analysis)**
  - **KNN + t-SNE (T-distributed Stochastic Neighbor Embedding)**
- Evaluate classification performance using:
  - Confusion Matrix
  - Classification Report
  - Matthews Correlation Coefficient
- Visualize the classification results in 2D space using PCA and t-SNE

---

## 📁 Dataset

- **Name**: Diamonds Dataset  
- **Source**: [Kaggle – Diamonds by Shivam Bansal](https://www.kaggle.com/datasets/shivam2503/diamonds)

> Download the dataset and place it in the `data/` folder as `diamonds.csv`.

---

## ⚙️ Techniques & Libraries Used

- Polynomial Feature Expansion
- K-Nearest Neighbors (KNN)
- Dimensionality Reduction:
  - PCA (Principal Component Analysis)
  - t-SNE (T-distributed Stochastic Neighbor Embedding)
- Evaluation Metrics:
  - Accuracy (R²)
  - Confusion Matrix
  - Classification Report
  - Matthews Correlation Coefficient (MCC)
- Visualization with Matplotlib and Seaborn

---

## 🧱 Project Structure

```
diamond-knn-visualization/
│
├── data/
│   └── diamonds.csv
│
├── Diamond_KNN_Classifier_PCA_TSNE.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/mgedna/diamond-knn-visualization.git
cd diamond-knn-visualization
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Place the dataset in the `data/` folder as `diamonds.csv`.

4. Open the notebook:
```bash
jupyter notebook Diamond_KNN_Classifier_PCA_TSNE.ipynb
```

---

## 👤 Author

**Edna Memedula**
📫 [LinkedIn](https://www.linkedin.com/in/edna-memedula-24b519245) • [GitHub](https://github.com/mgedna) 

