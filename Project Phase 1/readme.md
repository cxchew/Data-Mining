# Project Phase 1: Business Understanding, Exploratory Profiling, and Supervised Classification 📋

## 1. Project Summary
Phase 1 of this data mining project centered on laying the analytical and predictive foundations for examining mental health challenges within the global technology sector. Working in a group alongside Lau Yan Kai and Ng Yu Hin, we explored the open-source *Mental Health in Tech Survey* dataset from Kaggle to predict employee access to mental wellness resource arrays. The phase focused on the following key operational steps:
* **Business and Data Understanding Frameworks:** Diagnosed corporate operational pain points regarding workspace mental healthcare, establishing concrete problem statements to identify hidden indicators that prevent employees from seeking professional care.
* **Exploratory Data Analysis (EDA) & Profiling:** Profiled multi-variable data distributions, managed highly missing survey answers, and engineered targeted data cleaning pipelines to normalize erratic string attributes (such as inconsistent gender inputs).
* **Categorical Data Transposition Staging:** Built mapping arrays to handle sparse columns, converting loose textual choices into clean binary formats ready for mathematical processing.
* **Supervised Classification Modeling Execution:** Developed, trained, and cross-evaluated three diverse machine learning models—Logistic Regression, Decision Trees, and Random Forests—to find structural paths for predicting employee care benefits options (`care_options`).

---

## 2. Evidence and Explanation

<img src="images/Screenshot 2026-06-21 014935.png" width="500" alt="Supervised Classification Pipeline">

*Figure 1: Supervised Model Pipeline Tuning and Classifier Metric Matrices*

* **Data Wrangling Validation:** Standardized erratic survey features down to targeted observation vectors, handling multi-class inputs and generating correlation heatmaps to prevent collinearity distortion across parameters.
* **Classifier Evaluation Mechanics:** Measured performance metrics across all models, as illustrated in **Figure 1**. The Random Forest classifier emerged as the most resilient system, balancing sensitivity and precision boundaries safely to prevent classification errors.

---

## 3. Reflection

### What I Learned
* Moving through data pre-processing steps proved that raw, uncurated survey responses are completely unusable without meticulous cleaning. Standardizing unstructured categorical descriptions showed me how foundational data cleaning is to downstream classification success.
* Comparing predictive workflows across different classifiers gave me practical insights into model trade-offs. While Decision Trees were quick to configure, Random Forests handled complex data splits far more effectively, making them ideal for handling noisy human survey metrics.
