# vision_model
This is a simple neural network model based on tensorflow and data augmentation.

The  goal here is to detect 3 classes from the images but the input dataset is very small close to 100 images per class (although can be used for larger datasets)
and thats why I am using data augmentation to increase the size of the training and validation sets. The input images are stored on a single folder and this is split 
in 2 folders for training and validation.

The neural model itself  is a sequential model with convolutional layers followed by batchnorm and maxpool layers each.

The model achieves in training a good accuracy but not so good in validation which means its overfitining. The most basic solution to this is to increase
the size of the input dataset but other approaches can be helpful too!
