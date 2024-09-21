# 3D-SMART-FACTORY-PFA-2024
## Description
This repository contains two 3D segmentation models: 3DUnet and 3DUnetKAN, developed for brain tissue segmentation using Kolmogorov-Arnold Network (KAN) and U-Net technologies. These models were designed to enhance segmentation accuracy by leveraging advanced deep learning architectures during my internship at 3D-SMART-FACTORY.
<h1 align='center'>UNetKAN</h1>

### This is a warehouse for UNetKAN-Pytorch-model, can be used to train your IRM-image-dataset for segmentation tasks.

### [KAN: Kolmogorov–Arnold Networks](https://arxiv.org/abs/2404.19756)  

![image](https://github.com/CUHK-AIM-Group/U-KAN/blob/main/assets/framework-1.jpg)  

### Download Dataset
[3DBrainTissueSegmentation](https://www.kaggle.com/datasets/soroush361/3dbraintissuesegmentation/data)  

## Project Structure
```
├── 3DSPFA
    ├── data: Load datasets
        ├── train
        ├── test
    ├── Model: Unet & UNetKAN Model
        ├── IRM_Preprocesing_basic_model.ipynb: Construct UNet model
        ├── Unet_With_KANLayers.ipynb: Construct UNetKAN  model
    ├── requirement.txt
├── README.md
├── LICENSE
