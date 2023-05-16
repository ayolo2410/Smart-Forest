# Smart-Forest

## Description
The project is a proof of concept application developed using the Flask library. It utilizes the YOLOv8 machine learning algorithm for object detection, specifically targeting the identification of humans and vehicles trespassing in forest areas. The purpose of the project is to assist forest authorities in efficiently dealing with trespassing incidents without the need for constant patrolling, thereby optimizing resource utilization.

## Features
### Object Detection: The application utilizes the trained YOLOv8 model to detect humans and vehicles in real-time using the webcam feed.
### Custom Dataset: The model has been trained on a custom dataset specific to forest areas, enabling accurate detection in this environment.
### Flask Web Application: The project is implemented as a Flask web application, providing a user-friendly interface for accessing and utilizing the object detection capabilities.
### Future Enhancements: The future version of the project aims to incorporate IoT devices equipped with camera modules to enable detection and monitoring in remote areas of the forest.

## Installation
1. Clone the project repository:
 `git clone`
 
2. Install the required dependencies:
 `pip install -r requirements.txt`
 
## Usage
1. Start the Flask application:
 `python app.py`
 
2. Access the application through the provided URL (e.g., http://localhost:5000).

3. Grant necessary permissions to access the webcam.

4. Once the webcam feed is displayed, the application will automatically detect and highlight humans and vehicles in the video stream.

## Documentation
For more detailed information, refer to the project's documentation, which includes instructions on training the YOLOv8 model, dataset preparation, and other relevant details.
