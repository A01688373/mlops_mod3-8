# Deliverable: REST API

### Instructor: Carlos Mejia
### Student: Gabriela Sánchez

The best way to serve up an ML model for use by outsiders, without exposing all of the source code, is through a REST API.

This deliverable must cover the following points:
1. Creation of folder for api
2. Endpoints for:
   - Train a new model
   - Predict a new value
3. Validation of input data with exception handling using FastAPI

The folder is "api" in: 
https://github.com/A01688373/mlops_mod3_itesm/blob/main/README.md

- Install requirements.txt:

pip install -r requirements.txt

- Run FastAPI

Change to the [api](.) directory
Run next command to start calculator api locally

    ```bash
    uvicorn api.main:app --reload
    ```

- Checking endpoints

1. Access "http://127.0.0.1:8000/", you will see a message like this "Stroke classifier is all ready to go!"

example: "server.png"

2. Access "http://127.0.0.1:8000/docs", the browser will display something like this:

example: "FastAPI.png"    

3. Try running the sum endpoint by writing the values --