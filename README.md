# realestate_data_analysis
This project demonstrate data analysis of Sacramento real estate transactions Dataset using Numpy.

# Objective:
* Create readable DataFrame using pandas, verify head and tail of the dataset.
* Import Sacramento_realestate_transactions.csv using getfromtxt() method, converting into 2-dimensional array.
* Display first 5 rows and only (stree, city, zip, state) columns.
* Display result in boolean, True where zip is equal to for example "95815".
* Display the index where zip is equal to 95815 using where( ) method.
* Now save this array into new file called 'result.csv' using savetxt() method.
* Display 'result.csv' through pandas.

# Steps To Run:
For this demonstration, I am using the Jupyter Notebook, open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

### Step 1:
Create a new folder and called it numpy.

$ mkdir numpy ---> $ cd numpy ----> $ mkdir Project 1

### Step 2:
Create a virtual enviroment and install dependencies by running requirements.txt.

$ pip install virtualenv env

$ source env/bin/activate

$ pip install -r requirements.txt

### Step 3:
Run the script.

$ cd python_pandas_operations

$ jupyter notebook
