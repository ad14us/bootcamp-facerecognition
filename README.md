# bootcamp-facerecognition

## About The Project
This project was created to do face recognition using the VGG16 and VGG19 model architecture. The output will be label with male or female. The dataset used for training is celebfaces attributes (celeba) which have 200 K images in original dataset. For this project, i only use 5 K images. 

## The files
I use jupyter notebook to develop this project.
* project_1_EDA.ipynb
  This is Exploratory Data Analysis that i used to clean the dataset. You don't need to run again this file as i have clean the label and images needed as input. 
* project_1_training_vgg_model.ipynb
  The file used to training the vgg19 and vgg16. Recomendation to use GPU instead of CPU. Hyperparameter tuning i used as below :
  Epoch : 20 and 30
  Optimization : Adam
  Learning Rate : 0.001
  loss : sparse_categorical_crossentropy
* project_1_validation_vgg_model.ipynb
  The file used to validation the model
* project_1_predict_other_image.ipynb
  The file used to predict other image dataset

## The Result
* VGG16 ep 30 give 0.95 accuracy and 0.94 validation accuracy
* VGG19 ep 30 give 0.93 accuracy and 0.92 validation accuracy
