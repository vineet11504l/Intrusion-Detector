# Cyber Intrusion Detection using Machine Learning Techniques

This repository contains an implementation of a project aimed at detecting cyber intrusions in network traffic, specifically focusing on port scan data. The project explores the use of machine learning techniques to identify and predict malicious activities based on refined feature vectors derived from unstructured textual data. Conducted as a supervised research initiative from February to April 2024, the project showcases the application of multiple methodologies for intrusion detection and analysis.

The data preprocessing phase involved cleaning and structuring raw network port scan data to extract meaningful features. **Regular expressions (RegEx)** were utilized to identify patterns such as IP addresses and protocol details, while **tokenization** helped split textual data into manageable components. Advanced feature extraction techniques like **Bag of Words (BoW)** and **Term Frequency-Inverse Document Frequency (TF-IDF)** were employed to numerically represent the textual data.

To classify and detect intrusions, three machine learning algorithms—**K-Nearest Neighbors (KNN)**, **Random Forest**, and **Naive Bayes**—were implemented and fine-tuned. The Random Forest model achieved the highest accuracy of **90%**, effectively identifying malicious activities in the dataset.

Additionally, **Hidden Markov Models (HMMs)** were utilized to analyze temporal patterns in network traffic, enabling the identification and prediction of high-probability attack sequences. This aspect of the project contributed to a deeper understanding of network attack dynamics and their probabilistic behavior.

The implementation leveraged Python programming and libraries such as **Scikit-learn**, **Pandas**, and **hmmlearn** for data processing, modeling, and analysis. The outcomes of this project highlight the potential of machine learning techniques in enhancing cyber security measures through precise and proactive intrusion detection.

For further exploration, the project sets the groundwork for integrating real-time detection systems, experimenting with deep learning models, and refining feature engineering to incorporate additional network parameters. Conducted under expert supervision, this work represents a significant step toward automated and intelligent network security solutions.
