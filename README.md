<!-- =========================================================== -->
<!-- 🚀 IBM Data Science Capstone: SpaceX Falcon 9 Landing Prediction -->
<!-- Enhanced Professional README -->
<!-- =========================================================== -->

<h1 align="center" style="font-family:'Segoe UI',sans-serif; color:#00E5FF;">
🌌 SpaceX Falcon 9 First Stage Landing Prediction
</h1>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/SpaceX_Falcon_9_logo.svg" width="180" alt="SpaceX Falcon 9 Logo">
</p>

<p align="center">
  <b style="color:#00FFC6;">A Data-Driven AI Framework to Predict Falcon 9 Reusability</b><br>
  <i>Developed by Aakif Altaf — Data Scientist | IBM Certified | Google Certified Analyst</i>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Python-0D1117?style=for-the-badge&logo=python&logoColor=00E5FF&labelColor=0D1117&color=00FFC6">
  <img src="https://img.shields.io/badge/Powered%20by-Machine%20Learning-0D1117?style=for-the-badge&logo=scikitlearn&logoColor=00E5FF&labelColor=0D1117&color=00FFC6">
  <img src="https://img.shields.io/badge/License-MIT-0D1117?style=for-the-badge&logo=opensourceinitiative&logoColor=00E5FF&labelColor=0D1117&color=00FFC6">
</p>

---

## 🌠 Overview

Predicting the successful landing of a **SpaceX Falcon 9 first stage** is more than a machine learning challenge — it’s an exploration of how data intelligence can reduce costs and optimize rocket reusability.

This project combines **real launch telemetry**, **API-sourced data**, and **machine learning pipelines** to forecast mission outcomes — providing insight into how **SpaceX revolutionized space economics**.

---

## 🧩 Tech Stack

| Domain | Tools |
|:--|:--|
| **Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Folium, Plotly Dash |
| **Environment** | Jupyter Notebook, IBM Watson Studio |
| **Data Sources** | SpaceX REST API, Web Scraping (Wikipedia) |

---

## 🧮 Core Algorithms

```python
# 🚀 Falcon 9 Landing Prediction Core
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.svm import SVC
from sklearn.neighbors import KNeighborsClassifier

# 🧠 Model Evaluation
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report

```


| Model               | Accuracy | Notes                      |
| :------------------ | :------: | :------------------------- |
| Logistic Regression |    83%   | Baseline Model             |
| Decision Tree       |    88%   | Best overall performer     |
| SVM                 |    85%   | Margin-based classifier    |
| KNN                 |    86%   | Strong under optimized k=3 |



<p align="center"> <img src="https://cdn.dribbble.com/users/1615584/screenshots/14318150/media/0f7b80a6db36f545a4273cf6b8b723f9.gif" width="85%"> </p>


| Phase                   | Description                                                                                 |
| :---------------------- | :------------------------------------------------------------------------------------------ |
| **1️⃣ Data Collection** | Fetched launch data using SpaceX REST API and scraped Wikipedia for additional attributes.  |
| **2️⃣ Data Cleaning**   | Preprocessed missing data, handled categorical encoding, and refined features for training. |
| **3️⃣ EDA**             | Visualized launch success trends using Matplotlib, Seaborn, and Correlation Heatmaps.       |
| **4️⃣ Mapping**         | Created **Folium-based interactive maps** showing launch site success patterns.             |
| **5️⃣ Model Training**  | Applied Logistic Regression, Decision Tree, KNN, and SVM models.                            |
| **6️⃣ Dashboard**       | Built an **interactive Plotly Dash dashboard** for user exploration and visualization.      |




Interactive Map Preview
<p align="center"> <img src="https://media.giphy.com/media/hu9ZzVx6pYV0k/giphy.gif" width="80%" style="border-radius:15px; box-shadow:0 0 20px #00ffc6;"> </p> <p align="center"> <i>Folium visualization of global SpaceX launch sites, color-coded by success probability.</i> </p>


**Visual Insights**



📈 High success rates observed for launches after 2018, correlating with iterative model improvements.

🛰️ Launch site and booster version were the strongest predictive features.

💸 Reusability models directly tied to SpaceX’s cost reduction strategy.

💡 Key Takeaways

Data analytics plays a strategic role in aerospace economics.

Machine learning provides predictive reliability for reusability planning.

Visualization enhances interpretability — bridging science and story.
