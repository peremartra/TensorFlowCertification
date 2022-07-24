# TensorFlow Certification
Notebooks Used to prepare the TensorFlow Certificationby Google. https://www.tensorflow.org/certificate

## Files. 
[ConvMNISTImage.ipynb](https://github.com/oopere/TensorFlowCertification/blob/main/ConvMNISTImage.ipynb)
With 7 models, starting with the most simple model, just tho Dense layers from with more complicated models using diffent kind of layers. 
The noteboopk is organized in parts:

**Import libraries and Data.**

**Functions**

With funtions to plot the data. A callback function to stop the learning process whet it reach an appropiate % in  **val_data**. And one function witth all the models inside and their results. 

**Models training**

Every model has an specific part where you can found the result after 100 epochs of traing. 

**Experiments**

**Data Augmentation** 

After transform the data with Data Augmentation i repeated the 100 epoch training for the major part of the models. 

**Custom Learning Rate**

Just with one model, I Used a callbackl function to modify the learning rate in every epoch. After a first execution choose a learning rate and use it for a second 100 epochs traing. As i've been using an Adam optimizer the learning rate isn't crucial, but as a aexperiment it was easy to do, and improved the results a little bit. 
[IMAGERecog.ipynb](https://github.com/oopere/TensorFlowCertification/blob/main/IMAGERecog.ipynb)
Binary classification problem using the cat & dogs dataset. 

Two different convolutiona models executed with and without Data Augmentation. 

Two different samples of Transfer learning with Inceptionv3 and VGG16. 
