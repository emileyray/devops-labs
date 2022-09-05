# Lab 1: Web Application

## Overview

This is a simple web application that shows current time in Moscow. Time is updated whenever the page is refreshed

The project contains two folders with the application implemented in two different languages:

* `app_python`: contains project implemented in python with the use of [Flask](https://flask.palletsprojects.com/en/2.2.x/quickstart/) framework

* `app_python`: contains project implemented in dart with the use of [Flutter](https://flutter.dev/) framework

## Build

### Python Build

* Install Flask: `pip install Flask`
* Go to `app_python` folder
* Set path `FLASK_APP` equal to `app.py` in your environment
* Run `python -m flask run`
* Go to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser
* Enjoy!

### Flutter Build

* Install Flutter on your OS according to [instructions](https://docs.flutter.dev/get-started/install)
* Go to `app_dart` folder
* Run `flutter pub get`
* Run `flutter run -d chrome --web-renderer html --web-port=5000` (can be any other browser besides chrome)
* Enjoy!

## Usage

### Python Usage

* Build the app and open [http://127.0.0.1:5000](http://127.0.0.1:5000)
* Time will be updated whenever the page is refreshed

![image](https://user-images.githubusercontent.com/69918609/188426184-1c392fd2-9ac6-482a-bc82-ddf1a7864500.png)

### Flutter Usage

* Build the app and open [http://localhost:5000](http://localhost:5000)
* Time will be updated whenever the page is refreshed

![image](https://user-images.githubusercontent.com/69918609/188425794-8e11d746-9aa2-4d93-8f57-8632e9f4ad68.png)

## Contact

* Emil Khabibullin
* e.khabibullin@innopolis.university
