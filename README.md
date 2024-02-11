
# Image Classificaiton - Animals 10 Dataset using ResNet18

The dataset contains about 28K medium quality animal images belonging to 10 categories: dog, cat, horse, spyder, butterfly, chicken, sheep, cow, squirrel, elephant.

The objective is to classify the images using Deep Learning.


## Built With

Below listed Tools /Environments used to create, Train, Test and Deploy the model.
 - Python 3.10
 - Pytorch
 - TorchVision
 - Albumentations
 - CV2
 
## Sections

- Data Preparation  
  - Download Dataset from kaggle (alessiocorrado99/animals10)
  - Perform EDA on the data to understand the data distribution 
  - Perform Undersampling to address the class imbalance issue


- Model Selection
  - Based on the resource limitation to 4 GB and time constraint to run the algorithm in 2 mins. I have chosen ResNet18.
  - Select the ResNet model (https://pytorch.org/vision/main/_modules/torchvision/models/resnet.html)


- Model Training 
  - Performed PCA to identify the important features
  - Performed TSNE and clustering to visualize the classes
  - Performed Data Augmentation [Resize, Normalize, colorjitter]
  - Batch training the tarin dataset with ResNet18 model
  - Calculate the training loss with CrossEntropyLoss

- Model Validation
  - Evaluated validation batch with test data
  - Calculated the CrossEntropyLoss
    
   

## Authors

- [@dmahali1983](https://github.com/dmahali1983)

