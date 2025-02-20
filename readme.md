# 🌟 ParkerNet: A Deep Learning Tool for Switchback Classification in Parker Solar Probe Data 🚀

## 🔥 Project Highlights  
Switchbacks—**abrupt disturbances or reversals in the radial magnetic field of the solar wind**—have been extensively studied since NASA’s **Parker Solar Probe (PSP)** mission. These disturbances could hold the key to understanding how the **solar wind is heated and accelerated**. 🌞💨  

In this project, we introduce **ParkerNet**—a **Deep Learning model** designed to classify switchbacks in **PSP data** for the first time!  

✅ **Trained on PSP FIELDS and SWEAP (SPC) instrument measurements obtained from publicly available data on CDAweb**.  
✅ **Quickly classifies switchbacks** in PSP data.  
✅ **ParkerNet Version 1.0** is introduced here.

---  

## 📂 What's Included in the Main folder ParkerNetVersion01?  
This repository contains **three** subfolders containing *three* Jupyter Notebooks, each serving a specific function:  

### 📂 ParkerNet_Training: Subfolder containing Jupyter Notebook needed for training ParkerNet
📜 **ParkerNet_Version1_Training_ApJ_Notebook1of3.ipynb**  
🔹 **Train ParkerNet** with different **seeds** and **train-validation splits**.    
  
## ⚙️ Run **ParkerNet_Version1_Training_ApJ_Notebook1of3** in Google Colab  
### 📌 Notebook 1: Training ParkerNet  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_Training/ParkerNet_Version1_Training_ApJ_Notebook1of3.ipynb)  

### 📂 ParkerNet_Ensemble_Prediction: Subfolder containing Jupyter notebook needed to perform ensemble prediction on new (prediction) datasets.
📜 **ParkerNet_Version1_Ensemble_Prediction_APJ_Notebook2of3.ipynb**  
🔹 Computes **ensemble (weighted average) predictions** from **71 pre-trained ParkerNet models**.  
🔹 Includes **datasets for prediction**, or use your own data!  

## ⚙️ Run **Ensemble_Prediction_APJ_Notebook2of3** in Google Colab
### 📌 Notebook 2: Ensemble Prediction  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_Ensemble_Prediction/ParkerNet_Version1_Ensemble_Prediction_APJ_Notebook2of3.ipynb) 

### 📂 ParkerNet_ApJ_Figures: Data Visualization & Figures  
📜 **ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3.ipynb**  
🔹 Reproduce figures from the research paper:  
📖 *"An Iterative, Deep Learning Approach for Switchback Classification in Parker Solar Probe Data"* 📊 
🔹 Includes **datasets needed to recreate figures**. 

## ⚙️ Run **ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3** in Google Colab
### 📌 Notebook 3:ApJ Figures  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_ApJ_Figures/ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3.ipynb)


📜 **Notes for user:** 
✅ **All required files for these notebooks are included in the project’s subfolders.** 
✅ **ParkerNet Version 1.0**is our base model, we have future improvements planned, including adding **explainable AI** and upgraded capabilities. 🚀 


👏 **We hope you enjoy learning about ParkerNet and find it useful!  🌟 Stay tuned for more cool ParkerNet updates and switchback science!** 🚀🌞  
