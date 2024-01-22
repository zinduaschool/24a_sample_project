## Setting up your local Python Project folder

1. Create you project folder and open it up using VsCode
    Terminal Commands - 
    a. cd - navigating through ypour folders
    b. mkdir - Creating a project folder
    c. code . - starting a vs code project
2. Create your main.py file that has any python script for testing purposes
3. create your virtual environment - 
    a. python -m venv venv - create youe virtual environment folder
    b. venv\Scripts\activate - Activating your python virtual environment. To confirm "(venv)" should appear at the begining of your path in a cmd terminal
    check if there are any libraries installed using "pip freeze" command

4. Installing a simple library/package. To do you use the pip command
    lets try and install numpy - Numerical python, helps in advanced mathematical operations/numerical operations

    command: pip install numpy
5. Installing from requirements.txt file - list down required libraries inside a file named requirements.txt
    Run command "pip install -r requirements.txt" to install all libraries listed

    NB: make sure to list down jupyter inorderv to start running jupyter notebooks locally. 

6. You can now start jupyter server using the command
    jupyter notebook
