# hand-signs-recognition
#### hand signs recognition is softmax classifier to recognize signs made by humman hand. we have 6 signs from 0 to 5 made by hand 

![Screenshot](datasets/signs.png)

> the dataset contains 1028 image with size (64 x 64 x 3) for training  and 128 image for testing the model
 
> model architecture is  LINEAR -> RELU -> LINEAR -> RELU -> LINEAR -> SOFTMAX

> model training accuracy is 99% and testing accuracy is 88% 

##### fututre work
* add L2 regularization to prevent model overfitting to training set
* also try to use dropout for overfitting problem 
