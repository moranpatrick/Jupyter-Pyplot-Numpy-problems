# Problem set: Jupyter, pyplot and numpy
Patrick Moran  
g00179039@gmit.ie  
This repository contains the soloutions to a Problem [sheet](https://emerging-technologies.github.io/problems/jupyter.html) for my Forth Year Emerging technologies Module.

## How To Use this Repository?
This problem sheet was completed using Jupyter Notebook. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more. You can try out the notebook on their website or click [here](https://try.jupyter.org/).  

To install Jupyter click [here](http://jupyter.org/install.html) for full instructions.

You can view the notebook in this repository but you cannot interact with it. To view the notebook click [here](https://github.com/moranpatrick/Jupyter-Pyplot-Numpy-problems/blob/master/Jupyter%2C%20Pyplot%20and%20Numpy.ipynb).

## Running your own Notebook
Step 1: Open the notebook in this repository.  
Step 2: Click Raw. (Its On the right)  
Step 3: Right Click somewhere over the text and click "Save as"  
Step 4: Remove the .txt extension from the end. Make sure the file is saved as .ipynb  
Step 5: Open a command prompt where the file you downloaded is saved.  
Step 6: Then type  
>\> jupyter notebook  

Step 7: This will open the notebook at the directory level in your browser. Click on the notebook you saved. (Jupyter, Pyplot and Numpy.ipynb) and your good to go.

## Problem Sheet
These problems relate to Jupyter, numpy, and pyplot. We will use the famous iris data set. 

### 1. Get and load the data

Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.

### 2. Write a note about the data set

In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.

### 3. Create a simple plot

The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.

### 4. Create a more complex plot

Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.

### 5. Use seaborn

Use the seaborn library to create a scatterplot matrix of all five variables.

### 6. Fit a line

Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.

### 7. Calculate the R-squared value

Calculate the R-squared value for your line above.

### 8. Fit another line

Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and petal width. Plot the data points in a scatter plot with the best fit line shown.

### 9. Calculate the R-squared value

Calculate the R-squared value for your line above.

### 10. Use gradient descent

Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the outputs to your calculations above.