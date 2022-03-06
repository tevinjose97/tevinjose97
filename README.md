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
* Predictive model that uses vehicle characteristics to accurately predict insurance claim payments
* Explore the dataset
* Splitting dataset into **Train, Test** and **Validation** sets
* Custom function to handle **categorical** and **ordinal** values (based on pattern)
* Handle the **mising** values and **imbalanced** dataset (**cluster centroids**)
* Experiment with **Tandem model** combining the **binary classifier** and **regressor**, due to the high amount of zero claims
* Regressor Models: **Linear, Ridge, Random Forest** and **Gradient Boosting**
* Classification Models: **Random Forest** and **Gradient Boosting**
* **GridSearchCV** for **tuning the model hyperparameters** and obtaining the optimal model
