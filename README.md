# Transfer-Learning-for-Image-Classification
In this project, we build a classifier that distinguishes images of 20 bird species. When dealing with classification of relatively small image datasets, deep networks may not perform very well because of not having enough data to train them. In such cases, one usually uses transfer learning, which uses deep learning models that are trained on very large datasets such as ImageNet as feature extractors.
In this project, pre-trained models EfficientNetB0 and VGG16 are used.
To perform empirical regularization, crop, randomly zoo, rotate, flip, contrast, and translate images in the training set for image augmentation.
Use ReLU activation functions in the last layer and a softmax layer, along with batch normalization and a dropout rate of 20% as well as ADAM optimizer. Use multinomial cross entropy loss.
