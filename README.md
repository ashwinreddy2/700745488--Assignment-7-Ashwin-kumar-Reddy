# 700745488--Assignment-7-Ashwin-kumar-Reddy


Here is the video link which states the description
https://drive.google.com/file/d/1qGjDHrD6oHrcBl6hhThz9DDTN8ZD0nI-/view?usp=sharing


1. Follow the instruction below and then report how the performance changed.(apply all at once)
• Convolutional input layer, 32 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer, 32 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Convolutional layer, 128 feature maps with a size of 3×3 and a rectifier activation function.
• Dropout layer at 20%.
• Convolutional layer,128 feature maps with a size of 3×3 and a rectifier activation function.
• Max Pool layer with size 2×2.
• Flatten layer.
• Dropout layer at 20%.
• Fully connected layer with 1024 units and a rectifier activation function.
• Dropout layer at 20%.
• Fully connected layer with 512 units and a rectifier activation function.
• Dropout layer at 20%.
• Fully connected output layer with 10 units and a Softmax activation function
Did the performance change?
2. Predict the first 4 images of the test data using the above model. Then, compare with the actual label for those 4
images to check whether or not the model has predicted correctly.
3. Visualize Loss and Accuracy using the history object

A) Here in this program we are using keras datasets which help in providing proper data for preparing the models according to the requirement, importing cifar10 which are set of images that can be used to teach a computer how to recognize the objects, and we use constraints module which allows setting constraints on model parameters, additionaly we are importing maxnorm which has a axis argument, along which the norm is calculated and also we are importing Convo2D is used which is a 2 dimensional pattern responsible for generating the kernel of convolution, Maxpooling2D is also imported which calculates the largest or maximum value in every patch and the feature map and finally np_utils is imported which is used to convert the vector of class to the matrix of binary class. From here we are adding convolutional input shape with 32 feature maps with size 3*3, adding a dropout layer of 0.2, adding a convolutional layer without input shape and adding maxpool layer with size 2*2 and nextly we are adding convolutional layer with 64 feature with size of 3 *3 and a drop out layer of 0.2 and then a max pool layer of size 2*2 and adding again a convolutional layer with 128 feature with a drop out layer of 0.2 and then again a maxpool layer and a flatten layer and next  a dropout layer of 0.2 and fully connected  layer with 1024 units and a dropout layer of 0.2 and again a fully connecetd layer with 512 units and a dropout layer and lastly fully connected output layer with 10 units and a softmax activation function and finding the accuracy of it and next step is to predict the first 4 images of the test data and again comaparing with the actual label for those 4 images and finfing the accuracy. Here we can see there is change in the accuracy and finally visulaizing loss and accuracy using the history object.
