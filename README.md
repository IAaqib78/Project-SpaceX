<!-- =========================================================== -->
<!--  IBM Data Science Capstone: SpaceX Falcon 9 Landing Prediction -->
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

##  Tech Stack

| Domain | Tools |
|:--|:--|
| **Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Folium, Plotly Dash |
| **Environment** | Jupyter Notebook, IBM Watson Studio |
| **Data Sources** | SpaceX REST API, Web Scraping (Wikipedia) |

---
---

 

The SpaceX Launch Success Prediction project leveraged a combination of **data engineering, visualization, and machine learning tools** to deliver robust predictive insights.

<p align="center">
  <!-- Python & Data Science -->
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=FFD43B" alt="Python" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-FF5733?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn" />
</p>

<p align="center">
  <!-- ML & Modeling -->
  <img src="https://img.shields.io/badge/Scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/Logistic_Regression-00ffc6?style=for-the-badge&logoColor=black" alt="Logistic Regression" />
  <img src="https://img.shields.io/badge/SVM-ff00ff?style=for-the-badge&logoColor=white" alt="SVM" />
  <img src="https://img.shields.io/badge/Decision_Tree-00fff7?style=for-the-badge&logoColor=black" alt="Decision Tree" />
  <img src="https://img.shields.io/badge/KNN-ff00ff?style=for-the-badge&logoColor=white" alt="KNN" />
</p>

<p align="center">
  <!-- Dashboards & Visualization -->
  <img src="https://img.shields.io/badge/Plotly-3F4CFF?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly" />
  <img src="https://img.shields.io/badge/Folium-1DC9C9?style=for-the-badge&logoColor=white" alt="Folium" />
  <img src="https://img.shields.io/badge/Jupyter-FF4300?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
</p>

<p align="center">
  <!-- Others / Version Control -->
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=F05032" alt="Git" />
</p>


---




## 🧮 Core Algorithms

```python
#  Falcon 9 Landing Prediction Core
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.tree import DecisionTreeClassifier
from sklearn.svm import SVC
from sklearn.neighbors import KNeighborsClassifier

#  Model Evaluation
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




 


**Visual Insights**



 High success rates observed for launches after 2018, correlating with iterative model improvements.

 Launch site and booster version were the strongest predictive features.

 Reusability models directly tied to SpaceX’s cost reduction strategy.

 **Key Takeaways**


Data analytics plays a strategic role in aerospace economics.

Machine learning provides predictive reliability for reusability planning.

Visualization enhances interpretability — bridging science and story.





---

## 📊 Dashboard & Insights

Explore the key visualizations derived from SpaceX launch data. These dashboards summarize payload outcomes, launch site trends, and overall mission success probability.  

### Payload Outcome Dashboard (0–16,000 kg)
<p align="center">
  <img src="images/payload_outcome_dashboard_0_16000.png" alt="Payload Outcome 0-16000" width="80%" style="border-radius:10px; box-shadow:0 0 20px #00fff7;" />
</p>
*Insight:* Higher payload mass from Kennedy launch site correlates with higher probability of mission success.  

### SpaceX Launch Success Dashboard
<p align="center">
  <img src="images/spacex_launch_success_dashboard.png" alt="SpaceX Launch Success Dashboard" width="80%" style="border-radius:10px; box-shadow:0 0 20px #ff00ff;" />
</p>
*Insight:* LEO missions demonstrate the highest success rates, while Polar orbits show more variability.  

### Payload Outcome Dashboard (0–8,000 kg)
<p align="center">
  <img src="images/payload_outcome_dashboard_0_8000.png" alt="Payload Outcome 0-8000" width="80%" style="border-radius:10px; box-shadow:0 0 20px #00fff7;" />
</p>
*Insight:* Low payload launches indicate marginal success probability; careful planning improves outcomes.  







🧑‍🚀 Author
<h3 align="center" style="color:#00E5FF;">👨‍🚀 Aakif Altaf</h3> <p align="center"> <b>Data Scientist | AI Innovator | IBM & Google Certified</b><br> BCA | MCA | Data Science (IBM) | Data Analytics (Google)<br> <i>"Machines see data — I teach them to understand meaning."</i> </p>





 




<h3>  Future Enhancements</h3>

Incorporate real-time telemetry streaming.

Apply Neural Networks for complex nonlinear prediction.

Integrate weather & orbital parameters for richer features.

Deploy the dashboard as a cloud-hosted AI service.




<h2 align="center" style="color:#00ffc6;"> A Data-Driven Leap Toward Space Intelligence</h2> <p align="center"> <img src="https://cdn.dribbble.com/users/926537/screenshots/4502924/space_illustration.gif" width="60%" style="border-radius:12px; box-shadow:0 0 25px #00ffc6;"> </p>
<p align="center" style="font-size:14px; color:#8B949E;"> ⭐ If you found this project inspiring — don’t forget to star the repository and share it with fellow space enthusiasts! </p> 






---

## 🎥 Final Presentation

<h4 align="center">|| Click Below ||</h4>

<p align="center">
  <a href="SpaceX_Launch_Success_Prediction_Presentation.pdf" target="_blank">
    <img src="https://img.shields.io/badge/📊_View_Final_Presentation-00fff7?style=for-the-badge&logo=microsoftpowerpoint&logoColor=ff5c00&labelColor=0D1117" alt="View Presentation" />
  </a>
</p>



*This presentation summarizes the full technical workflow — from data collection and EDA to model building, evaluation, and insights — as developed for the IBM Data Science Capstone Project.*
---
