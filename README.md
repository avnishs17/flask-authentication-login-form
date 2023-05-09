# Flask Authentication App
## Description
This is a simple Flask application that demonstrates how to implement user authentication and authorization. The app allows users to register, login, and access a protected page only available to authenticated users.

## Dependencies
The app requires the following dependencies:
* Flask
* Flask_SQLAlchemy
* Flask_Login
* Werkzeug

### All dependencies can be installed by running the following command:
	<sub> pip install -r requirements.txt </sub>

## Setup
Clone the repository.
Install the dependencies.
Run the following command to start the app:
> python main.py 

## How to Use
1. Open a web browser and navigate to http://localhost:5000.
2. Click on the "Register" link to create a new account.
3. After registering, log in with your credentials.
4. Access the protected page by clicking on the "Secrets" link.

## Files
- main.py - This is the main Flask application file.
- templates/ - This directory contains the HTML templates used by the app.
- static/ - This directory contains static files used by the app, such as css folder, images and PDF files.
- users.db - This is the SQLite database used by the app to store user information.
