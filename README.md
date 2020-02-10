# Image Classification Using Convolutional Neural Network with Deployment in flask

First we trained our model, which gives 50% accuracy. The parameters for measuring accuracy is confusion matrix.


![](output/out_1.PNG)

We then uses VGG16 pretrained model Pretrained model gives accuracy of around 100 % 


![](output/out_3.PNG)


The confusion matrix for VGG16 pretrained model is below :-


![](output/out_2.PNG)


We then save our model i.e h5 file as VGG16_cats_and_dogs.h5. We will use this h5 file to do predictions in real time.


![](output/out_4.PNG)


Then we install flask to run our model at real time and to do real time predictions.

![](output/out_5.PNG)


Then our model is loaded.

![](output/out_6.PNG)


Then our flask predict_html page is looks likes


![](output/out_7.PNG)


Then when we clicked the predict button, it will gives the prediction for cats and dogs of given image at real time.


![](output/out_9.PNG)
