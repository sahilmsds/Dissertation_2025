# Dissertation\_2025

This repository contains the research work for my M.Sc. Data Science dissertation:

**“Investigating the influence of Age, Bodyweight and Strength metrics on athletic powerlifting performance”**
(Goa University, 2025)

The study applies regression-based statistical modeling (Ordinary Least Squares and Generalized Additive Models) to analyze how demographic and physiological variables affect powerlifting outcomes, using the **OpenPowerlifting** dataset.

---

🎯 Why this research matters

This research is important because it bridges data science with sports performance in a transparent and practical way:

Sports relevance – Coaches and athletes gain interpretable insights into how age, bodyweight, and strength metrics influence outcomes, helping to design better training strategies.

Explainable models – Unlike black-box machine learning, the OLS and GAM models provide clear, interpretable results that practitioners can trust.

Transferable methodology – The same workflow (data cleaning → preprocessing → regression modeling → evaluation) applies beyond powerlifting, in areas like healthcare, fitness apps, and athlete scouting.

Evidence-based decisions – Results highlight which factors matter most (e.g., bodyweight and squat performance), supporting data-driven planning for performance improvement.

This makes the project relevant not only for academic research but also for companies in sports analytics, fitness technology, and health data science.

---


## 📂 Repository Structure

### Data (`/data`)
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
* Other notebooks are included to demonstrate the **full workflow** and for supervision/reproducibility.
* Large raw files are excluded from this repo. Please refer to [OpenPowerlifting](https://www.openpowerlifting.org) for original datasets.

---