# handwritten-digit-angle-prediction
This task aims to predict the angle of image that has a rotated handwritten digit.

Synthetic images of handwritten digits originated from the widely known MNIST database (http://yann.lecun.com/exdb/mnist/). Rotated images together with the corresponding angles (in degrees) were used for training and testing. 

There are 5000 samples in total, 500 for each digit. Each example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is represented by a floating point number indicating the grayscale intensity at that location. Each image is uniformly rotated from 1 to 90 degrees with stepsize 2. 

Examples from the dataset:
![image](https://user-images.githubusercontent.com/44447135/112702037-77e52a80-8e4f-11eb-9fb1-f4b9562b53d0.png)

For each digit, degrees 1,5,9,...89 are used for training, 3,7,11,...87 are used for testing. The accuracy of the two algorithms are compared in terms of RMSE:

![image](https://user-images.githubusercontent.com/44447135/112706233-3ad56400-8e60-11eb-9c7c-0d092b9618bd.png)
