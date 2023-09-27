# Transfer-Learning-for-Image-Classification
In this project, we build a classifier that distinguishes images of 20 bird species. When dealing with classification of relatively small image datasets, deep networks may not perform very well because of not having enough data to train them. In such cases, one usually uses transfer learning, which uses deep learning models that are trained on very large datasets such as ImageNet as feature extractors.
In this project, pre-trained models EfficientNetB0 and VGG16 are used.
Preprocessed data by splitting the dataset, resizing images, applying one-hot encoding to class labels, and augmenting training images for empirical regularization.
To perform empirical regularization, crop, randomly zoo, rotate, flip, contrast, and translate images in the training set for image augmentation.
Used pre-trained models EfficientNetB0 and VGG16 as feature extractors, applied global average pooling, used batch normalization and a dropout rate of 20%, followed by the last fully connected layer with ReLU activation functions and a softmax layer.
Trained the networks for 100 epochs using Adam optimizer to minimize cross-entropy loss. Performed early stopping based on the validation set. Achieved a micro F1 score of 0.93 for EfficientNetB0 and 0.94 for VGG16.
