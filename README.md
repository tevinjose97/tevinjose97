
## ⚡ Technologies

![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![Nodejs](https://img.shields.io/badge/-Nodejs-black?style=flat-square&logo=Node.js)
![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=Python)
![React](https://img.shields.io/badge/-React-black?style=flat-square&logo=react)
![Java](https://img.shields.io/badge/-java-E34A86?style=flat-square&logo=java)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C?style=flat-square&logo=bootstrap)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript)
![MongoDB](https://img.shields.io/badge/-MongoDB-black?style=flat-square&logo=mongodb)
![Redis](https://img.shields.io/badge/-Redis-black?style=flat-square&logo=Redis)
![ElasticSearch](https://img.shields.io/badge/-ElasticSearch-005571?style=flat-square&logo=elasticsearch)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql)
![Apollo GraphQL](https://img.shields.io/badge/-Apollo%20GraphQL-311C87?style=flat-square&logo=apollo-graphql)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql)
![MySQL](https://img.shields.io/badge/-MySQL-black?style=flat-square&logo=mysql)
![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku)
![Docker](https://img.shields.io/badge/-Docker-black?style=flat-square&logo=docker)
![DigitalOcean](https://img.shields.io/badge/-Digital%20Ocean-darkblue?style=flat-square&logo=digitalocean)
![Amazon AWS](https://img.shields.io/badge/Amazon%20AWS-232F3E?style=flat-square&logo=amazon-aws)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-232F7E?style=flat-square&logo=microsoft-azure)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-black?style=flat-square&logo=google-cloud)
![Git](https://img.shields.io/badge/-Git-black?style=flat-square&logo=git)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)
![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=flat-square&logo=gitlab)
![BitBucket](https://img.shields.io/badge/-BitBucket-darkblue?style=flat-square&logo=bitbucket)
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-C51A4A?style=flat-square&logo=Raspberry-Pi)

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
