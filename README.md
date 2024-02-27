## Table of Contents
- [About](#about)
- [Installation(s)](#installation)
- [Usage](#usage)
- [License](#license)


<a name="about"></a>
## About
The Human-Car-Traffic Object detection project is an object detection web service. The project aims to make use of two trained machine learning models (one for detecting cars and humans and the other for detecting traffic light and signs) to detect objects in an image. The project contains the following programming languages and elements in it:

### Programing Languages
- Python
- HTML
  
### Elements of the project
- __datasets__ : This folder contains both the human and car, and then the traffic datasets in each of these datasets contains a train and valid folder and a data.yaml file. The train and valid folders both contain the images and the label folders. The datasests were used to train the model for detecting these objects. 
- __samples__ : The samples folder contains the images that will be used to test the trained model. It contains the folder for the human and car images and for traffic images respectively
- __Web_Object_Detector__ : The Web_Object_Detector folder is where the codes and the two models lie. It contains two folders that contain the code for the human and car detection and the traffic detection in each of these folders lie the frontend(index.html) and the backend(object_detector.py). Also, the names of the two models are __human_car.pt__ and __traffic.pt__
 
<a name="installation"></a>
## Installation
In order to make use of the 

<a name="usage"></a>
## Usage
This is the usage section.

<a name="license"></a>
## License
This is the license section.
