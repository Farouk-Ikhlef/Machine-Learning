# Machine Learning — Lab Work (TPs)

**Master 1 Artificial Intelligence — Université Aboubekr Belkaid, Tlemcen**  
**Academic Year: 2025–2026**

Machine Learning lab work and practical sessions (TPs) covering data preprocessing, supervised and unsupervised learning, model evaluation, and visualization.

---

## Repository Structure

```
Machine-Learning/
├── data treatment/           # Data preprocessing: cleaning, scaling, encoding, visualization
├── linear regression from scratch/  # Simple, multiple & polynomial regression
├── non lineare/              # Non-linear regression and classification models
├── KNN algorithm/            # K-Nearest Neighbors classification with hyperparameter tuning
├── clustering/               # Unsupervised learning: K-Means, CAH, GMM, Mean-Shift, DBSCAN
└── README.md
```

---

## Topics Covered

### Supervised Learning
| Topic | Folder | Description |
|-------|--------|-------------|
| Linear Regression | `linear regression from scratch/` | Simple, multiple, and polynomial regression implemented from scratch |
| Non-linear Models | `non lineare/` | Binary and multiclass classification, Naive Bayes |
| K-Nearest Neighbors | `KNN algorithm/` | KNN classification with distance-based prediction and k tuning |

### Unsupervised Learning
| Topic | Folder | Description |
|-------|--------|-------------|
| Clustering | `clustering/` | K-Means, Agglomerative Hierarchical Clustering (CAH), Gaussian Mixture Models (GMM), Mean-Shift, DBSCAN |

### Data Preprocessing
| Topic | Folder | Description |
|-------|--------|-------------|
| Data Treatment | `data treatment/` | Handling missing values, feature scaling (StandardScaler), encoding, train/test split, exploratory data analysis |

---

## Datasets Used

| Dataset | Task | Samples | Features | Source |
|---------|------|---------|----------|--------|
| Iris | Multiclass classification | 150 | 4 | `sklearn.datasets` |
| Breast Cancer Wisconsin | Binary classification | 569 | 30 | `sklearn.datasets` / UCI |
| Diabetes | Regression | 442 | 10 | `sklearn.datasets` |
| Pima Indians Diabetes | Binary classification | 768 | 8 | Kaggle / UCI |
| Wine | Multiclass classification | 178 | 13 | `sklearn.datasets` / UCI |

---

## Evaluation Metrics

- Accuracy, Precision, Recall, F1-score, Fβ-score
- Confusion matrices and classification reports
- Visual comparison of model performance

---

## Environment

- **Python** 3.x
- **IDE**: VS Code with Jupyter Notebook (.ipynb)
- **Libraries**: scikit-learn, NumPy, pandas, Matplotlib, Seaborn

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

---

## Author

**Omar El Farouk IKHLEF**  
M1 Artificial Intelligence — Université de Tlemcen, Algeria  
[LinkedIn](https://www.linkedin.com/in/omar-el-farouk-ikhlef) · omarelfarouk.ikhlef@hotmail.com
