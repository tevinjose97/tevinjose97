# Machine Learning Portfolio

## Project 1: CyberThreat Detecting using ML
* Cyber threat hunting assumes organizations are compromised and proactively looks for advanced threats that have evaded existing security solutions.
* Built an interactive threat hunting tool using Python to help threat hunters train models using custom labeled threat datasets and predict unlabelled datasets, to detect and classify threats/ anomalies.
* The Model Pipeline is as follows: 
   1. Loading and Splitting the Dataset
   2. Data Preprocessing
   3. Feature Selection
   4. Resampling (Undersampling and Oversampling)
   5. Model Training and Tuning
   6. Performance Analysis
* The project tries to leverage the benefits of Supervised and Unsupervised methods by combining them. The Catboost Classifier and Isolation Forest models were used in an ensemble so that the Catboost model can handle known threats while the Isolation Forest can handle unknown anomalies.
* The tool employs a web user interface using Python's Streamlit library. The tool also provides visualizations (pie chart, color-coded predictions, frequency plots) of the predictions to infer data at a glance.
* The performance of the machine learning models was evaluated using performance metrics like Accuracy, Precision, Recall and F1-Score.

<!--
**tevinjose97/tevinjose97** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
