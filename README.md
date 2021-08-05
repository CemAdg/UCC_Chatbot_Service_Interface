# Chatbot Dynamic Service Integration App of UCC @ Retail

Web App with REST APIs for dynamically integrating services to a speech assistant / chatbot without adapting the chatbot to the corresponding tasks of the service 

## About the Stack

tbd


## Chatbot Dynamic Service Integration REST APIs

tbd

When running the app locally, the app is accessible under the following URL: http://localhost:5000 or  http://127.0.0.1:5000

## Getting Started

### Installing Dependencies

#### Python 3.7

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Environment

We recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organized. Instructions for setting up a virtual environment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by running:

```bash
pip install -r requirements.txt
```

This will install all of the required packages we selected within the `requirements.txt` file.

##### Key Dependencies

- [Flask](http://flask.pocoo.org/)  is a lightweight backend microservices framework. Flask is required to handle requests and responses.

- [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/#) is the extension we'll use to handle cross origin requests from our frontend server. 


## API Reference

This chapter gives a detailed documentation about the API endpoints and their expected behavior.

### Endpoints

- GET '/api/'


#### GET '/api/'
- tbd
```
{
    'tbd': 1,
    'success': true
}
```

### Error handling

The API will return the following error responses based on the request failures:

    400: Bad Request
    404: Not Found
    422: Unprocessable Entity
    500: Internal Server Error


## Running the server

From within this directory first ensure you are working using your created virtual environment. 

To run the server, execute the following within the backend folder:

Linux:
```
python3 app.py
```

Windows PowerShell:
```
python app.py
```
