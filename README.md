# 📊 Multiple Correspondence Analysis (MCA) on Categorical Data

This project applies **Multiple Correspondence Analysis (MCA)** to summarize and visualize a dataset where individuals are described by **qualitative (categorical) variables**.

---

## 🎯 Objectives

- Explore similarities between individuals based on their categorical profiles.
- Identify and visualize **associations between variable modalities**.
- Reduce the complexity of multidimensional qualitative data.
- Detect **latent patterns** and **individual profiles** across multiple variables.

---

## 🧪 Dataset

- **Type**: Survey or observation data with categorical variables
- **Format**: Individuals × qualitative variables
- **Goal**: Explore associations and profiles

---

## 🧭 Analysis Workflow

### 1. 🗂️ Data Preparation
- Encode categorical variables as factors
- Handle missing or rare modalities

### 2. 🔎 Applying MCA
- Perform Multiple Correspondence Analysis using `FactoMineR`
- Extract eigenvalues, inertia, and principal dimensions

### 3. 📈 Visualizations
- Plot individuals and modalities on the first two dimensions
- Color by groups or clusters if applicable
- Highlight strong associations and proximity between points

### 4. 🧠 Interpretation
- Identify groups of similar individuals (profiles)
- Detect clusters of associated categories (modalities)
- Understand the structure and dimensionality of the data

---

## 🛠️ Tools & Libraries

- `R`
- `FactoMineR`, `factoextra`, `tidyverse`
- (Optional) `ggplot2` for custom visualizations


