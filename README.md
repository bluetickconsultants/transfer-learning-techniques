
<h2> What is Transfer learning CNN Techniques? </h2>
<hr>

Transfer-learning techniques are neural networks where trained on 1000 labels dataset called ImageNet. Around 1.4 million images were used to develop CNN architectures. There are roughly 1.2 million training images, 50,000 validation images, and 150,000 testing images. 
<hr>
<img src="/Transfer learning Techniques/images/2.jpeg">
<hr>
<h2> VGG19 </h2>
<hr>
Vgg19 has 24 different layers where 16 convolutional layers and 5 max-pooling layers and 3 fully connected one-dimensional layers and one output layer with a softmax activation function.
<hr>
<img src="/Transfer learning Techniques/images/7.png">
<hr>
<h2> ResNet50 </h2>
<hr>
ResNet50 has 50 different layers where 48 convolutional layers and 1 max-pooling layer and 1 Average pool layer. ResNet architectures are known as Residual networks with deep neural networks. ResNet architectures use a concept known as a skip connection. Using skip connection vanishing gradient problem reduced during the time of backpropagation.
<hr>
<img src="/Transfer learning Techniques/images/8.png">
<hr>
<h2> VGG16 </h2>
<hr>
VGG16  has 21 different layers where 14 convolutional layers 5 max-pooling layers and 3 hidden layers and a softmax activation function at the output layer.
In transfer learning techniques we need to make sure the pre-trained weights should not be changed and we should make flatten layers from our data output itself. There is a padding of 1-pixel done after each convolution layer to prevent the spatial feature of the image.
<hr>
<img src="/Transfer learning Techniques/images/5.png">

<hr>
<h3>
Finally using fine-tuning VGG16, VGG19, and ResNet50 deep learning techniques in terms of extracting information from the data it was observed that VGG16 performed well in classifying covid, Normal, and viral pneumonia. However, excellence in high performance remained besides VGG16 with high precision and model accuracy.
</h3>

