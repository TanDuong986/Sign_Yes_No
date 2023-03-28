# Yes_No_Sign
* This is final project of Coursera course:  [**Introduction to Computer Vision and Image Processing**](https://www.coursera.org/learn/introduction-computer-vision-watson-opencv).

* The task is clasify the image that have stop sign or not.

* This project build a simple Convolutional Neural Network. The dataset has approximate 100 samples for each class with various size, I had write a function to survey the size of all image, you can choose the size to train based on your need.

* Although the amount of data is quite small, I gain the accuracy among 75-80%. I know it can higher, let contribute more for me if you have some fancy solving. I'm looking forward to hearing you 🥰🥰.

`update`: **29/3/2023**
* I have crawled quite a bit more data to increase the train set to 290 samples, and at the same time corrected the network structure by adding another convolution layer, the model improved quite well, the test on the independent set in the directory [test_data](./test_data) achieved 90% accuracy. Photos with signs that are too small or have bad color quality are usually undetectable.
