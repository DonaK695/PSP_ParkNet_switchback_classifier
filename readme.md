# 🌟 ParkerNet: A Deep Learning Tool for Switchback Classification in Parker Solar Probe Data 🚀

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14902722.svg)](https://doi.org/10.5281/zenodo.14902722)

## 🔥 Project Highlights  
Switchbacks—**abrupt disturbances or reversals in the radial magnetic field of the solar wind**—have been extensively studied since NASA’s **Parker Solar Probe (PSP)** mission. These disturbances could hold the key to understanding how the **solar wind is heated and accelerated**. 🌞💨  

In this project, we introduce **ParkerNet**—a **Deep Learning model** designed to classify switchbacks in **PSP data** for the first time!  

✅ **Trained on PSP FIELDS and SWEAP (SPC) instrument measurements obtained from publicly available data on CDAweb**.  
✅ **Quickly classifies switchbacks** in PSP data.  
✅ **ParkerNet Version 1.0** is introduced here.

---  

### 📂 What's Included in the Main folder ParkerNetVersion01?  
This repository contains **three** subfolders containing **three** Jupyter Notebooks, and accompanying datasets. The subfolders contain the following:  

- 📂 ParkerNet_Training: Subfolder containing Jupyter Notebook needed for training ParkerNet
	📜 **ParkerNet_Version1_Training_ApJ_Notebook1of3.ipynb**  
	🔹 **Train ParkerNet** with different **seeds** and **train-validation splits**. 
	🔹 Contains a file for optional evaluation. 

*Note: A large file needed to run Notebook 1 is archived on Zenodo. See "Instructions for using Notebook1" below.*



- 📂 ParkerNet_Ensemble_Prediction: Subfolder containing Jupyter notebook needed to perform ensemble prediction on new (prediction) datasets.
	📜 **ParkerNet_Version1_Ensemble_Prediction_APJ_Notebook2of3.ipynb**  
	🔹 Computes **ensemble (weighted average) predictions** from **71 pre-trained ParkerNet models**.  
	🔹 Includes **datasets for prediction**, or use your own data! 

*Note: A large file needed to run Notebook 2 is archived on Zenodo. See "Instructions for using Notebook1" below.*


- 📂 ParkerNet_ApJ_Figures: Data Visualization & Figures  
	📜 **ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3.ipynb**  
	🔹 Reproduce figures from the research paper:  
		📖 *"An Iterative, Deep Learning Approach for Switchback Classification in Parker Solar Probe Data"* 📊 
	🔹 Includes **datasets needed to recreate figures**.  


**General Instructions**

- To run in Colab, upload the files from this repo to your Google drive and then mount your drive. You should be able to run the notebooks as they are.  
- To run on your local machine, download this repo, create a virtual environment,  install all the packages you need from the provided requirements.txt file, and run the notebook in a Jupyter environment or you can obtain the Python and Jupyter extensions for VS code.  

*Note : you will have to adjust the data loading code but that's about it (provide path to your folder containing the repo files). The notebooks contain detailed instructions and will also tell you what files are needed.*


**📌 Instructions for using Notebook 1:**
You will need to obtain the training data file "PSP_E1toE7_July23_nonoise.txt" from [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14902750.svg)](https://doi.org/10.5281/zenodo.14902750)   

⚙️ To Open **ParkerNet_Version1_Training_ApJ_Notebook1of3** in Google Colab, click here :[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_Training/ParkerNet_Version1_Training_ApJ_Notebook1of3.ipynb)


**📌 Instructions for using Notebook 2:** 
You will need to obtain the training data file "PSP_E1toE7_July23_nonoise.txt" from [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14902750.svg)](https://doi.org/10.5281/zenodo.14902750) 

⚙️To open **Ensemble_Prediction_APJ_Notebook2of3** in Colab, click here: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_Ensemble_Prediction/ParkerNet_Version1_Ensemble_Prediction_APJ_Notebook2of3.ipynb) 


**📌 Instruction for using Notebook 3:** 
⚙️To open **ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3** in Google Colab, click here: [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DonaK695/PSP_ParkerNet_Switchback_classifier/blob/main/ParkerNetVersion01/ParkerNet_ApJ_Figures/ParkerNet_Version1_DataViz_Figures_APJ_Notebook3of3.ipynb)


📜 **Notes for user:** 

✅ **ParkerNet Version 1.0**is our base model, we have future improvements planned, including adding **explainable AI** and upgraded capabilities. 🚀 


👏 **We hope you enjoy learning about ParkerNet and find it useful!  🌟 Stay tuned for more cool ParkerNet updates and switchback science!** 🚀🌞  
