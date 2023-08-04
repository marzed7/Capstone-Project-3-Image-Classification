# Capstone Project 3: Image Classification of Cracked Concrete Detection
- The project aims to develop an image classification model to distinguish between concrete images with and without cracks using deep learning techniques, including binary image classification and transfer learning with MobileNetV2 architecture.

## Introduction
- Cracks in concrete structures can indicate potential structural problems, and early detection is crucial for maintenance and safety. This project focuses on automating the detection of cracks in concrete images using deep learning techniques. Two main approaches are explored: binary image classification and transfer learning using the MobileNetV2 architecture.

## Dataset
- The dataset used for this project consists of concrete images, both with and without cracks. The dataset can be obtained from [https://data.mendeley.com/datasets/5y9wdsg2zt/2]. It is organized into two classes: 'Negative' and 'Positive'. The 'Negative' indicates concrete image without crack, while 'Positive' indicates concrete image with cracks.

## Files For Script
- `imgclass.ipynb`: Jupyter Notebook containing the code for the binary image classification approach. This approach involves training a custom deep learning model to classify cracked and uncracked concrete images.
- `imgclass_transferlearning.ipynb`: Jupyter Notebook containing the code for the transfer learning approach. MobileNetV2 pre-trained on ImageNet is fine-tuned on the concrete crack dataset to leverage transfer learning benefits.

## Model Architecture
- The architecture of the deep learning model used for binary image classification is as follows:
- 1. Model architecture for 'imgclass.ipynb':
     ![image](https://github.com/marzed7/Capstone-Project-3-Image-Classification/assets/141207242/c358b486-66ca-46b9-bf9e-29195c4ee3b7)


- 2. Model architecture for 'imgclass_transferlearning.ipynb':
     ![image](https://github.com/marzed7/Capstone-Project-3-Image-Classification/assets/141207242/8b2b6911-aa2a-48ff-a904-a6d7ee87ceb6)

## Acknowledgements
- We would like to acknowledge the following resources that were instrumental in the completion of this project:
- - Source of Concrete Crack Dataset: [https://data.mendeley.com/public-files/datasets/5y9wdsg2zt/files/8a70d8a5-bce9-4291-bab9-b48cfb3e87c3/file_downloaded]
  - MobileNetV2 architecture pre-trained on ImageNet
    
Feel free to contribute, open issues, or provide feedback to help improve this project. Happy classifying!
