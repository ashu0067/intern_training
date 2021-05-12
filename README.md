# My Learnings
## I have learnt how to use Some of python libraries like pandas,matplotlib and numpy got Analysing Data. 
### Numpy
Numpy is used to calculating numeric data filled in form of arrays and numpy provide computation speed of C++ code flexiplity of pyhon.
we can import numpy - import numpy as np

### Pandas
Pandas is an open-source, BSD-licensed Python library providing high-performance, easy-to-use data structures and data analysis tools for the Python programming language.
DataFrames in Python are very similar: they come with the Pandas library, and they are defined as two-dimensional labeled data structures with columns of potentially different types.
In general, you could say that the Pandas DataFrame consists of three main components: the data, the index, and the columns.
We can handle rows and colouns of our data using .loc or .iloc method of data object.
import pandas as pd
df = pd.read_csv('file name'.csv)

### Matplotlib
Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy. As such, it offers a viable open source alternative to MATLAB. Developers can also use matplotlib's APIs (Application Programming Interfaces) to embed plots in GUI applications.
Pandas is a library used by matplotlib mainly for data manipulation and analysis. Pandas provides an in-memory 2D data table object called a Dataframe. Unlike numpy, pandas is not a required dependency of matplotlib.
import matplotlib.pyplot as plt
# Plot some numbers:
plt.plot([1, 2, 3]) 
plt.title(”Line Plot”) 
# Display the plot:
plt.show()
