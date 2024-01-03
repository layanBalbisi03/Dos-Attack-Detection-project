# Dos-Attack-Detection-project

# Abstract
The utilization of Wireless Sensor Networks (WSN) and their prevalence expose these networks to a multitude of security threats. To counteract these threats, it becomes imperative to employ a robust Intrusion Detection System (IDS). The identification of these attacks poses a significant challenge, particularly in the context of detecting Denial of Service (DoS) attacks.
This project provides a comprehensive empirical study aims at examining several Ensemble learning using a new specialized, published dataset for WSN networks (named as WSN-DS). The purpose is to provide an efficient IDS for detecting critical Denial of Service (DoS) attacks, which have a serious impact on the services provided by WSNs.
In this repository, we share the code and data for reproducability.

# setup 
Although each foundation model has its own configuration steps, we provide you with a universal configuration as follows:

Python version: 3.8.17.
GPU: NVIDIA or use Google colab.
All code is available in [DosDetection_FullCode.ipynb](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/blob/main/DosDetection_FullCode.ipynb) , just Run it.

# Models
This project focused on Dos attack detection, a diverse array of 11 distinct machine learning models was employed. These models served as the cornerstone of approach, aimed at identifying and mitigating potential Dos attacks within network traffic data. The utilization of these models was pivotal in fortifying our defense mechanisms against the evolving landscape of cyber threats.

For simplicity, we provide Jupyter notebooks containing codes for the Dos attack detection inside [models](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/blob/main/Models/Models.ipynb) directory

![Blank diagram](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/assets/103776716/9c5c5a42-149e-489f-910f-893fbe324b7a)


# Datasets & Preprocessing
Datasets (WSN) and their sampling variations (undersampled) can be found inside the [Data](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/blob/main/Data/WSN-DS.zip)
 directory. You can also find the preprocessing code for Class Rebalancing (undersampling) and scaling in [data_preprocessing.ipynb](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/blob/main/Data/Data_Preprocessing.ipynb)

# Ensemble Learning
Ensembling Learning leverages multiple base models to achieve better predictive performance, which is often better than any of the constituent models alone. It has been proven critical in many practical applications and data science competitions applications. 
You can find the Ensemble model code for ( stacking Classifier, Fixed Weighted, Voting, Learnable Weighted) in [Ensemble_learning.ipynb](https://github.com/layanBalbisi03/Dos-Attack-Detection-project/blob/main/Ensemble%20learning/Ensemble_Learning.ipynb)

# Contact Us
If you encounter any issues and need assistance, please sumbit an issue on this GitHub repository, or contact us via
- bsr0189040@ju.edu.jo
- lya0215423@ju.edu.jo
- mry0216884@ju.edu.jo
- zyn0218080@ju.edu.jo
- Lyn0219463@ju.edu.jo
  
Thank you for your interest in reproducing the results!


