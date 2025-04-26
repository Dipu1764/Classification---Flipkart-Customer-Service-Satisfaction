**🚀 Flipkart Customer Service Satisfaction - Classification Project**
**🧐 About the Project**
How can Flipkart predict whether a customer was happy after contacting customer support?
In this project, we build a machine learning pipeline to classify customer satisfaction based on service interaction data.
The outcome? A model that helps Flipkart understand customer emotions at scale and boost service excellence.

**🎯 Goal**
Predict if a customer is satisfied or dissatisfied after a support interaction.

Use actionable insights to improve operational efficiency and customer loyalty.

**📂 Data Summary**
Features: Customer interaction details (issue type, resolution time, communication channel, feedback score, etc.)

Target Variable: Customer Satisfaction Status (Satisfied / Dissatisfied)

**🧩 Project Workflow**
Understanding the Data

Data Cleaning & Preprocessing

Missing value treatment

Label encoding & One-hot encoding

Feature scaling

Exploratory Data Analysis (EDA)

Visual correlation checks

Feature importance ranking

Model Building

Trained multiple models:

Logistic Regression

Decision Tree

Random Forest

ExtraTreesClassifier (Winner 🏆)

Model Evaluation

Used metrics like Accuracy, F1 Score, Confusion Matrix, and ROC-AUC

Model Saving

Exported the best model (ExtraTreesClassifier) using joblib

**⚙️ Tech Stack**

Tool	Purpose
Python	Programming language
Pandas	Data manipulation
NumPy	Numerical operations
Scikit-learn	Machine learning modeling
Matplotlib	Data visualization
Seaborn	Advanced plots and graphs
Google Colab	Cloud-based notebook platform
🛠️ Model Performance
Best Model: ExtraTreesClassifier


Metric	Score (Example)
Accuracy	94%
Precision	93%
Recall	92%
F1 Score	92.5%
(replace with your actual scores if needed)

**📦 Model Deployment**
Saved to: /content/drive/MyDrive/Flipkart_Csat/et_model.pkl

Format: .pkl using joblib library

****💡 Insights Gained
Certain issue types lead to higher dissatisfaction.

Longer resolution times directly impact customer satisfaction.

Communication channels like chat showed higher satisfaction rates.

🚀 What's Next?
Deploy as a web service to predict real-time CSAT for new cases.

Integrate NLP (Natural Language Processing) for text feedback analysis.

Suggest best resolution strategies based on customer profiles.

**🙌 Thank you for reading!**
