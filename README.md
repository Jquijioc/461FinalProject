# 461FinalProject: Identification of Aircraft using EfficientNet

## Project Overview
In this project, we used EfficientNet to identify military aircraft. Identification of military aircraft plays an important role in modern day defense. Especially in modern times, where the chaotic events seen in Ukraine and other places necessitates aircraft identification when the only sources for analysis come from video and images taken from phones or drones since they are the only gear available in the field. Our Goal was to develop a model capable of identifying a wide range of military aircraft from a multitude of countries.

## Features
* **EfficientNet Models**: Utilization of pretrained EfficientNetB3 to classify aircraft
* **Heatmap Visualization**: Utilized Heatmaps for images so users can see what the model was "looking at," using Grad-CAM



## Example Aircraft Prediction:
Here is an example of the model prediction and the actual aircraft used:

Input Image of an F-15

### Heatmap Visualization and Identification:

![alt text](https://github.com/Jquijioc/461FinalProject/blob/main/GithubF15.jpg)


## Installation

### **Important**

Installation of the Dataset must be done in a directory level above the repo

1. Make a housing folder for the repo. This is where you will download the kaggle dataset. An example of this could be /AircraftIdentify/repo/, with AircraftIdentify being your housing folder
2. Download Dataset:
https://www.kaggle.com/datasets/a2015003713/militaryaircraftdetectiondataset

2. Clone the repo inside the housing folder
3. Install dependencies using ``` pip install -r requirements.txt ```
4. Run the Pretrained model in Project.ipynb. Note: If you prefer to tweak the model yourself to try out hyperparameters, you can do so in the testing.ipynb file.
