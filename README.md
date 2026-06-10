# 🧬 ML-in-Metabolomics

> **IEEE-published research: Gradient Boosting model for Preterm Birth Prediction using metabolomics data — 97% classification accuracy.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)](https://jupyter.org)
[![IEEE](https://img.shields.io/badge/Published-IEEE-00629B?style=flat&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org)
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

---

## 📄 Publication

**"Precision at Its Core: Machine Learning infused Metabolomics Model for Preterm Birth Prediction in Humans"**

*Published in IEEE* — This paper presents a machine-learning-driven approach to predict preterm birth using metabolomics biomarker data, achieving **97% classification accuracy** with a Gradient Boosting ensemble model.

---

## 🎯 Project Overview

Preterm birth (< 37 weeks gestation) is a leading cause of neonatal morbidity worldwide. Traditional clinical diagnostics lack the sensitivity to predict preterm birth early enough for preventive intervention. This project applies supervised ML on metabolomics profiles (small molecule biomarkers from biological samples) to build a high-accuracy early-warning model.

### Key Results

| Metric | Value |
|--------|-------|
| Model | Gradient Boosting (scikit-learn) |
| Accuracy | **97%** |
| Dataset | Metabolomics biomarker profiles |
| Task | Binary classification (preterm vs. term) |

---

## 🧠 Methodology

1. **Data Preprocessing** — handling missing values, normalization, outlier detection on metabolomics CSV data
2. **Feature Engineering** — variance thresholding, correlation analysis, selecting top biomarkers
3. **Model Training** — Gradient Boosting Classifier with hyperparameter tuning via GridSearchCV
4. **Evaluation** — accuracy, precision, recall, F1-score, ROC-AUC curve analysis
5. **Interpretation** — feature importance ranking to identify key predictive metabolites

---

## 📁 Repository Structure

```
ML-in-metabolomics/
├── Pretermbirth.ipynb        # Full analysis notebook
└── file_name ABB (1).csv     # Metabolomics dataset
```

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/sharvinvarghese/ML-in-metabolomics
cd ML-in-metabolomics

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook Pretermbirth.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.x**
- **scikit-learn** — Gradient Boosting, model evaluation
- **pandas / numpy** — data manipulation
- **matplotlib / seaborn** — visualizations
- **Jupyter Notebook** — analysis environment

---

## 📜 Citation

If you use this work, please cite the IEEE publication:

```bibtex
@article{varghese2023metabolomics,
  title     = {Precision at Its Core: Machine Learning infused Metabolomics Model for Preterm Birth Prediction in Humans},
  author    = {Varghese, Sharvin and others},
  journal   = {IEEE},
  year      = {2023}
}
```

---

## 🤝 Contributing

Contributions, suggestions, and issue reports are welcome. Feel free to open a PR or raise an issue.

---

## 📄 License

MIT © [Sharvin Varghese](https://github.com/sharvinvarghese)
