# Dog-vs-Cat-Binary-Class-Prediction
https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition

There are two classes in the problem statement (i)Cat=0 and (ii)Dog=1.The aim of the project is predict which class does a given image belong. The dataset is divided into train,validation and test. There are 10000 train images for each class, 2500 validation images for each class and 12500 images for test.

Approach:

1.Used Image Data Generator for reading images from local system.

2.Using Imagenet weights I tried to train the model using VGG16,VGG19 and InceptionV3. Out of all the three models InceptionV3 gave the most promising score:

3.I also trained a Sequential model using trial and error method, the model however did not perform as well as InceptionV3. 

So for this project I decided to use InceptionV3+imagenet weights as my finalized model.
