# Setting up a python-django development environment using venv.
#### 1. Install Python
- Download from the official python website
```
https://www.python.org/downloads/release/python-3111/
```
#### 2. Install Pip
- Run in terminal
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```
```
python3 get-pip.py
```
#### 3. Install venv
- Run
```
pip3 install venv
```

#### 4. Cd into project directory and create virtual environment:
```
python -m venv my_project
```
#### 5. Change into created virtual environment
```
cd my_project
```

#### 6. Activate virtual environment
```
source bin/activate
```
#### 7. Install django into virtual environment
```
pip install django
```
#### 8. Check django installation:
```
django-admin --version
```
#### 9. Start django project:
```
django-admin startproject my_project
```


