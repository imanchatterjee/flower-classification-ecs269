# flower-classification-ecs269

Tutorials for pytorch

Deep Learning with PyTorch: A 60 Minute Blitz
How to setup PyTorch Code Base
mnist pytorch example, for 0.4 - mnist database
http://www.vision.caltech.edu/visipedia/CUB-200-2011.html CUB database
http://www.robots.ox.ac.uk/~vgg/data/flowers/102/ Oxford 102 dataset
We will be performing fine grain classification on biological datasets using the following techniques: AlexNet, Faster RCNN, Resnet, Inception and Inception Resnet

There is a need for preprocessing on the Oxford 102 datset since it is imbalanced so we will rotate, crop and shear the images of minority classes to create new images.

Then we are supposed to split both the datsets into training and test sets.
Experiments:

Comparing upsampled Oxford set with regular Oxford set (hypothesis - more data is better, balanced data is better)
Training only the classifier or the full network (hypothesis - fine tuning the classifier isn't good enough because ImageNet doesn't look at small details)
AlexNet, VGG16/19, Inception, Inception-ResNet, ResNet101
Start working on the report

Freeze layers in your network https://discuss.pytorch.org/t/how-the-pytorch-freeze-network-in-some-layers-only-the-rest-of-the-training/7088/3
