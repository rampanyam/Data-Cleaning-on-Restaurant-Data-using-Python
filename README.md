# Data-Cleaning-on-Restaurant-Data-using-Python
A data cleaning project intended to remove time discrepancies,  text inconsistencies, in-accurate classification of variables, outlier, and value correction using predictive modelling.  

Programming Language used: Python 3.6.1

Libraries Used
1) Regular Expressions(re) : It is a library used to identify and match a pattern given a sequence of strings. They are frequently used in search engines, text editors and word processors. In this assignment, regular expressions are used to identify,extract and substitute various elements by using regex methods such as re.search(), re.findall() and group().

2) Pandas : This library is used for exploratory data analysis and data manipulation. In this assignment, the Pandas library is used to store the elements in a data frame and convert the data frame into a CSV file by using pandas methods such as pd.DataFrame() and df.to_csv(). Methods such as pd.df.loc[] and pd.df.iloc[] are used to tranverse the dataframe.

3) numpy : numpy is a package used to perform scientific computing with Python. numpy.linalg.solve() method is usef to solve a linear matrix equation, or system of linear scalar equations.

4) datetime.datetime: A datetime object contains all the information from both date object and time object. classmethod datetime.strptime(date_string, format) is used to convert a date string into datetime object with format as ;%H:%M:%S'.

5) networkx: This is a python package used for creation,manipulation, and study of the structure, dynamics, and functions of complex networks. In this assignment, this package is used to create nodes, edges and then find shortest distances between a customer and a restaurant branch.

6) from sklearn import linear_model: LinearRegression() method is used from from linear_model. LinearRegression() class method will take in its fit method arrays X, y.

7)matplotlib.pyplot: This library is used to plot the scatter plot and box plot to check the linearity of the model and outliers respectively on outlier data. Functions such as plt.boxplot(),plt.scatter(),plt.title,plt.xlabel,plt.ylabel and plt.figure are used.


Algorithms Used:

1.) Dijkstra's algorithm is used to correct the shortest path distance from customer to the restaurant ( Value Correction) in this project.
Dijkstra's algorithm , Also known as the Shortest Path First Algorithm is used to find the shortest path from one node of the graph to every other node of the Graph.
For Example : The nodes may represent road networks. The weighted graph consits of Source verticies, Destination Verticies , edges and the weights of the edges.
In this case, the source vertex is the Restaurant Branch Nodes and the Destinatioon vertex is the customer nodes and the weights are the distances in Kilometers from the customer lattiude and longitude.


2.) Also, Dijkstra's Algorithm and Linear Regression Algorithms are used to impute missing values.



