# Data-Science-Ecosystem1
print("Data Science Tools and Ecosystem")
Data Science Tools and Ecosystem
print(" In this notebook, Data Science Tools and Ecosystem are summarized.")
 In this notebook, Data Science Tools and Ecosystem are summarized.
print("some of the popular languages that Data Scientists use are Python \n1.R\n2.SQL\n3.Java\n4.Julia \n5.Scala \n6.C/C++\n7.JavaScript.")
some of the popular languages that Data Scientists use are Python 
1.R
2.SQL
3.Java
4.Julia 
5.Scala 
6.C/C++
7.JavaScript.
print("Some of the commonly used libraries used by Data Scientists include \n1.TensorFlow\n2.NumPy\n3.SciPy \n4.Pandas\n5.Matplotlib \n6.Keras ")
Some of the commonly used libraries used by Data Scientists include 
1.TensorFlow
2.NumPy
3.SciPy 
4.Pandas
5.Matplotlib 
6.Keras 
 
  Cell In[13], line 3
    | --- | --- | --- |
    ^
SyntaxError: invalid syntax
 x = 40
y = 12
  
add = x + y
sub = x - y
pro = x * y
div = x / y
  
print(add)
print(sub)
print(pro)
print(div)
52
28
480
3.3333333333333335
x=(3*4)+5
print(x)
17
minutes=200
x=minutes/60
print(x)
3.3333333333333335
print("Some of the commonly used libraries used by Data Scientists include \n1.TensorFlow\n2.NumPy\n3.SciPy \n4.Pandas\n5.Matplotlib \n6.Keras ")
Some of the commonly used libraries used by Data Scientists include 
1.TensorFlow
2.NumPy
3.SciPy 
4.Pandas
5.Matplotlib 
6.Keras 
print(" In this notebook, Data Science Tools and Ecosystem are :")
x={"Data colllection","cleaning","analysis","visualization"}
print("some of the popular languages that Data Scientists use are Python")
z={"SQL",".Java","Julia","Scala","C/C++","JavaScript"}
print("Some of the commonly used libraries used by Data Scientists include:")
y = {"TensorFlow","NumPy","SciPy", "Pandas","Matplotlib","Keras"}
   

print(x)
print(z)
print(y)
 In this notebook, Data Science Tools and Ecosystem are :
some of the popular languages that Data Scientists use are Python
Some of the commonly used libraries used by Data Scientists include:
{'cleaning', 'Data colllection', 'visualization', 'analysis'}
{'.Java', 'Julia', 'C/C++', 'Scala', 'JavaScript', 'SQL'}
{'Matplotlib', 'SciPy', 'Keras', 'Pandas', 'NumPy', 'TensorFlow'}
from IPython.display import Markdown, display

markdown_text = " ## Alex Aklson"
display(Markdown(markdown_text))
Alex Aklson
from tabulate import tabulate

# Define your data as a list of lists
data = [
    ["NumPy", "Fundamental package for scientific computing", "[numpy.org](https://numpy.org/)"],
    ["Pandas", "Data analysis and manipulation library", "[pandas.pydata.org](https://pandas.pydata.org/)"],
    ["Matplotlib", "2D plotting library", "[matplotlib.org](https://matplotlib.org/)"],
    # Add more rows as needed
]

# Create the table in Markdown format
table = tabulate(data, headers=["Tool", "Description", "Website"], tablefmt="pipe")

# Print the table
print(table)
| Tool       | Description                                  | Website                                         |
|:-----------|:---------------------------------------------|:------------------------------------------------|
| NumPy      | Fundamental package for scientific computing | [numpy.org](https://numpy.org/)                 |
| Pandas     | Data analysis and manipulation library       | [pandas.pydata.org](https://pandas.pydata.org/) |
| Matplotlib | 2D plotting library                          | [matplotlib.org](https://matplotlib.org/)       |
 
