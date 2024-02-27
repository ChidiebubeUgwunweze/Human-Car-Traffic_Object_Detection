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
In order to run this project successfully you have to install the following:

- __Python__: To install python, visit [python website](https://www.python.org/)
- __Flask__: To install flask execute ``pip install Flask`` on your terminal.
- __PIL__: To install pillow execute ``pip install Pillow`` on your terminal.
- __Ultralytics__: To install ultralytics execute ``pip install ultralytics`` on your terminal.

<a name="usage"></a>
## Usage
In order to make use of the project seamlessly the following should be taken note of:

- In the Web_Object_Detector folder, there are two other folders and two models in it. The two folders are __human_car__ and __traffic__ in each of them as stated before are the html file and the python file
- Before running the code always check the python file (object_detector.py) to see if the the paths listed for making use of the html file and the path for making use of the model are correct.
- To run the project you run ``python object_detector.py`` on the current path you are working on.
- To see the result(s) you have to run:
      - ``http://localhost:3030/`` for the human_car detection
      - ``http://localhost:8080/`` for the traffic detection
- To end the running project you have to execute Ctrl + C

<a name="license"></a>
## License
Contributions are permissible on this project. Thank you.
