# Real-Time Traffic Sign Detection Web Application
![Screenshot of a model which detected traffic lights](https://github.com/umairmaratab/Real-Time-Traffic-Sign-Detection-Web-Application-with-YOLOv8-Model/blob/main/traffic_lights.png)
## Goal
This project implements a real-time traffic sign detection system using the `YOLOv8` model trained on a custom dataset of `traffic signs`. 

## Tools
* YOLOv8 (Traffic light Detection)
* HTML (Front-end)
* Flask (Backend)
* Waitress

## Training:
The model inference is performed on images captured through the web interface, providing instant feedback to users about the detected signs.

## Key Features:

* Utilizes YOLOv8 model for accurate and efficient real-time traffic sign detection.
* Integrates with Flask to create a seamless web application interface.
* Employs Waitress as the WSGI server for optimal handling of HTTP requests.
* Supports detection of various traffic signs, enhancing road safety and traffic management.

## How to use it:
* Clone this repo
* Create a  virtual environment using `conda` or `pyhton3 venv` i.e `python3 -m venv venv`.
* Install requirements with `pip install -r requirements.txt`
* To run the service `python3 object_detector.py`
