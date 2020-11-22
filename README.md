## Inbuilt  investigation of Spatial and Spectral features of Hyperspectral Image Classification through CONVLSTM2D.

# Illustration
To extract spatial and spectral features from the Hyperspectral image we are implementing a CONVLSTM2D model, so that we get the advantage of both the models like Long Short Term Memory (LSTM) and Convolution (CNN) at a same point of time.
# CONVLSTM2D MODEL

![](./convLSTM2d.jpg)


## Prerequisites
We have implemented this method on Google Colab. The version of Keras is 2.4.3, version of Python is 3.6.9 and version of Tensor flow is 2.3.1.

## Code running  description
* First of all we have to import some libraries of Google credentials.
* Secondly to have an access to any thing from Google drive a granting link is generated for us in Gmail account. We have to allow it and copy that link and paste it on google colab.
* Every file has a unique id and that id can be obtained from google drive. If we want to have an access to a particular data set we
need to copy that id from google drive and subsequently paste it on google colab.
* We have defined some functions like split of training testing ratio, dimension reduction technique and creating image cubes.
* Then we set the testing ratio and window size.
* Now we trained the data set through CONVLSTM2D model.
* Afterwards we assessed the accuracy of our model.
* As an output we got the predicted image and ground truth image of that data set.

# DATA SOURCE
We got four different types of hyperspectral datasets namely Indian Pines, Pavia University, Botswana, and Kennedy Space Center
from the site: http://www.ehu.eus/ccwintco/index.php/Hyperspectral_Remote_Sensing_Scenes  
These data sets are also stored in the folder name dataset.


