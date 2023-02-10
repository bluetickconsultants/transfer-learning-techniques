
<h1 align="center">Multi-label classification using Transfer Learning techniques </h1>

<hr>

<div align="center">
  <img src="https://user-images.githubusercontent.com/88481845/217153040-9987f17b-f9f0-43af-bc22-d0ed69db360e.jpg">
</div>

<hr>


# What is Transfer learning CNN Techniques? 

Transfer-learning techniques are neural networks where trained on 1000 labels dataset called ImageNet. Around 1.4 million images were used to develop CNN architectures. There are roughly 1.2 million training images, 50,000 validation images, and 150,000 testing images. 

<img src="https://user-images.githubusercontent.com/88481845/217153268-e2b4520b-b9b6-43c5-915d-084dc273c594.jpeg">

## How does Convolutional Neural Network work?

A CNN consists of input layers, hidden layers, pooling layers, fully connected layer, and output layer.
A CNN applies filters layers on the top of the input image to collect the important information carried by the pixels. Filter size can be selected as (3*3) or (5*5). Max pooling layer collects the highest pixel value from each filter we generated. This process will be continued and connected as a one-dimensional array called a fully connected layer. Thus a one-dimensional array can be given input to ANN followed by hidden layers and output layers. 

<img src="https://user-images.githubusercontent.com/88481845/217154432-33dcb019-d693-4953-8ba7-dd0998b322ff.jpg" width="70%" height="70%" >


### VGG19

VGG19 has 24 different layers where 16 convolutional layers and 5 max-pooling layers and 3 fully connected one-dimensional layers and one output layer with a softmax activation function.

<img src="https://user-images.githubusercontent.com/88481845/217153477-7156b778-d138-4acc-abce-2e58ceee5f5c.png">

### ResNet50 

ResNet50 has 50 different layers where 48 convolutional layers and 1 max-pooling layer and 1 Average pool layer. ResNet architectures are known as Residual networks with deep neural networks. ResNet architectures use a concept known as a skip connection. Using skip connection vanishing gradient problem reduced during the time of backpropagation.

<img src="https://user-images.githubusercontent.com/88481845/217153584-360dcb12-40af-48eb-95bc-ead11646e7b1.png">

### VGG16 

VGG16  has 21 different layers where 14 convolutional layers 5 max-pooling layers and 3 hidden layers and a softmax activation function at the output layer.
In transfer learning techniques we need to make sure the pre-trained weights should not be changed and we should make flatten layers from our data output itself. There is a padding of 1-pixel done after each convolution layer to prevent the spatial feature of the image.

<img src="https://user-images.githubusercontent.com/88481845/217153695-057d6de7-ad0c-44b7-a573-f03d09a89465.png">

Finally using fine-tuning VGG16, VGG19, and ResNet50 deep learning techniques in terms of extracting information from the data it was observed that VGG16 performed well in classifying covid, Normal, and viral pneumonia. However, excellence in high performance remained besides VGG16 with high precision and model accuracy.

# USE CASE - classifying covid, Normal, and viral pneumonia

COVID-19 is a contagious disease that caused thousands of deaths and infected millions worldwide. Using convolutional neural networks and transfer learning techniques we develop a highly accurate model to detect whether patients have been infected with covid-19, some other virus, or nothing. This work mainly focuses on the use of CNN models for classifying chest X-ray images for coronavirus, viral infected, and normal patients.

![covid_1](https://user-images.githubusercontent.com/88481845/217154219-ccb24f0d-7789-47c7-87cc-5f779711c036.jpg)

# Analysis of different techniques

## Transfer-learning technique VGG19
    1. Fixed-size of (224 * 224) image was given as input to this network.
    2.  Used kernels of (3 * 3) size with a stride size of 1 pixel, this enabled them to cover the whole notion of the image.
    3. Strides were used to apply the matrix on the top of filters and the input images.
    4. max-pooling was performed over 2 * 2-pixel windows with stride
    
### Performance Merics

![covid_6](https://user-images.githubusercontent.com/88481845/217154749-7f4a149d-3622-4580-bd60-b8e734cea44e.jpg)


## Transfer-learning Technique ResNet50

### Performance Merics
![covid_8](https://user-images.githubusercontent.com/88481845/217154848-0dd06337-2b80-4cda-b825-a707b7f815e5.jpg)

## Transfer-Learning Technique VGG16
    1. Fixed-size of (224 * 224) image was given as input to this network.
    2. Used kernels of (3 * 3) size with a stride size of 1 pixel, this enabled them to cover the whole part of the image.
    3. max-pooling was performed over 2 * 2-pixel windows with stride.
    4. The final layer has 3 outcomes where we apply softmax and find the results.
    
### Performance Merics

![covid_10](https://user-images.githubusercontent.com/88481845/217155002-bc06709f-a21c-4120-9dc4-5878cb9e5cea.jpg)


## Useful Information

### References
- [Multi-label classification using Transfer Learning techniques ](https://www.bluetickconsultants.com/multi-label-classification-using-transfer-learning-techniques.html)

## Other Projects

To view all other open source projects visit
  - [ Open Source Projects ](https://www.bluetickconsultants.com/open-source.html) 
  - [ Open Source Repositories ](https://github.com/orgs/bluetickconsultants/repositories)

## Author

[Bluetick Consultants LLP](https://www.bluetickconsultants.com/)
  #### contact us at admin@bluetickconsultants.com

<img src="https://user-images.githubusercontent.com/88481845/215745914-16aa10a5-f24b-4fa9-b1be-432454487788.png" width="50%">


