# Polyp-Segmentation
# Polyp Segmentation using U-Net (Kvasir-SEG Dataset)

This repository contains an implementation of **polyp segmentation** using a **U-Net architecture** trained on the **Kvasir-SEG** dataset. The objective is to accurately segment gastrointestinal polyps from colonoscopy images to support early detection and clinical analysis.

## 🚀 Overview
- Built a U-Net model tailored for medical image segmentation.
- Trained and tested on the Kvasir-SEG dataset (1000 annotated polyp images).
- Includes preprocessing, training, evaluation, and visualization.
- Evaluated using Dice Score and IoU.
- 
## 🧠 Model Architecture
The U-Net consists of an encoder–decoder design with skip connections to preserve spatial features.  
Key components:
- Downsampling via convolution + max pooling  
- Upampling via transposed convolutions  
- Skip connections for feature fusion  
- Final sigmoid activation for binary segmentation  

## 🧪 Dataset: Kvasir-SEG
- 1000 annotated polyp images  
- High-quality mask annotations  
- Image sizes vary between **332×487 to 1920×1072**  
- Public dataset by Simula Research Laboratory  
- Download: https://datasets.simula.no/kvasir-seg/
