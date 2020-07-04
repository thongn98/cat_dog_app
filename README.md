# Get started
## Initialize virtual envirornment
`python -m venv flask_app_env`

This will create a folder in your current directory. 

## Activate virtual environment
```
cd flask_app_env
source bin/activate
```

## Cloning this repository

Go to the directory you want to put the repository (can be in the virtual environment folder `flask_app_env`). Then use git to clone the repository

`git clone https://github.com/thongn98/cat_dog_app.git`

## Installing requirements

Go in this repository, then use pip to install the required library

```
cd cat_dog_app
pip install -r requirements.txt
```

## Copy the models

Copy the model (.h5 file) into `/models/` and change the 14th line in app.py to the right name of the model file.

## Run the app

Go back to `/cat_dog_app` and run

```
flask run
```

## View the app on your browser

Go to your browser and go to `localhost:5000` to view your app