
###### [Python Basics](https://github.com/ZackAtama/python_basics) || [PIP Installation](https://github.com/ZackAtama/python_basics/pip) || [APIs](https://github.com/ZackAtama/python_basics/apis)

# Virtual Environment
### What is a virtual environment?
The definition of a virtual environment in python takes on many forms, below are a couple of definitions that seem accurate enough.
- A virtual environment, also know as <code>virtualenv</code>, is a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages. Source: 
- A virtual environment in python is a folder that exists usually in a project folder, and it contains python packages/libraries specific to the project.

### Virtual environment setup
#### 1. Using the Command Line/Terminal
##### Linux/Mac
1. Install the virtual environment package: `sudo apt-get install python3.10-venv`.
2. Create a virtual environment called **env**: `python -m venv env`.
3. Activate the virtual environment: `source env/bin/activate`.

##### Windows 7/8/10/11
1. Install the virtual environment package: `python -m pip install --user virtualenv`.
2. Create a virtual environment called **env**: `python -m venv env`.
3. Activate the virtual environment: `.\env\Scripts\activate`.

#### 2. Using Pycharm
1. Press **Ctrl+Alt+S** to open the project **Settings** and go to Project: **project_name** | Python Interpreter. Click the **Add Interpreter** link, then on **Add Local Interpreter**.
![Add Interpreter](https://github.com/ZackAtama/python_basics/blob/dev/assets/screenshots/img_0.jpg)
2. Make sure the following are set by default:
 - The interpreter should be **Virtualenv Environment**.
 - Unless you have an existing virtual environment, use **New** for environment.
 - Pycharm will create a virtual environment folder called **env**, this can be edited. Click **OK** for both windows and let Pycharm create the virtual environment.
![Create Virtual Environment](https://github.com/ZackAtama/python_basics/blob/dev/assets/screenshots/img_1.jpg)
