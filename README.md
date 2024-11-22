# Food-101 Image Classification using ResNet-50

The Food-101 dataset, a comprehensive collection of 101,000 food images across 101 categories, presents a challenging benchmark for image classification due to its intentionally noisy and mislabeled training data. This study leverages the ResNet-50 architecture, a deep convolutional neural network known for its residual learning capability, to classify food images into binary categories: sweet and savory. Extensive preprocessing, including
data cleansing, augmentation, and dimensionality reduction using Principal Component Analysis (PCA), was employed to prepare the dataset. Our experiments compared ResNet-50 with other models, such as VGG-16 combined with logistic regression, to highlight performance trade-offs. Preliminary results indicate that ResNet-50 achieves superior classification accuracy, show-casing its potential in fine-grained food image classification tasks.

Link to Project WebPage - https://curved-cairnsmore-c18.notion.site/Food-101-Image-Classification-using-ResNet-50-1451d779703e807e8fbae7b0274c4cb3?pvs=4

Link to Model-Weight and Test-data: https://drive.google.com/drive/folders/1Gn5K8lwGtu9XWGrAS14G_FbE4whWbW2o


Instructions to run the main.py:

1. Download the Pretrained Model: Get the ResNet-50-based model trained on the Food-10 dataset from here: https://drive.google.com/drive/folders/1Gn5K8lwGtu9XWGrAS14G_FbE4whWbW2o
2. Download the Test Data: Obtain the test dataset required for the model from here: https://drive.google.com/drive/folders/1Gn5K8lwGtu9XWGrAS14G_FbE4whWbW2o
3. Add Custom Test Data: If you want to add your custom test data, ensure the data directory follows the same format as the test dataset above.
4. Output of the Classification Model: The model will classify the input image as either containing a sweet dish or a savory dish.

For more information about unning the code, please feel free to reach out to our team.
