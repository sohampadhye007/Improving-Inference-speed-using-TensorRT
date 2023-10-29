# Improving-Inference-using-TensorRT
Used TensorRT for improving the the inferencing speed

MNIST dataset is a collection of handwritten digits used for image classification tasks in
machine learning. It is a widely used dataset for training and testing image classification
models. The dataset consists of 70,000 grayscale images of handwritten digits (28x28 pixels).
We are going to use this data for digit classification
I'm using pytorch to implement this task

## Defining custom layers for digit classification and comparing it with ResNet18
ResNet18 is generally a better choice for image classification tasks compared to the custom
CNN layers that I have defined. Especially for larger datasets with complex patterns resnet18 is
good. However, the specific choice between these architectures would depend on the specific
requirements of the task and available resources.
As we can see in the accuracy vs no. Of epoch for both the models is quite similar.
There is no significant change in the accuracy. That’s why the layers that I have defined are well
classifying the digits. But the resnet is very powerful and its accuracy is also good.
