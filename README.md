# BreastCancer-SemanticSegmantation
<div align="justify">
  Breast cancer ranks among the leading causes of death in women worldwide. Early and precise detection plays a vital role in enhancing treatment outcomes.
</div>

    
<!-- ![image](resources/pot.jpg) -->
<div align="center">
  <img src="./Resources/malignant (1).png" alt="Image 1" height="200" style="margin-right: 10px;">
  <img src="./Resources/malignant (10).png" alt="Image 2" height="200" style="margin: 0 10px;">
  <img src="./Resources/malignant (100).png" alt="Image 3" height="200" style="margin-left: 10px;">
</div>

<p align="center">
  Some samples from patients.
</p>  

<div align="justify">
  In recent years, deep learning-based semantic segmentation has demonstrated remarkable potential in medical image analysis, especially in accurately outlining cancer boundaries in ultrasound images.
</div>  
<div align="justify">
  Therefore, we suggest some methods can deal with those tasks by comparing six semantic segmentation models—UNet, PSPNet, DeepLabV3+, TransUNet, Swin-Unet, and SegFormer—using two benchmark datasets: BUSI and BUS-WHU.
</div>  
<div align="justify">
  You can read full version of reference through
  <a href="https://easychair.org/conferences2/submission_download?a=34672663&submission=7283684&upload=151756">Paper</a>.
</div>  

### How semantics segmentation deals with those problems
<div align="justify">
  Breast cancer is currently one of the most life-threatening cancers diagnosed and continues to rise in prevalence worldwide.
</div>  
<div align="justify">
  Early detection plays a crucial role in reducing mortality and improving patient outcomes (Crosby et al., 2022). With advancements in artificial intelligence (AI), semantic segmentation has become a promising technique for breast cancer detection
</div>  
<div align="justify">
  A wide range of semantic segmentation models, particularly those based on deep learning, have been introduced (Hu et al., 2020).
</div>  
<div align="justify">
  However, most of these models were originally developed for general object detection tasks—such as identifying vehicles or animals—and have seen limited application in the context of breast cancer.
</div>  
<div align="justify">
  To address this gap, this study aims to evaluate and analyze the performance of deep learning-based semantic segmentation models on breast cancer datasets, with the goal of identifying the most effective architecture for accurate detection.
</div>  
   
<div align="justify">
  In this subsection, we use two different datasets of breast ultrasound images to evaluate semantic segmentation models,
namely the Breast Ultrasound Images (BUSI) and the Breast Cancer Ultrasound Image (BUSI_WHU).
</div>  
<div align="justify">
  Both of those datasets are published and dowloaded through <a href="https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset">Breast Ultrasound Images (BUSI)</a> and <a href="https://data.mendeley.com/datasets/k6cpmwybk3/1">Breast Cancer Ultrasound Image (BUSI_WHU)</a>.
</div>  

### Experimental results  
<div align="justify">
  Deep Learning-Based Semantic Segmentation models can be classified into two main types: CNN-based methods (Unet, PSPNet, DeeplabV3+) and Transformer-based models (TransUnet, SwinUnet,and Segformer)
</div>  
To obtain the results of all models on both datasets, we utilized Kaggle as the computing platform.  

Notebooks use Breast Ultrasound Images (BUSI) dataset (Those notebook may not have equal results compared to our reference because of different runs):

Unet: [Notebook]()  

PSPNet: [Notebook]()  

DeepLabV3+: [Notebook]()  

Segformer: [Notebook]()  
 
SwinUnet: [Notebook]()  

TransUnet: [Notebook]()  
You can see our detection score of compared semantic segmentation models on the Potholes-Detection dataset:
| Method       | Accuracy (%) | mIoU (%) | Dice (%) |
|--------------|--------------|----------|-----------|
| Unet         | 87.46        | 82.00    | 89.54     |
| PSPNet       | 85.45        | 79.90    | 88.08     |
| DeepLabV3+   | 87.28        | 81.79    | 89.40     |
| SegFormer    | 87.52        | 82.45    | 89.85     |
| TransUnet    | 88.00        | 86.73    | 85.60     |
| SwinUnet     | 86.44        | 87.15    | 96.89     |


Notebooks use Breast Cancer Ultrasound Image (BUSI_WHU) Dataset (Those notebook may not have equal results compared to our reference because of different runs) :

Unet: [Notebook]()  

PSPNet: [Notebook]()  

DeepLabV3+: [Notebook]()  

Segformer: [Notebook]()  
 
SwinUnet: [Notebook]()  

TransUnet: [Notebook]()  
You can see our detection score of compared semantic segmentation models on the Potholes-Detection dataset:
| Method       | Accuracy (%) | mIoU (%) | Dice (%) |
|--------------|--------------|----------|-----------|
| Unet         | 87.46        | 82.00    | 89.54     |
| PSPNet       | 85.45        | 79.90    | 88.08     |
| DeepLabV3+   | 87.28        | 81.79    | 89.40     |
| SegFormer    | 87.52        | 82.45    | 89.85     |
| TransUnet    | 88.00        | 86.73    | 85.60     |
| SwinUnet     | 86.44        | 87.15    | 96.89     |
