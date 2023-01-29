# FastAPI Notes Application

Repository containing code for "Deploying FastAPI applications to Vercel".
Reference: https://blog.logrocket.com/deploying-fastapi-applications-to-vercel/

## Running the application

To run the application on your machine, clone this repository and install the dependencies:

```
$ git clone https://github.com/Youngestdev/fastapi-notes-app && cd fastapi-notes-app
```

Setup a virtual environment:

```
$ virtualenv --python=python3.8 venv
$ source venv/bin/activate
$ deactivate
```

Install dependencies:

```
$ pip3 install -r requirements.txt
```

Run the application:

```
python3 main.py
git add . && git commit -m "C" && git push origin main && vercel --prod

```

## Error?

If it's an error with regards to path, run the command:

```
export PYTHONPATH=$PWD
```

Any other one? Please raise an issue.
