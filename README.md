# Medical-Image-Segmentation-Deep-Learning-Project
In this deep learning project, we will implement Unet++ models for medical image segmentation to detect and classify colorectal polyps.

**Project Description**

**Business Objective**

Machine learning and deep learning technologies are increasing at a fast pace with respect to the domain of healthcare and medical sciences. These technologies sometimes even out perform medical doctors by producing results that might not be easily notable to a human eye. Polyp recognition and segmentation is one such technology which helps doctors identify polyps from colonoscopic images.

 

 

**Data Overview**

CVC-Clinic database consists of frames extracted from colonoscopy videos. The dataset contains several examples of polyp frames & corresponding ground truth for them.

The Ground Truth image consists of a mask corresponding to the region covered by the polyp in the image.  The data is available in both .png and .tiff formats

 

 

**Aim**

To segment the polyps from colonoscopy images

 

 

**Tech Stack**

Language used : Python

Deep learning library used : Pytorch

Computer vision library used : OpenCV

Other python libraries :  Scikit-learn, pandas, numpy, albumentations etc.

 

 

**Approach**

1. Data Understanding :
Understanding the essence of the dataset

2. Understanding evaluation metrics:
Understanding the metrics that are going to be used for evaluating the predictions

3. Unet Architecture :
Understanding Unet architecture and why is it preferred widely in building deep learning models with respect to medical sciences.

4. Unet ++ :
Understanding Unet++ and how is it different from Unet

5. Environment Setup :
Setting up a working environment for the project

6. Data Augmentation :
Creating new data by making modifications on the existing data

7. Model building :
Building Unet ++ model using pytorch

8. Model Training
Training the model. ( A GPU might be required since model training takes a really long time in CPUs)

9. Model Prediction
