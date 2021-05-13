# cat-and-dog-classifier
I have created a machine learning/deeep learning model which can classify an image as an image of an dog or an cat.
Here i have first used some very basic convolution layers in which i have been getting an accuracy of around 80% then after I have used the technique of transfer learning and used the base layers of the model VGG16 and then i have got an accuracy score of 94% which can also be increased by running the model for some more epochs.
I have also saved the model so that anyone can directy use the model without training the model on their systems. 
I have used a very small set of train test and validation sets which are available on Kaggle.
I have also create a function which can make a prediction on new images that we give rather than those images present in train test and validation sets.
![Screenshot (11)](https://user-images.githubusercontent.com/62389014/118094591-8df17f00-b3ec-11eb-832d-eb17476b471b.png)
I have deployed this deep learning model using flask and created a interactive webpage.
you just need to uplaod any image from your device and the model classifies it and gives you result
