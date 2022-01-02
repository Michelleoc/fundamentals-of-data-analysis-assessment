# Fundmentals of Data Analysis Assessment, Winter 21/22

# Michelle O'Connor, Student ID G00398975


***
### Assessment details    

Create a Jupyter notebook titled 'pyplot'covering the following:
- Overview of the matplotlib.pyplot Python package.
- In-depth explanation of 3 plots in the matplotlib.pyplot Python package. 


Create a Jupyter notebook titled 'cao' covering the following:
- Loading CAO points data from CAO website into a pandas data frame.  
- Comparison of the 2019, 2020 & 2021 CAO points using the functionality in panadas using plots and other visualisations.


## Contents of Repository   

Jupyter Notebooks :   
1. cao jupyter notebook 
2. pyplot jupyter notebook  

Folders : 
1. test-data  
2. fifa-data which contains the fifa dataset used in the pyplot notebook. 
3. images which contains images used in both jupyter notebook

The repository also contains a requirement txt file which outlines the required libraries and packages needed to run this assessment. The packages can be installed using pip. An example of using a requirements file is:   
`%pip install -r requirements.txt`

## How to view the notebooks

### cao

You can view the notebook in static form by clicking the following image:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Michelleoc/fundamentals-of-data-analysis-assessment/blob/main/cao.ipynb)

You can view the notebook in dynamic form by clicking the following image:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Michelleoc/fundamentals-of-data-analysis-assessment/main?filepath=cao.ipynb)


### pyplot

You can view the notebook in static form by clicking the following image:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Michelleoc/fundamentals-of-data-analysis-assessment/blob/main/pyplot.ipynb)

You can view the notebook in dynamic form by clicking the following image:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Michelleoc/fundamentals-of-data-analysis-assessment/main?filepath=pyplot.ipynb)

  

## How to run the notebook

1. Download and install [Anaconda](https://www.anaconda.com/products/individual).
2. Download [cmder](https://cmder.net/) if working on a Windows operating sytem.
3. After downloading the required software, in cmder change to the required directory. 
4. Type "jupyter lab" or "jupyter notebook".
5. Jupyter will open in your web browser as a new tab. 
6. Keep the command prompt window open as it needs to stay open/running while Jupyter is active.
7. Select the jupyter notebook you wish to run.
8. Once in the notebook, on the menu bar select Kernel and then click on the "Restart and run all" option.
9. When you have finished, close or exit the tab in your browser.
10. Enter "Ctrl + C" in the command prompt to end the jupyter lab session.


## Packages used in the notebook

1. NumPy  
    Python library used for working with arrays, including a large collection of high-level mathematical functions to operate on these arrays  

2. Matplotlib  
    Comprehensive library for creating static, animated, and interactive visualizations in Python. Most of the Matplotlib utilities lies under the pyplot submodule which provides a procedueral interface to the matplotlib object oriented plotting library.   

3. Seaborn  
    Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics  
    
4. Pandas   
    Programming language for data manipulation and analysis. Pandas allows importing data from various file formats such as comma-separated values, JSON, SQL, Microsoft Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting.

5. Datetime  
    The datetime module supplies classes for manipulating dates and times.   

6. urllib.request  
    The urllib.request module defines functions and classes which help in opening URLs.

7. requests     
    The requests module allows you to send HTTP requests using Python.  

8. Regular expression (RE)   
    Regular expressions (called REs, or regexes, or regex patterns) are essentially a tiny, highly specialized programming language embedded inside Python and made available through the re module. Using this language, you specify the rules for the set of possible strings that you want to match.