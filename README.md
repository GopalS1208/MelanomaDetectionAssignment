# MelanomaDetectionAssignment

## Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. Usecase is to build a solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset:
Dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. 

Below are the diseases
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Solutions:
Melanoma Detection Skin Care ISIC.ipynb - Contains 3 Models along with Augumentor for 500 samples as part of Class imbalancing
Melanoma Detection Skin Care ISIC_Aug_1000_Images.ipynb - Contains same 3 Models along with Augumentor for 1000 samples as part of Class imbalancing. Observations are mentioned in the comments after each model execution.