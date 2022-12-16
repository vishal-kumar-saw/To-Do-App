## FastApi-App

1. Make a Directory for the Project and navigate into it
     > mkdir fastapi-app && cd fastapi-app

2. Create a Python Virtual Environment and Activate it
     > python3 -m venv venv 
     > ls
     > source venv/bin/activate

3. Install Fastapi 
     > pip install fastapi

4. Install an ASGI server 
     > pip install "uvicorn[standard]"

5. Install package for the template 
     > pip install python-multipart jinja2

6. Install package for database support
     > pip install sqlalchemy


7. The Open the Project with VSCode and create three files: `app.py`, `database.py` and `models.py`

Note:
 Update Pip `python3 -m pip install --upgrade pip`

6. To run the app, with uvicorn using the file_name:app_instance

     > uvicorn app:app --reload


7. Commit and push your code to github.com and Deactivate the Virtual Env.
   
    $ deactivate
    $ conda deactivate

