# 3D-SMART-FACTORY-PFA-2024
## Description

Ce dépôt contient deux modèles de segmentation 3D : 3DUnet et 3DUnetKAN, développés pour la segmentation des tissus cérébraux en utilisant des réseaux de type Kolmogorov-Arnold (KAN) et les technologies U-Net. Ces modèles ont été conçus pour améliorer la précision de la segmentation en tirant parti des architectures avancées en apprentissage profond.
<h1 align='center'>UNetKAN</h1>

### This is a warehouse for UNetKAN-Pytorch-model, can be used to train your IRM-image-dataset for segmentation tasks.

### [KAN: Kolmogorov–Arnold Networks](https://arxiv.org/abs/2404.19756)  

![image](https://github.com/CUHK-AIM-Group/U-KAN/blob/main/assets/framework-1.jpg)  

### Download Dataset
[3DBrainTissueSegmentation](https://www.kaggle.com/datasets/soroush361/3dbraintissuesegmentation/data)  

## Project Structure
```
├── datasets: Load datasets
    ├── train
    ├── test
├── models: UNetKAN Model
    ├── IRM_Preprocesing_basic_model.ipynb: Construct UNet model
    ├── Unet_With_KANLayers.ipynb: Construct UNetKAN  model
├── requirement.txt

