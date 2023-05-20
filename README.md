# Create_new_python_project
This template contains all the steps that I think are good to follow for creating a new python project

## Steps: 
### 1. Clone this repository
```console
git clone https://github.com/rubzip/Create_new_python_project.git
```
### 2. Create the Virtual Envioroment
```console
python -m venv .\venv\venv
```
### 2.5 Activate the Virtual Envioroment
This has to be done every time that we restart the kernel.
```console

```
If we are working in VScode it can be done by default:

### 3. Define the needed libraries
They should be defined all the needed libraries and the respective versions in `requirements.txt`. Here you have an example:
```
python==3.9.0
numpy==1.24.3
pandas
```
The following command will tell you the packages currently installed and their version:
```console
pip freeze 
# If we want to store the list in a file:
pip freeze > requirements.txt
```

### 4. Install the libraries
```console
pip install -r requirements.txt
```
