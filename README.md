# ⚠️ Disclaimer  

**This repository contains harmful or violence-related medical images, collected from the public Fitzpatrick17k dataset.**  
If you are not comfortable or feel uneasy, please refrain from opening any notebook or image-related files.  

---

# Fitzpatrick17k Skin Disease Classification  

This repository contains the code and resources for our research on the Fitzpatrick17k dataset, focusing on skin disease classification. The work explores individual model performance, preprocessing methods, and the use of explainable AI (XAI) for better model interpretability.  

---

## Repository Structure  

### 1. **Notebooks/Individual_Models_TABLE_III**  
Contains experiments on individual deep learning models used in our research:  
- `InceptionResNetV2.ipynb`: Experiment using the InceptionResNetV2 model.  
- `InceptionV3.ipynb`: Experiment using the InceptionV3 model.  
- `MobileNetV2.ipynb`: Experiment using the MobileNetV2 model.  
- `NASNetLarge.ipynb`: Experiment using the NASNetLarge model.  
- `ResNet50.ipynb`: Experiment using the ResNet50 model.  
- `VGG19.ipynb`: Experiment using the VGG19 model.  
- `Xception.ipynb`: Experiment using the Xception model.  

### 2. **Notebooks/Individual_SkinType_TABLE_IV**  
Contains experiments focusing on individual skin types and their impact on classification:  
- `CAEN_Experiment_On_Each_SkinType.ipynb`: Evaluates model performance on each skin type using the CAEN approach.  
- `Individually_SkinTone_Raw.ipynb`: Raw analysis of individual skin tones.

### 3. **Notebooks**  
Contains experiments focusing on individual skin types and their impact on classification:
- `Basic_Base_Lighter_Mid_Darker.ipynb`: Analysis based on lighter, mid-tone, and darker skin tones.  
- `CAEN_Lighter_Mid_Darker.ipynb`: Advanced analysis of lighter, mid-tone, and darker skin tones using CAEN. 

### 3. **Notebooks**  
Explores the classification performance across different skin tone categories:  
- `Basic_Base_Lighter_Mid_Darker.ipynb`: Baseline analysis of classification across lighter, mid-tone, and darker skin tones.  
- `CAEN_Lighter_Mid_Darker.ipynb`: In-depth analysis of lighter, mid-tone, and darker skin tones using the CAEN framework.  


### 4. **Notebooks/Preprocessing**  
Scripts for preprocessing the Fitzpatrick17k dataset:  
- `Data_Pre_Processing_v1.ipynb`: Initial preprocessing methods applied to the dataset.  
- `Data_Pre_Processing_v2_Final.ipynb`: Finalized preprocessing pipeline for the dataset.  

### 5. **Notebooks/XAI**  
Contains explainable AI (XAI) visualizations to interpret model predictions:  
- `XAI_Fitz17K.ipynb`: Grad-CAM visualizations for explaining model predictions.  

---

## Usage  
1. **Preprocessing**: Start with the preprocessing notebooks to prepare the dataset.  
2. **Model Training**: Use the individual model notebooks or skin type-specific experiments for training and evaluation.  
3. **Explainable AI**: Generate visual explanations using the XAI notebook.  

---

## Archive

- [Medrxiv (Archive)](https://medrxiv.org/cgi/content/short/2024.12.11.24318858v1)
