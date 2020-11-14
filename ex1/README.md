# Fashion_MNIST

The Fashion MNIST dataset was created by e-commerce company, Zalando.
It is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. 
Each example is a 28x28 grayscale image, associated with a label from 10 classes.

# Prerequisites
>- Python
>- Tensorflow
>- keras
>- Pandas
>- NumPy
>- Matplotlib

## DataSet Description
>- Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
>- Each pixel has a single pixel value associated with it, indicating the lightness or darkness of that pixel(higher numbers meaning darker).
>- The pixel value is an integer between 0 and 255.
>- The training and testing datasets have 785 columns.
>- The first column in the dataset consist of class labels which represents the article of clothing.
>- The rest of the columns contain the pixel values of the associated image.

![](https://github.com/sarthak169/Fashion_MNIST/blob/master/label.PNG)

# Objectives
>- View the data as an image
>- Train different classifiers
>- Compare performance for different classifiers using various metrics
![](https://github.com/sarthak169/Fashion_MNIST/blob/master/fashion.png)

All models were trained by Lenet-5 CNN architecture:
![LeNet-5](http://media5.datahacker.rs/2018/11/LeNet5-1024x188.png)
The Lenet-5 network has been implemented 4 times. Different regularization techniques were added in each implementation including:
1.	Dropout
2.	Weight Decay
3.	Batch Normalization

Optimized by Adam optimization technique by its defult parameters (lr=0.001), 100 example batch size and trained for 40 epochs were used. 


# Performance Mertices Used:
>- Accuracy Score
>- Logarithmic loss (L2)
