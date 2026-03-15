# Flask Third Party Login
A Flask application that allows users to log in with their third party accounts.

## What it does
This application provides a simple way to integrate third party login services such as Google, Facebook, and GitHub into your Flask application. It uses OAuth 2.0 to authenticate users and retrieve their profile information.

## Installation
To install the application, run the following commands:
```bash
git clone https://github.com/your-username/flask-thirdpary-login.git
cd flask-thirdpary-login
pip install -r requirements.txt
```

## Running the application
To run the application, execute the following command:
```bash
python app.py
```
Then, open your web browser and navigate to `http://localhost:5000`.

## Example usage
To log in with Google, for example, you would need to register your application with Google and obtain a client ID and secret. You can then configure the application by setting the following environment variables:
```python
GOOGLE_CLIENT_ID = 'your_client_id'
GOOGLE_CLIENT_SECRET = 'your_client_secret'
```
You can then access the login page by visiting `http://localhost:5000/login/google`. After authenticating with Google, you will be redirected back to the application.