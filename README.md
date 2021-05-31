# Cancer-Detection-using-CNN

To build a multiclass classification model using a custom convolutional neural network in tensorflow for detecting Melonoma Skin Cancer. 

 ## Problem statement: 
 To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


You can download the dataset here https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view


The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

Tasks Performed:
1. Data Reading/Data Understanding 

2. Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32 and also resize images to 180*180.

3. Dataset visualisation → To visualize one instance of all the nine classes present in the dataset 

4. Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser and loss function for model training
Choose an appropriate data augmentation strategy to resolve underfitting/overfitting 

5. Model Building & training on the augmented data : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
Choose an appropriate optimiser, data augmentation strategy and loss function for model training


 
