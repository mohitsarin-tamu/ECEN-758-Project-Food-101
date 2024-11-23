# Food-101 Image Classification using ResNet-50

The Food-101 dataset, a comprehensive collection of 101,000 food images across 101 categories, presents a challenging benchmark for image classification due to its intentionally noisy and mislabeled training data. This study uses the ResNet-50 architecture, a deep convolutional neural network known for its residual learning capability, to classify food images into binary categories: sweet and savory. Extensive preprocessing, including data cleansing, augmentation, and dimensionality reduction using Principal Component Analysis (PCA), was employed to prepare the dataset. In this study, we compared ResNet-50 with other models, such as VGG-16 combined with logistic regression, to understand the performance of different models on our dataset. The ResNet-50 model achieves the highest classification accuracy of 93.36%, showcasing ResNet-50 potential in fine-grained food image classification tasks.

Link to Project WebPage - https://curved-cairnsmore-c18.notion.site/Food-101-Image-Classification-using-ResNet-50-1451d779703e807e8fbae7b0274c4cb3?pvs=4

Link to Pretrained Model Weights: Get the ResNet-50-based model trained on the Food-10 dataset from here: https://drive.google.com/drive/folders/1JxiV60AmDM7gEqmlHOSM7mSvyzq3U8z3 

Link to the Test Data: Obtain the test dataset required for the model from here: https://drive.google.com/drive/folders/1rtnQWkxBWYxcktQa2CoXj6fGXXv94RHx

Instructions To run the code:

1. Copy the main.py into your jupyter notebook or google collab or any other environment which can import all these packages  
  numpy  
  pandas  
  torch  
  torchvision  
  Pillow  
  opencv-python  
  scikit-learn  
  gdown  
 
Or

1. Make sure Python is installed in you system

2. Run this code to download the packages
```
cd Code
pip install -r requirements.txt
```

3. Run the Script

```
python main.py
```


Contributors:
* Mohit Sarin
* Pavan Santosh
* Sharvani Ramineni
* Vinodheni Ramasrinivasan
* Dorian Satuluri
