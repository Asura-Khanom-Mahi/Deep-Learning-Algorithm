# Deep-Learning-Algorithm Melanoma Classification
Melanoma classification using deep learning models with data splitting and preprocessing.

This project implements deep learning models for binary melanoma classification using image preprocessing and data splitting. Models are trained with transfer learning on pretrained backbones, followed by custom classification layers.

- Loaded images from folders and split them into 80% training and 20% validation
- Applied basic image preprocessing rescaling, flipping, shifting 
- Used pretrained models like InceptionV3, ResNet50, VGG16, and MobileNet
- Froze the base layers and added custom dense layers for classification
- Trained using Adam optimizer and categorical crossentropy loss
- Evaluated using confusion matrix and AUC curve
