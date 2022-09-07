# Zero-hunger
Tomato leaf disease detection app using tensorflow.
This is a tonato leaf disease detection app built using react native and flask backend. 
Steps: 1: Model training I used a pretrained keras model. VGG16 
The weights were adjusted and activation function changed to increase the accuracy of the model. 
Using early stopping and callbacks I prevented model fitting and underfitting on the test images.

I used plantvillage dataset with 10,000 images, broken into 10 classes of data to train the model. 
The model was trained using keras a tensorflow library and saved as a .h5 file

The model was then deployed using flask backend. 
The frontend was developed using react native: a Crossplatform framework for mobile applications.(ios & android)

To run app clone this project
Navigate to project folder cd project
run npm install if you have node js installed 
install expo cli 
cd expo projectname
run npm start

#voila! your app is up and running!
