## Classification of physical activity


This project is build on python 3.7, but it will probably run on any python3 version.
 

### Check your python version: 
```bash
python --version
```
### Verify that pip is installed:
```bash
which pip
```
or 
```bash
pip --version
```

### If **pip**  is not installed run 
```bach
sudo apt-get install python3-pip
```

### To create new virtual environment:

1. Install the virtualenv packege with
    ```bash
    pip3 install virtualenv 
    ```
    or verify the virtualenv installed:
    ```
    virtualenv --version
    ```

2. Create new virtualenv (here it's named pythonUCU)
    ```
    virtualenv pythonUCU
    ```
3. Active your virtual environment:

    ```
    source pythonUCU/bin/activate
    ```
   
    To deactivate:
    ```
    deactivate
    ``` 

We will continue with installation inside the pythonUCU env, so make sure you are inside the virtual env. 
   
    
    source pythonUCU/bin/activate
    

### Install Jupyter notebook 
```
pip install jupyter notebook
```
 
### Install packages for this project from requirements.txt 
```
pip install -r requirements.txt
```

### Start Jupyter from inside the pythonUCU env

```
jupyter notebook
```