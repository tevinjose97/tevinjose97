
# Technologies

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

![Apache Spark](https://a11ybadges.com/badge?logo=apachespark)
![Streamlit](https://a11ybadges.com/badge?logo=streamlit)

### Familiar with:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

# Machine Learning Portfolio

## [Project: CyberThreat Hunting using ML](https://github.com/tevinjose97/Machine-Learning-Projects/tree/main/CyberThreat-Hunting_using_ML)
* Cyber threat hunting assumes organizations are compromised and proactively looks for advanced threats that have evaded existing security solutions.
* Built an **interactive threat hunting tool** using **Python** to help threat hunters **train predictive models** using **custom labeled threat datasets**, to detect and classify threats/ anomalies**.
* The Model Pipeline is as follows:
   1. **Loading and Splitting the Dataset**
   2. **Data Preprocessing**
   3. **Feature Selection**
   4. **Resampling (Undersampling and Oversampling)**
   5. **Model Training and Hyperparameter Tuning (GridSearchCV)**
   6. **Performance Analysis**
* The **Catboost Classifier** and **Isolation Forest** models were used in an ensemble so that the Catboost model can handle known threats while the Isolation Forest can handle unknown anomalies.
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
