# Dissertation\_2025

This repository contains the research work for my M.Sc. Data Science dissertation:

**“Investigating the influence of Age, Bodyweight and Strength metrics on athletic powerlifting performance”**
(Goa University, 2025)

The study applies regression-based statistical modeling (Ordinary Least Squares and Generalized Additive Models) to analyze how demographic and physiological variables affect powerlifting outcomes, using the **OpenPowerlifting** dataset.

---

## 📂 Repository Structure

### Data (`/data`)

* **raw/** – Original dataset(s) collected
* **preprocess/** – Intermediate datasets created during cleaning and transformation
* **final/** – Final dataset used for modeling (`dataset.csv`)

### Notebooks (`/Notebooks`)

* **preprocess/** – Data preparation steps

  * `DataCleaning.ipynb`
  * `DataTransform.ipynb`

* **modeling/** – Model development

  * `Fitted_models.ipynb` (final results and outputs)

* **analysis/** – Supporting work, experiments, and comparisons

  * `Analysis.ipynb`
  * `comparison.ipynb`
  * `Accuracy_40.ipynb`
  * `Models.ipynb`

---

## 📑 Dissertation Mapping

* **Chapter 3: Methodology** → `Notebooks/preprocess/` + `data/preprocess/`
* **Chapter 4: Results** → `Notebooks/modeling/Fitted_models.ipynb` + `data/final/dataset.csv`
* **Chapter 5: Discussion** → `Notebooks/analysis/`

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Main libraries:

* pandas, numpy
* matplotlib, seaborn
* statsmodels
* pyGAM
* scikit-learn
* jupyter

---

## 📌 Notes

* The **final results** in the dissertation are based on `data/final/dataset.csv` and `Notebooks/modeling/Fitted_models.ipynb`.
* Other datasets and notebooks are included to demonstrate the **full workflow** and for supervision/reproducibility.
* Large raw files are excluded from this repo. Please refer to [OpenPowerlifting](https://www.openpowerlifting.org) for original datasets.

---