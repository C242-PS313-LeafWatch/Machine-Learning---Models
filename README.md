 # Machine-Learning---Models

## Model Overview
* our model is created using transfer learning technique with MobilenetV3Large as our base model  
* this repository also contain another model that use EffcientnetB0 for comparrison however we ended up using the one with MobilenetV3Large as our base model

## Data
* we get our data from kaggle public dataset, the dataset contains around 87k RGB images of healthy and diseased crop leaves which is categorized into 38 different classes.  
* there is also a separate test folder created for prediction purposes containing 33 images.

## Feature
* The model task is to classify the plant disease present in the inputed images 

## Results
* Our model demonstrated strong performance in our plant disease detection task, achieving high accuraxy in our test dataset and was able to correctly predict 31/33 test images correctly

## Acknowledgments
* New Plant Diseases Dataset created by Samir Bhattarai, is a great dataset with quality images that make this project possible  
link : https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset/data
