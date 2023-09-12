# Translator Using SeamlessM4T Model

Since the model is too big to upload on GitHub, therefore follow the below steps to run the project.

## Install Python
If Python is already installed on your system, you can check its version by running
```
$ python --version
Python 3.11.3
```
Otherwise, install it.
## Install a Text Editor or IDE
I used VS Studio.

## Start a new project with Flask
Before starting any new Python project, we should create a **virtual environment**
```
# Create a new virtualenv named "myproject"

# Python 3.3+
$ python -m venv myproject

# Python pre 3.3
$ virtualenv myproject
New python executable in myproject/bin/python

# Activate the virtualenv (OS X & Linux)
$ source myproject/bin/activate

# Activate the virtualenv (Windows)
$ myproject\Scripts\activate

# Change the directory
cd myproject
```
You’ll need to activate your virtual environment every time you work on your Python project. In the rare cases when you want to deactivate your virtualenv without closing your terminal session, just use the `deactivate` command.

## Install Flask
Use pip to install the Flask
```
pip install Flask 
```
## Now Clone the Repository
```
git clone https://github.com/areejayy23/SpeechTranslator.git
```
- You can clone it anywhere on your system for now
-  After cloning it, copy the files from the cloned folder to your Flask app folder
-  Following are the files in the repository
```
├── app.py
├── README.md
├── requirements.txt
├── libsndfile.so.1
└── templates
    └── index.html
```
## Copy the Files to Your Flask App
- Copy the repository files to your Flask App
- Copy ** libsndfile.so.1 ** to lib folder in your Flask App
## Install the Dependencies
Now open the code on any IDE or terminal and run the command to install the dependencies
```
pip install -r requirements.txt
```
## Run the Project

```python app.py```

## Enjoy
### Following instructions works fine on Linux System. For installation of dependent libraries on MacOS or Windows, other steps are required to run.
