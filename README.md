# EPAM-Final-Project

## Herbify

### Plant Identification App

Herbify is an plant identification RESTFUL web app utilizing vgg-16 deep learning neural network architecture for classifying plants according to their images. It also allows people to socialize via registering themselves to app, and chat with other users, share their achievements, discover the properties of plants growing in specific geographical areas.

### Used Technologies
- HTML/CSS
- Python Flask
- REST APIs
- tensorflow
- keras
- SQLAlchemy

### Dependencies required to work with Herbify (lastly updated at 08/07/2024)

- tensorflow 2.16.1
- keras 3.4.1
- flask 3.0.3
- Flask-Login 0.6.3
- Flask-SQLAlchemy 3.1.1
- Werkzeug 3.0.3

### Instructions to Run Herbify

project can be run by typing following commands on terminal

1. cd app
2. export FLASK_APP=run.py
3. export FLASK_ENV=development
4. flask run
5. local development server will be initiated at `http://127.0.0.1:5000`
6. go to the server url to use and test the application
