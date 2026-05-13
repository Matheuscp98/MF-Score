# 📊 MF-Score Datasets Repository

## 🧠 MF-Score: Model-Agnostic Feature Selection without Model Training

This repository contains a curated collection of **30 classification datasets** used to evaluate the proposed **MF-Score methodology**, a model-agnostic criterion for feature subset evaluation in Machine Learning classification problems.

MF-Score quantifies **multivariate class separability prior to classifier training** by integrating classical **MANOVA statistics** into a single latent index through **Principal Component Factor Analysis (PCFA)**.

The methodology was designed to provide:

- Efficient feature subset evaluation
- Reduced computational cost
- Classifier-independent analysis
- Robust performance across heterogeneous datasets

---

# 🚀 Overview

The MF-Score framework combines:

- **Multivariate Analysis of Variance (MANOVA)**
- **Principal Component Factor Analysis (PCFA)**
- **Design of Experiments (DOE)**

to evaluate feature subsets **before model training**, enabling scalable and computationally efficient Feature Selection (FS).

The methodology was validated across:

- 📂 **30 datasets**
- 🤖 **8 Machine Learning classifiers**
- 📊 Multiple predictive metrics

Experimental results indicated:

- Strong alignment between **MF-Score and predictive performance**
- Competitive classification performance
- Lower computational cost compared to traditional FS methods
- Robustness across different domains and model families

---

# ⚙️ Methodological Pipeline

The MF-Score framework is composed of six sequential stages:

1. Data preprocessing and standardization  
2. Latent variable extraction using PCFA with Varimax rotation  
3. Structured subset exploration using DOE  
4. MANOVA-based multivariate separability analysis  
5. MF-Score computation through latent-factor aggregation  
6. Statistical and predictive validation  

---

# ✨ Main Characteristics

- ✅ Model-agnostic
- ✅ Multivariate
- ✅ Computationally efficient
- ✅ Pre-modeling feature evaluation
- ✅ DOE-driven subset exploration
- ✅ Scalable to high-dimensional datasets
- ✅ Independent of downstream classifiers

---

# 🤖 Model Validation

The predictive utility of the selected subsets was validated using:

- Logistic Regression (LR)
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree (DT)
- Random Forest (RF)
- Gradient Boosting (GB)
- eXtreme Gradient Boosting (XGB)

## Evaluation Metrics

- Accuracy
- Precision
- F1-score
- LogLoss

All experiments were conducted using **stratified 5-fold cross-validation**.

---

# 📂 Repository Structure

- 📁 [`data/`](data/)
  - [`acoustic_extinguisher_fire.csv`](data/acoustic_extinguisher_fire.csv)
  - [`alzheimers_disease.csv`](data/alzheimers_disease.csv)
  - [`apple_quality.csv`](data/apple_quality.csv)
  - [`brain_tumor.csv`](data/brain_tumor.csv)
  - [`breast_cancer_wisconsin.csv`](data/breast_cancer_wisconsin.csv)
  - [`cancer.csv`](data/cancer.csv)
  - [`cardiovascular_disease.csv`](data/cardiovascular_disease.csv)
  - [`date_fruit.csv`](data/date_fruit.csv)
  - [`diabetes.csv`](data/diabetes.csv)
  - [`dry_bean.csv`](data/dry_bean.csv)
  - [`fetal_health_classification.csv`](data/fetal_health_classification.csv)
  - [`glass_identification.csv`](data/glass_identification.csv)
  - [`heart_failure_prediction.csv`](data/heart_failure_prediction.csv)
  - [`image_segmentation.csv`](data/image_segmentation.csv)
  - [`ionosphere.csv`](data/ionosphere.csv)
  - [`magic_gamma_telescope.csv`](data/magic_gamma_telescope.csv)
  - [`mice_protein_expression.csv`](data/mice_protein_expression.csv)
  - [`palm_fruit_vision_features.csv`](data/palm_fruit_vision_features.csv)
  - [`pen_based_recognition_of_handwritten_digits.csv`](data/pen_based_recognition_of_handwritten_digits.csv)
  - [`pepper.csv`](data/pepper.csv)
  - [`pistachio_image_features.csv`](data/pistachio_image_features.csv)
  - [`pumpkin_seeds.csv`](data/pumpkin_seeds.csv)
  - [`raisin.csv`](data/raisin.csv)
  - [`rice_msc.csv`](data/rice_msc.csv)
  - [`sonar_mines_rocks.csv`](data/sonar_mines_rocks.csv)
  - [`tool_materials.csv`](data/tool_materials.csv)
  - [`vehicle_silhouettes.csv`](data/vehicle_silhouettes.csv)
  - [`weather_classification.csv`](data/weather_classification.csv)
  - [`wine_quality_red.csv`](data/wine_quality_red.csv)
  - [`wine_quality_white.csv`](data/wine_quality_white.csv)

- 📁 [`scripts/`](scripts/)
  - [`preprocessing/`](scripts/preprocessing/)
  - [`validation/`](scripts/validation/)
  - [`examples/`](scripts/examples/)

- 📄 [`.gitattributes`](.gitattributes)
- 📄 [`.gitignore`](.gitignore)
- 📄 [`LICENSE`](LICENSE)
- 📄 [`README.md`](README.md)

---

# 📚 Publications

This repository is part of the research study:

> *Manuscript currently under peer review*

---

# 📊 Datasets

The repository includes 30 heterogeneous classification datasets covering multiple domains and complexity levels.

The datasets vary significantly in:

- 📌 Number of features
- 📌 Number of samples
- 📌 Number of classes
- 📌 Dimensionality complexity

Examples include:

- Small and low-dimensional datasets
- Large-scale datasets with tens of thousands of instances
- High-dimensional datasets with 100+ features

This diversity enables robust benchmarking of:

- Feature Selection methods
- Machine Learning models
- Multivariate statistical methodologies

All datasets are available in `.csv` format inside the `/data` directory.

---

# 🛠️ Main Libraries

The methodology and experiments rely on:

- `numpy`
- `pandas`
- `scipy`
- `scikit-learn`
- `statsmodels`
- `factor_analyzer`
- `pyDOE2`
- `xgboost`
- `matplotlib`

---

# ▶️ How to Use

## Clone the repository

```bash
git clone https://github.com/your-username/MF-Score-Datasets.git
cd MF-Score-Datasets
```

## Load datasets in Python

```python
import pandas as pd

df = pd.read_csv("data/wine_quality_red.csv")

print(df.head())
```

The datasets can be used for:

- Feature Selection (FS)
- Machine Learning (ML)
- Statistical analysis
- Benchmarking studies
- Validation of multivariate methodologies

---

# 📬 Contact

<a href="mailto:matheusc_pereira@hotmail.com">
  <img src="https://i.ibb.co/k6Ddn36k/email.png" alt="E-mail" height="60"/>
</a>

<a href="https://www.linkedin.com/in/matheuscostapereira/">
  <img src="https://i.ibb.co/Kx4rZxdr/linkedin.png" alt="LinkedIn" height="60"/>
</a>

<a href="https://scholar.google.com.br/citations?user=1iDBIzYAAAAJ&hl=en-us">
  <img src="https://i.ibb.co/SwsRKK1t/scholar.png" alt="Google Scholar" height="60"/>
</a>

<a href="https://lattes.cnpq.br/7025666927284220">
  <img src="https://i.ibb.co/1fMjS38j/lattes.png" alt="Lattes" height="60"/>
</a>

---

> Feel free to open issues or pull requests, or contact me for collaborations and research discussions.
