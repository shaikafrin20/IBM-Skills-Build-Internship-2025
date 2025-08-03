# IBM-Skills-Build-Internship-2025
This repository contains all the projects I worked on and certificates I achieved during my 4-weeks Internship at IBM SkillsBuild organised by Edunet Foundation

This internship covered a wide range of topics related to Machine Learning and Artificial Intelligence.<br><br><br>
<img width="925" height="596" alt="image" src="https://github.com/user-attachments/assets/7755029b-e00d-4771-ab82-274c7801903b" />

All the projects were performed on IBM cloud, which gave me an indepth knowledge and practical experience of using IBM cloud for various machine learning and AI tasks

# 🛡️ Network Intrusion Detection Using IBM Cloud ML Services

This project is a capstone implementation of a **Network Intrusion Detection System (NIDS)** using **Machine Learning algorithms**, deployed on **IBM Cloud Machine Learning Services**. The system analyzes network traffic data to detect and classify various types of cyber-attacks and separate them from normal activity.

## 📌 Problem Statement

Cybersecurity threats are on the rise, and early detection of malicious network activity is critical. This project aims to create a robust ML-based system to identify network intrusions such as:

- Denial of Service (DoS)
- Probe attacks
- Remote to Local (R2L)
- User to Root (U2R)

The goal is to provide an early-warning system for malicious activity in communication networks.

## 💡 Proposed Solution

The system follows a typical machine learning pipeline:

- **Data Collection**: Network traffic data with labels for attack/normal activity.
- **Preprocessing**: Cleaning, handling missing values, and feature engineering.
- **Model Training**: A **Decision Tree Classifier** with ensemble learning was used.
- **Evaluation**: Metrics like Accuracy, Precision, Recall, F1-Score were used.
- **Deployment**: Hosted using IBM Cloud's AutoAI ML services.

## 🛠️ System Development

- **Algorithm**: Decision Tree Classifier + Ensemble Learning
- **Training Platform**: IBM Cloud ML Services
- **Input Features**: Protocol types, service type, traffic duration, etc.
- **Output**: Binary classification (Intrusion = 1, Normal = 0)

## 🚀 Deployment

The model is deployed and can be accessed through the following API:

🔗 [IBM Cloud ML Deployment Link](https://eu-gb.ml.cloud.ibm.com/ml/v4/deployments/a1eeb2e4-9788-473d-953c-bce56dc707c1/predictions?version=2021-05-01)

## 📈 Result

The model achieved an impressive accuracy of **99.5%** on test data, making it a highly effective intrusion detection tool.

## 🔮 Future Scope

- Integrate with real-time traffic data for dynamic predictions.
- Use advanced ensemble techniques (e.g., Random Forest, Gradient Boosting).
- Expand model to detect zero-day attacks.
- Enable integration with existing SIEM tools.

## 📂 Dataset

- [Kaggle - Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)

## 📚 References

- [Decision Tree Classifier Paper - IEEE](https://ieeexplore.ieee.org/document/6498972/)
- [ScienceDirect Article on Intrusion Detection](https://www.sciencedirect.com/science/article/pii/S1877050916311127)
- [IBM Cloud AutoAI Documentation](https://www.ibm.com/docs/en/watsonx/saas?topic=solutions-autoai-machine-learning)

