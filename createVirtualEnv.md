#Creating a virtual env for python


**Step 1:**
    
Make sure virtualenv is installed:
    
    sudo easy_install virtualenv
    
**Step 2:**

Make a directory for your virtual environment

    mkdir ~/virtualenvironment
    
**Step 3:**

Now create a fresh environment for your app:

    virtualenv ~/virtualenvironment/my_new_app

**Step 4:**

the next step is to activate te virtualenv.

    cd my_new_app/bin
    source ./activate

**Step 5:**

install your libraries now using pip e.g. :

    pip3 install tensorflow
    
**Step 6**

if you wish to leave the virtual environment you simply type:

    deactivate

## How to use it:
Now you simply activate it or deactivate it if you wish to use it. 

**PYcharm** users can select the desired virtualenv you use (and even create one in the window "project interpreter"). 

**Spyder** users just open spyder while in the virtualenv.


source: http://www.pythonforbeginners.com/basics/how-to-use-python-virtualenv