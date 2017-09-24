# Semantic Segmentation

In this project, I have labelled the pixels of a road in images using a Fully Convolutional Network (FCN). 
I've used the VGG-16 model and trained the model to learn the correct features from the images. 
I have replaced fully connected layers with the 1x1 convolutional layers then added up-sampling by using transposed convolutional layers and 
implemented the skip-layer architecture to get better segmenatation results. I have tuned hyperparameters to optimize the neural network model. 
I have set the number of epochs to 100, batch sizes to 5 and low learning rate 1e-4.
While training the model,I have observed decreased loss over time. Once the model built,the classifier has done a pretty good job identifying road pixels. 
it has generated inference images on Kitti Road dataset with correct label.

![a01](./runs/a01.png)

![a1](./runs/a1.png)

![a2](./runs/a2.png)

![a03](./runs/a03.png)

![a3](./runs/a3.png)

![a4](./runs/a4.png)

![a5](./runs/a5.png)

![a7](./runs/a7.png)

![a8](./runs/a8.png)

Image : The loss decreased during training - 


![trainingLoss](./networkTraining.png)


 
