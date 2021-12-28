# Fundamentals of Data Analysis Assessment - Winter 2021
## Galway Mayo Insitute of Technology
## Author: Ross Downey (G00398275)
## Lecturer: Dr. Ian McLoughlin
***

This repository exists as part of the assessment of the "Fundamentals of Data Analysis" module for the Higher Diploma in Computer Science in Data Analytics.  
The repository contains two Jupyter notebooks, pyplot.ipynb and cao.ipynb. Pyplot.ipynb provides an overview of the matplotlib.pyplot package in Python. Cao.ipynb is a notebook which loads the points from the CAO website and examines the differences between the years 2016 to 2021 using pandas and plots. More details have been included below.  
A requirements.txt file has also been added to run the notebooks with minimal configuration.

## Install
***


These are the steps to install the required software packages to run the notebooks:

1. Download [Anaconda](https://www.anaconda.com/),
 or should the entire Anaconda package not be required download [Python](https://www.python.org/downloads/)
2. Download [CMDER](https://cmder.net/) or other suitable console terminal.



## Overview of the matplotlib.pyplot Python package
***

This Jupyter notebook contains an overview of the matplotlib.pyplot package, including discussion on the creation of the package, and sections devoted to three types of plots: scatter plots, histograms and pie charts.

## Run
***

This is how to run the notebook

1. Open console terminal
2. Enter 'jupyter lab'
Note: Jupyter lab is run on your default internet browser.
3. Open the pyplot.ipynb notebook

Alternatively, the following badges can be clicked to run the notebook:

NB Viewer for a static version of the notebook  

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/G00398275/FODA2021/blob/main/pyplot.ipynb)

Binder for a dynamic copy which you can edit if required

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/G00398275/FODA2021/HEAD?labpath=pyplot.ipynb)
***

## Explore  
***
On opening the pyplot.ipynb notebook you will see an introduction and discussion on the matplotlib.pyplot package. Numpy was used to generated random data to simulate plots in the sections on scatter and histograms, and also some manually entered data was used. Manually entered data was also used to generate pie charts.  
Consider the following code:

`x = np.random.normal (100.0, 0.25, 1000)

plt.hist (x, bins=20, facecolor='g')
plt.rcParams["figure.figsize"] = (10,8)
plt.title ('Histogram - Assay Results', size=20)
plt.xlabel('Assay Results (%)', size=15)
plt.ylabel('Frequency', size = 15)
plt.xticks(fontsize=12)
plt.yticks(fontsize=12)
plt.grid(True)
plt.show()`

The can be used to generate a histogram with a normal distribution around a mean of 100. 
Adjusting the mean (100.0), mu (0.25) and size (1000) values in the brackets can yield a different plot if the user wishes.
Adjusting the formatting options can also change the appearance of the histogram plotted.
***

## CAO Points Notebook
***

This Jupyter notebook contains an overview of how to load CAO points from the CAO website and a comparison of the CAO points in the years 2016 to 2021 using pandas and plots.

## Run
***

This is how to run the notebook

1. Open console terminal
2. Enter 'jupyter lab'
Note: Jupyter lab is run on your default internet browser.
3. Open the cao.ipynb notebook

Alternatively, the following badges can be clicked to run the notebook:

NB Viewer for a static version of the notebook 

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/G00398275/FODA2021/blob/main/cao.ipynb)

Binder for a dynamic copy which you can edit if required

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/G00398275/FODA2021/HEAD?labpath=cao.ipynb)


***

## Explore  
***
On opening the cao.ipynb notebook you will see an introduction and discussion on the CAO points system. The first section loads the points from all level 8 courses offered in 2021, taken from a web page on the CAO site. The next section loads the level 8 points from 2020 which were located in an excel file on the CAO site. The third section loads level 8 2019 points from a "PDF" file.Further PDF files were available for the years 2018, 2017 and 2016.  A comparison was done between the years by adding all points to various pandas dataframes to see the changes from year to year on the CAO system. Subsequent to this, the points from level 6 and 7 courses were taken from the CAO site and analysed in the same manner to discern any trend in the points changes during the years in question.  
Increases were observed in 2020 and 2021. These increases can be attributed to the predicitve grades model employed as a result of the COVID-19 pandemic. In the years prior to 2020 no obvious increase was observed.  
All relevant dataframes are included in the notebook, along with statistical analysis and relevant plots to help viewer comprehension.

## Credits
***

I used a number of different packages in this jupyter notebook to help simultate data (numpy) and plot data (matplotlib, seaborn) etc. 
Details of the packages used are included below:

### Numpy

Numpy, or numerical Python, is a library used in Python to create different types of arrays or multi-dimensional matrices, and includes a large collection of mathematical functions to operate on these arrays. In this case Numpy will be used to simulate data using the numpy.random package based on certain mathematical distributions.  

### Pandas
 
Pandas is an open source library built for data analysis and manipulation in Python

### Matplotlib
  
Matplotlib is a plotting library used in python to create visual plots from data. For this case Matplotlib will be used to create certain plots to help present large amounts of numerical data, generated using Numpy, in a clear and concise manner using histograms, charts etc.  



## Contact 
*** 

I can be contacted by e-mail at 'G00398275@gmit.ie' for any queries or issues.