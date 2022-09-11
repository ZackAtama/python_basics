
[Python Basics](https://github.com/ZackAtama/python_basics) | **Virtual Environment** | [Packages and PIP](https://github.com/ZackAtama/python_basics/tree/dev/pip) | [Functions](https://github.com/ZackAtama/python_basics/tree/dev/functions) | [Classes](https://github.com/ZackAtama/python_basics/tree/dev/classes) |  [APIs](https://github.com/ZackAtama/python_basics/tree/dev/apis)

# Virtual Environment
## What is a virtual environment?
The definition of a virtual environment in python takes on many forms, below are a couple of definitions that seem accurate enough.
- A virtual environment, also know as <code>virtualenv</code>, is a self-contained directory tree that contains a Python installation for a particular version of Python, plus a number of additional packages. Source: 
- A virtual environment in python is a folder that exists usually in a project folder, and it contains python packages/libraries specific to the project.

## Installation, Configuration and Activation
### Using the Command Line/Terminal
##### For Linux/Mac
1. Install the virtual environment package: `sudo apt-get install python3.10-venv`.
2. Create a virtual environment called **env**: `python -m venv env`.
3. Activate the virtual environment: `source env/bin/activate`.

##### For Windows 7/8/10/11
1. Install the virtual environment package: `python -m pip install --user virtualenv`.
2. Create a virtual environment called **env**: `python -m venv env`.
3. Activate the virtual environment: `.\env\Scripts\activate`.

## Using PyCharm
#### Step 1
Press **Ctrl+Alt+S** to open the project **Settings** and go to Project: **project_name** | Python Interpreter. Click the **Add Interpreter** link, then on **Add Local Interpreter**.
![Add Interpreter](https://github.com/ZackAtama/python_basics/blob/dev/assets/screenshots/img_0.jpg)

- **Step 2**: Make sure the following are set by default:
 - The interpreter should be **Virtualenv Environment**.
 - Unless you have an existing virtual environment, use **New** for environment.
 - Pycharm will create a virtual environment folder called **env**, this can be edited. Click **OK** for both windows and let Pycharm create the virtual environment.
 
 ![Create Virtual Environment](https://github.com/ZackAtama/python_basics/blob/dev/assets/screenshots/img_1.jpg)

- **Step 3**: Now the packages section of your virtual environment has some packages installed by default. You can now add any package by clicking on the plus icon and search for a package.
![Create Virtual Environment](https://github.com/ZackAtama/python_basics/blob/dev/assets/screenshots/img_2.jpg)

---
**Sources:** [Python Docs](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments) | [JetBrains](https://www.jetbrains.com/help/pycharm/creating-virtual-environment.html#python_create_virtual_env)

---
## Other Related Docs
- [Python Basics](https://github.com/ZackAtama/python_basics/tree/dev/python_basics)
- Virtual Environment
- [Packages and PIP](https://github.com/ZackAtama/python_basics/tree/dev/pip)
- [Functions](https://github.com/ZackAtama/python_basics/tree/dev/functions)
- [Classes](https://github.com/ZackAtama/python_basics/tree/dev/classes)
- [APIs](https://github.com/ZackAtama/python_basics/tree/dev/apis)