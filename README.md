# Python API Project
A complex FastAPI api project with DB support and Authentication, using a tutorial from FreeCodeCamp.com

## Getting Started
1. create virtual environment (optional):  
note: This is specific to Linux, for more info go [here](https://docs.python.org/3/library/venv.html) 
```
python3 -m venv venv
source ./venv/bin/activate
```
2. install dependencies: `pip install -r requirements.txt`
3. create postgres database (if you need easy access to a postgres database, check out [elephantsql](https://www.elephantsql.com/))
4. setup environment variables
    a. `cp template.env .env`
    b. update `.env` file with db connection info
5. run server: `uvicorn app.main:app --reload`
6. access server on localhost port 8000
7. view api docs at [http://localhost:8000/docs](http://localhost:8000/docs)
