# Car-Brands-recognition-CNN-Transfer-Learning-deployment

# Problem staement :
In this project we will be doing image recognition of car. we will be classify which car brand a given car image.

<pre>
1. Here we are having 6 categories </b>
            
    where the categories are numbered 0 to 5, in the following order:

    <b>0 audi
    1 lamborghini
    2 ford mustang
    3 Mercedes-Benz
    4 rolls royce
    5 Bentley</b>

</pre>

# Data Dataset statistics:
- we have downloaded data set from google image using imageye image downloader chrome extensions .
- Total number of image in train data set is 1623 images belonging to 6 classes.
  - Number of image in  audi is 179
  - Number of image in  ford mustang is 346
  - Number of image in lamborghini is 293
  - Number of image in Mercedes-Benz is 288
  - Number of image in rolls royce is 297
  - Number of image in Bentley is 221
- Total number of image in test data is 180
- 
# Model Building 
- Model2 is built using Vgg ResNet50 and adam optimizer , got validation acuuracy of 52% and train acurracy of 40%[link text](https://)
- Model2 is built using Vgg16 and adam optimizer , got validation acuuracy of 81% and train acurracy of 97%


# Deployment:
for we choose best model and used flask framework for deployement

