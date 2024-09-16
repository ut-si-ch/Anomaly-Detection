# Anomaly Detection
Compared machine learning models, including Random Forest and LightGBM, to detect cyber anomalies in CPS based systems.
# Data Source
Link to the data source:- https://research.unsw.edu.au/projects/toniot-datasets

# Overview:
This thesis focuses on improving the security and privacy of Cyber-Physical Systems (CPS) by utilizing advanced machine learning (ML) algorithms for anomaly detection. The research leverages various datasets, including TON_IoT, and explores the use of models such as Random Forest, Gradient Boosting, LightGBM, and Generative Adversarial Networks (GANs). The work highlights the critical need for reliable anomaly detection systems to address cybersecurity threats, particularly in critical infrastructure.

# Business Understanding:
CPS, widely used in sectors such as healthcare, smart cities, and industrial control systems, face growing cyber threats. These systems require robust security measures to prevent disruptions that could lead to severe financial losses, safety hazards, or privacy breaches. This research aims to develop effective models that enhance the detection of malicious activities within CPS networks, ultimately improving the resilience and reliability of these systems.

# Dataset Understanding:
The dataset used in the research is the TON_IoT dataset, which includes data from IoT and IIoT environments such as telemetry data from sensors, network traffic, and operating system activities. The dataset is well-suited for cybersecurity applications as it contains both normal and malicious events such as Denial of Service (DoS), Distributed Denial of Service (DDoS), ransomware, and scanning attacks.

# Modeling & Evaluation:
The thesis explores the use of supervised ML algorithms such as Random Forest, XGBoost, and LightGBM, alongside a GAN-based model for anomaly detection. Key steps in the modeling process include data preprocessing, feature selection using the SelectKBest method, and hyperparameter tuning. Each model was evaluated using metrics such as accuracy, precision, recall, and F1-score. LightGBM achieved the highest accuracy of 96.5%, while the GAN-based model had the lowest accuracy at 94.2%. Despite lower accuracy, GANs show potential for improving anomaly detection by generating synthetic data to simulate complex network behaviors.

# Conclusion:
The research demonstrates the effectiveness of ML models in detecting various types of cyberattacks within CPS. Models like LightGBM and XGBoost are shown to be highly effective, while GANs provide promising avenues for future improvements. The thesis concludes by outlining the need for further research to optimize GAN architectures and integrate real-time anomaly detection systems. Additionally, privacy-preserving techniques such as differential privacy and federated learning are recommended to protect sensitive data in CPS environments .


