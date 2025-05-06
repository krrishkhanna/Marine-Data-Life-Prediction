

---

# Marine Life Protection — Data Compilation & Analysis

This repository presents a comprehensive analysis of the threats facing marine ecosystems and explores potential solutions through data-driven modeling. The primary objective is to support efforts toward preserving biodiversity and enhancing the effectiveness of Marine Protected Areas (MPAs).

## 🌊 Project Overview

Marine life is under increasing threat from pollution, overfishing, climate change, habitat destruction, and invasive species. This project consolidates various data points and analytical approaches to:

* Define and contextualize the key threats to marine ecosystems.
* Quantify and visualize the impacts of these threats.
* Evaluate the efficacy of MPAs and ecosystem-based management strategies.

## 📂 Contents

* **Data Definitions** — Key terms like biodiversity, ecosystem services, and fishing mortality are clearly outlined.
* **Exploratory Data Analysis** — The dataset is explored to understand distributions, outliers, and correlations.
* **Modeling Approaches** — Machine learning models, including k-Nearest Neighbors (KNN), are used to predict ecosystem outcomes.
* **Model Tuning** — Comparative analysis between different KNN configurations.
* **Interpretation** — Statistical measures such as Kappa scores are used to evaluate model reliability.

## 🧰 Tech Stack

* **Language:** Python 3.12
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
* **Tools:** Jupyter Notebook

## 🔍 Key Insight

A tuned KNN model (k=21) outperforms a baseline model (k=3), suggesting that refined parameter selection enhances predictive accuracy. The low kappa score also highlights challenges in data quality or class imbalance, encouraging further data enrichment.

## 📌 How to Use

1. Clone the repository
2. Open the Jupyter Notebook
3. Follow each section sequentially — from data definitions to model interpretation

## 📢 Contributing

Contributions are welcome! Whether it’s adding more datasets, improving models, or creating visual dashboards, feel free to fork and submit a pull request.

---


