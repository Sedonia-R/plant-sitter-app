Welcome to Plant Sitter Pro!

To initiate this project, I started by setting up the backend. I used Python 3.10.15, Flask 3.0.3, and Flask-SQLAlchemy 3.1.1

Others thing to install for this project:

  flask_cors
  flask_restful
  axios

Reference for Axios: https://www.geeksforgeeks.org/axios-in-react-a-guide-for-beginners/

My Flask application file structure:

/plant-sitter-app
  /api
    /app
      __init__.py
      models.py
      routes.py
    /venv
    HelloApiHandler.py
    run.pyt

I configured CORS by installing Flask-CORS and initializing it in my __init__.py file.

To create a new python virtual environment (venv, located in the api folder)I used:

  python -m venv venv

To activate venv, I used (from the api folder):

  source venv/bin/activate

In my project's root directory (plant-sitter-app), I created an app.py file.

To check that the backend is running:

  flask run  #in the terminal
  localhost:5000/flask/hello  #in the browser
  # {"resultStatus": "SUCCESS", "message": "Hello Api Handler"} 

Then I setup the frontend, using React. I created a folder called frontend, navigated into it, and used create-react-app:

  npx create-react-app .


