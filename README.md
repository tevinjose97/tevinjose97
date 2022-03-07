
## Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

Familiar with: ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python)
![Java](https://img.shields.io/badge/-java-E34A86?style=flat-square&logo=java)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql)
![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)
![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=flat-square&logo=gitlab)

# Machine Learning Portfolio

## [Project: CyberThreat Hunting using ML](https://github.com/tevinjose97/Machine-Learning-Projects/tree/main/CyberThreat-Hunting_using_ML)
* Cyber threat hunting assumes organizations are compromised and proactively looks for advanced threats that have evaded existing security solutions.
* Built an **interactive threat hunting tool** using **Python** to help threat hunters **train models** using **custom labeled threat datasets** and **predict unlabelled datasets, to detect and classify threats/ anomalies**.
* The Model Pipeline is as follows:
   1. **Loading and Splitting the Dataset**
   2. **Data Preprocessing**
   3. **Feature Selection**
   4. **Resampling (Undersampling and Oversampling)**
   5. **Model Training and Hyperparameter Tuning (GridSearchCV)**
   6. **Performance Analysis**
* The project tries to leverage the benefits of **Supervised** and **Unsupervised** methods by combining them. The **Catboost Classifier** and **Isolation Forest** models were used in an ensemble so that the Catboost model can handle known threats while the Isolation Forest can handle unknown anomalies.
* The tool employs a web user interface using Python's **Streamlit** library.
* To infer data at a glance, the tool provides **visualisations** such as **pie charts, color-coded predictions,** and **frequency plots** of the predictions .
* The performance of the machine learning models was evaluated using performance metrics like **Accuracy, Precision, Recall** and **F1-Score**.

<p align="center">
  <img src="/Images/threat_anomaly_pred_ui.png" width="400" />
  <img src="/Images/predictions_table.png" width="400" />
</p>

<p align="center">
  <img src="/Images/unsw_piechart.png" width="400" /> 
  <img src="/Images/unsw_feat_threat_results.png" width="400" />
</p>

## [Project: Insurance Claim Prediction (Vehicle Characteristics)](https://github.com/tevinjose97/Machine-Learning-Projects/tree/main/Insurance_Claim_Prediction_(Vehicle-Characteristics))
* Predictive model that uses **vehicle characteristics** to accurately **predict insurance claim payments**
* Explore the dataset
* Splitting dataset into **Train, Test** and **Validation** sets
* Custom function to handle **categorical** and **ordinal** values (based on pattern)
* Handle the **mising** values and **imbalanced** dataset (**cluster centroids**)
* Experiment with **Tandem model** combining the **binary classifier** and **regressor**, due to the high amount of zero claims
* Regressor Models: **Linear, Ridge, Random Forest** and **Gradient Boosting**
* Classification Models: **Random Forest** and **Gradient Boosting**
* **GridSearchCV** for **tuning the model hyperparameters** and obtaining the optimal model


<p align="center">
  <img src="/Images/Claims_Histogram.PNG" width="600" />
</p>
