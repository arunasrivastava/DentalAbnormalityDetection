# Dental Abnormality Detection using X-Ray Radiograph Segmentation and Mask Generation
**Authors: Aimon Benfield-Chand, Aruna Srivastava, Yafqa Khan**

* [aimonbc@cs.washington.edu](aimonbc@cs.washington.edu)
* [arunasri@cs.washington.edu](arunasri@cs.washington.edu)
* [yafqak@cs.washington.edu](yafqak@cs.washington.edu)

### 1.0 Abstract
Dental and oral diseases significantly impact global health, necessitating advancements in diagnostic technologies. This paper introduces a novel approach to dental abnormality detection using panoramic X-ray radiograph segmentation and mask generation. Leveraging the Tufts Dental Database, we develop a multi-step method that segments dental radiographs into individual tooth crops and subsequently fine-tunes a segmentation model to generate dental abnormality masks. Our approach integrates a UNET-inspired architecture with Meta's DinoV2 pretrained Vision Transformer (ViT) as the encoder, providing a balance between precise abnormality localization and robust feature extraction. We demonstrate the effectiveness of our method by comparing it against a baseline model, highlighting the qualitative and quantitative differences in abnormality detection.

## 1.1. Motivation
Dental and oral diseases significantly impact global
health, affecting around 35% of the population with un-
treated tooth decay, 11% with severe gum disease, and 2%
experiencing tooth loss [4]. Current diagnostic methods
rely heavily on manual examinations, leading to potential
inconsistencies and discomfort. This study aims to address
these issues by implementing deep learning techniques for
more accurate and efficient dental abnormality detection.

* By segmenting the dental radiographs from the [Tufts Dental Database](https://www.kaggle.com/datasets/deepologylab/tufts-dental-database/data)into individual teeth crops and subsequently training a segmentation model, we generate dental abnormality masks for individual teeth crops [7].
* This method combines tooth segmentation and abnormality detection, aiming to enhance the precision of abnormality localization while developing a model that learns an abstraction of the features defining a dental abnormality.
  ![image](https://github.com/arunasrivastava/DentalAbnormalityDetection/assets/82174933/b0b58a14-2873-45e4-940c-6a5d60819f4c)

## Architecture 
![image](https://github.com/arunasrivastava/DentalAbnormalityDetection/assets/82174933/ba574f81-8406-4a1e-a9c1-927bb1951ac4)

## Results
![image](https://github.com/arunasrivastava/DentalAbnormalityDetection/assets/82174933/8cb26007-7f79-401a-ad82-49136ef64e2b)



