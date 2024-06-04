Melanoma Skin Cancer Detection with Convolutional Neural Network
The aim of this project is to develop a Convolutional Neural Network (CNN) model that can accurately detect melanoma, a severe form of skin cancer responsible for 75% of skin cancer-related deaths. Early detection of melanoma can significantly increase survival rates. This model can assist dermatologists by automatically evaluating images and identifying potential melanoma cases, thereby reducing the manual effort required for diagnosis.

Table of Contents
General Information
Conclusions
Acknowledgements
Contact
General Information
Dataset: The dataset consists of 2357 images of both malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). The images are categorized based on ISIC classifications. The dataset includes an equal number of images per category, except for melanoma and moles, which are slightly overrepresented.
Categories: The dataset covers the following conditions:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
Conclusions
Custom Models: Three custom CNN models were built and evaluated. No pre-trained models were used.
Image Processing: Images were resized to 180x180 pixels and a batch size of 32 was used during training.
Model Performance:
Model 1: Exhibited overfitting, with high training accuracy but low validation accuracy.
Model 2: Exhibited underfitting, with low accuracy due to potential data imbalance.
Model 3: Showed promising results, achieving good accuracy and validation accuracy. Data augmentation was performed using the Augmentor library to address the data imbalance issue.
Acknowledgements
I would like to extend my gratitude to Upgrad and IIIT Bangalore for providing the opportunity to work on this project.

Contact
Created by @pendyalajoel
