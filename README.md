

<p align="center">
  <img src="https://github.com/hocuf/vissuAlize/assets/92105996/d1c0eb1f-a3b3-47c4-ba2d-e6595002aff2" width="300" />
</p>


# vissuAlize 

<p align="center">
  <img src="https://github.com/hocuf/vissuAlize/assets/92105996/86e099c8-d531-4cf0-ab54-d3c9078cb1a0" width="200" />
  <img src="https://github.com/hocuf/vissuAlize/assets/92105996/58dc5561-818d-4887-9d79-684735753d48" width="200" /> 
</p>






`vissuAlize` is a Python visualization library that provides a high-level interface for drawing attractive and informative statistical graphics. It is built on top of Matplotlib and Seaborn and offers a variety of chart types that can be created with minimal code.

## Installation

Install `vissuAlize` using pip:

```sh
pip install vissuAlize
```

## dir()

The `dir()` function lists all properties and methods that an object has. For example, to see all the functions and properties your vissuAlize module has, you can use it as follows:



<p align="left">
  <img src="https://github.com/hocuf/vissuAlize/assets/92105996/b2c060e2-feb2-4d93-ad6c-8f402bcca514" width="200" />
</p>


## help()

The `help()` function provides detailed information about an object, module or function in Python. It is useful for explaining to the user what the object does, how to use it, and what its methods are.

<p align="left">
  <img src="https://github.com/hocuf/vissuAlize/assets/92105996/9cfbf667-adf3-4160-ac5d-140a8e7818a0" width="600" />
</p>

## Quick Start

To create a bar chart with `vissuAlize`, simply import the library and use the `bar` method. You can customize your chart with various parameters such as `title`, `xlabel`, `ylabel`, `figsize`, and `color`. Here's an example:

```python
from vissuAlize import vissuAlize


# Create data for the chart
categories = ['Category 1', 'Category 2', 'Category 3']
values = [10, 20, 15]

# Generate the bar chart
vissuAlize.bar(x=categories, y=values, title='Sample Bar Chart', xlabel='Categories', ylabel='Values', figsize=(8, 6), color='maroon')
```

<img src="https://github.com/hocuf/vissuAlize/assets/92105996/bb95245a-ea92-4401-a4f5-206f88538394" width="400" />

## Scatter Plot Example

```python
# Sample data for scatter plot
x_values = [5, 20, 40, 60, 80]
y_values = [25, 45, 65, 85, 105]

# Generating the scatter plot
vissuAlize.scatter(x=x_values, y=y_values, title='Scatter Plot Example', xlabel='X Axis', ylabel='Y Axis', figsize=(10, 6), color='green', marker='x')
```


<img src="https://github.com/hocuf/vissuAlize/assets/92105996/b4b81109-6df6-4ee5-b4d8-4571569584b6" width="400" />



## Line Plot Example
```python


# Time series data
months = ['Jan', 'Feb', 'Mar', 'Apr', 'May']
revenue = [10000, 15000, 12000, 17000, 14000]

# Generating the line plot
vissuAlize.lineplot(x=months, y=revenue, title='Monthly Revenue', xlabel='Month', ylabel='Revenue', figsize=(10, 6), color='red', linestyle='--', linewidth=2)



```
<img src="https://github.com/hocuf/vissuAlize/assets/92105996/99a2fb8d-0298-4276-b65f-9187f7cad7d1" width="400" />


## Histogram Example
```python

# Sample data for histogram
data = [22, 87, 5, 43, 56, 73, 55, 54, 11, 20, 51, 5, 79, 31, 27]

# Generating the histogram
vissuAlize.histogram(data=data, bins=8, title='Sample Histogram', xlabel='Value', ylabel='Frequency', figsize=(10, 6), color='purple')

```
<img src="https://github.com/hocuf/vissuAlize/assets/92105996/e396cd7f-225e-4b4f-a6b1-c273711def28" width="400" />




## Acknowledgements

This project, vissuAlize, has been developed to provide an easy and intuitive way to visualize data in Python. It stands on the shoulders of giants by utilizing the powerful visualization capabilities provided by matplotlib and seaborn. We are thankful to the developers and contributors of these libraries for making data visualization accessible and effective.

matplotlib: A plotting library for the Python programming language and its numerical mathematics extension NumPy. Matplotlib
seaborn: A Python data visualization library based on matplotlib that provides a high-level interface for drawing attractive statistical graphics. Seaborn
