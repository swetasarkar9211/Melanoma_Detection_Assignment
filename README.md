## PROJECT NAME

### MELANOMA DETECTION ASSIGNMENT

__To build a CNN based model which can accurately detect melanoma.__<br>

## PROBLEM STATEMENT :
- __Melanoma__ is a type of cancer that can be deadly if not detected early. 
- It accounts for __75%__ of skin cancer deaths. 
- A solution which can evaluate images and alert the dermatologists about the __presence of melanoma__ has the potential to __reduce a lot of manual effort__ needed in diagnosis.
- The dataset consists of __2357 images of malignant and benign oncological diseases__, which were formed from the International Skin Imaging Collaboration __(ISIC)__. 
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.<br>

#### The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions

### Model 1 : 
- __Overfitting__ spotted and hence data augmentation is used in second model to overcome this issue.

### Model 2 : 
- Overfitting issue is resolved to some extent but still there is a scope for improvement in accuracy. Hence class imbalance issue is observed and resolved using __Augmentor__.

### Model 3 :
- Class imbalance issue is resolved and the accuracy of the model is improved.

## Libraries Used

- pandas 
- numpy
- matplotlib.pyplot
- seaborn 
- keras
- tensorflow
