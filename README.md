# virtual-envs-ands-notebooks

<a href = "https://www.geeksforgeeks.org/using-jupyter-notebook-in-virtual-environment/"> Using Jupyter Notebook in Virtual Environments </a>

### 1. Create venv

```
python -m venv venv
```

### 2. Activate venv
```
venv\Scripts\activate
```
### 3. Install ipython and ipykernel
```
pip install ipython
pip install ipykernel
```
### 4. Create a kernel that can be used to run jupyter notebook commands inside the virtual environment
```
ipython kernel install --user --name=venv
```

### 5. Select the installed kernel when you want to use jupyter notebook in this virtual environment
In VsCode:

<img width="738" alt="image" src="https://user-images.githubusercontent.com/45129483/209995940-2a44ec16-03fc-45dc-b7f2-ef18819cfe2a.png">

In browser:

<img width="432" alt="image" src="https://user-images.githubusercontent.com/45129483/209995989-8f3c3403-0a62-4edc-94ae-c2db0486e97d.png">
