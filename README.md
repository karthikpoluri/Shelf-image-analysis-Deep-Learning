# Shelf-image-analysis-Deep-Learning

I have conducted an object detection recognition analysis on shopping mall shelf images.
I used two types of analysis for this 
1. R CNN algorithm 
2. SSD mobilenet algorithm.


# Links to the Data: The data is 1.4 GB and having 345 Shelf images which combined have 13000 product images divided into 10 classes. 
https://github.com/gulvarol/grocerydataset/releases/download/1.0/GroceryDataset_part2.tar.gz

# Dependancies
The solution depends on the following Libraries.
* TensorFlow successfulI
* Keras
* Tensorflow Object Detection API
* OpenCV

# Resnet CNN
I have used Resnet CNN to build our first model which is pretty successfull with 89% accuracy.
Detailed documentation regarding this model was provided in the PDF form above.

# SSD Mobilenet
Even though R CNN worked well i have also tried this SSD Mobilent which is amazing for trials.
I have first created TF records for both training and evaluation using the above-listed code.
Using both trains. record and eval record I have trained my model on GPU and evaluated on my CPU.

# implimentation
Whatever we do but finally implementation is what matters the most so here is my implementation where I have got 95% accuracy in predicting the shelf image boundaries and recognizing the brand names.

This is one of the amazing projects I have done Thanks for reading I appreciate your time.
