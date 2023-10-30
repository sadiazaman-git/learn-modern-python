# Learn Modern Python for Data Analysis

## What is Modern Python?


**Modern Python** refers to the current state of Python programming, which incorporates new features and improvements. It aims to make Python code more efficient, readable, and maintainable. Below are the key elements of Modern Python and what's new in it:

### Advantages of Modern Python:

 - **Consistency:** Black ensures uniform code formatting, reducing the need for style-related discussions and improving code readability.
 - **Type Safety:** Mypy and type hinting help catch type-related errors during development, enhancing code robustness.
 - **Data Integrity:** Dataclasses, in combination with immutability, provide better data integrity and make data structures easier to work with.
 - **Data Validation:** Pydantic allows for easy data validation and ensures that data adheres to specified types.
 - **Enumerations:** Enumerations provide a cleaner way to define and use constants in code.

### Key Points

Key Takeaways from the Text:

* Modern Python emphasizes the use of tools like Black, Mypy, and Continuous Integration to improve code quality and maintainability.
* Type hinting allows for gradual adoption of type checking in Python code, enhancing safety and readability.
* Dataclasses simplify the creation of data structures and can be made immutable for data integrity.
* Pydantic offers advanced data validation and coercion capabilities for data structures.
* Python's enumeration support makes it easier to work with named constants.

Overall, Modern Python focuses on improving code quality, readability, and safety through these new features and practices.

[Modern Python: New Features, Better Code](https://www.easypost.com/blog/2022-09-14-modern-python-new-features-better-code)

[Modern Good Practices for Python Development](https://www.stuartellis.name/articles/python-modern-practices/)


# Installation

[Install Anaconda with Python 3.12](https://www.anaconda.com/download) 

[Install VS Code](https://code.visualstudio.com/)

[Install Python Plugin](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

[Read this Document for Reference](https://python.plainenglish.io/typed-python-for-typescript-developers-791145e7171c)

## Commands to Upgrade to Latest Python 3.12 in Anaconda

    conda create --name myenv3_12 python=3.12
    conda env list
    conda activate myenv3_12
    python --version

## Text Books

1. [Python Crash Course 3rd Edition](https://www.amazon.com/Python-Crash-Course-Eric-Matthes/dp/1718502702/ref=sr_1_1)
2. [Chapter 5 of Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter 3rd Edition](https://www.amazon.com/Python-Data-Analysis-Wrangling-Jupyter/dp/109810403X/ref=sr_1_1)


## Learning Material

We will cover Python version 3.12+ with the Latest Features

1. [Chapters 1-10 of Python Crash Course 3rd Edition](https://www.amazon.com/Python-Crash-Course-Eric-Matthes/dp/1718502702/ref=sr_1_1)

    [Additional Resources for Python Crash Course](https://ehmatthes.github.io/pcc_3e/)

    [Google Colaboratory](https://colab.google/)

2. [How to Determine the Type of an Object in Python?](https://itslinuxfoss.com/determine-type-object-python/) 

3. [Python end parameter in print()](https://www.geeksforgeeks.org/gfact-50-python-end-parameter-in-print/)
   
4. [Lambda Function](https://www.geeksforgeeks.org/python-lambda-anonymous-functions-filter-map-reduce/)
5. [Understanding Pass-by-Value vs. Pass-by-Reference and Mutable vs. Immutable in Python](https://www.linkedin.com/pulse/understanding-pass-by-value-vs-pass-by-reference-elhousieny-phd%E1%B4%AC%E1%B4%AE%E1%B4%B0/)
   
6. [*args and **kwargs in Python](https://www.geeksforgeeks.org/args-kwargs-python/)

7. [Typing](https://www.infoworld.com/article/3630372/get-started-with-python-type-hints.html)

    https://peps.python.org/pep-0484/#type-aliases

    [Typing Cheat Sheet](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)

8. Abstract Base Classes (collections.abc)

    https://www.youtube.com/watch?v=oUt1feRoyvI 

    https://docs.python.org/3/library/collections.abc.html 

9. Yield in Python

    https://www.simplilearn.com/tutorials/python-tutorial/yield-in-python 

    https://stackoverflow.com/questions/74774919/proper-typing-for-a-interesting-yield-function 


Example of type hint for a function returning yield i.e. generator function:

First Import:

    from collections.abc import Iterator

Then define the function that returns yield:

    def my_generator()-> Iterator[int]:
        function statements


10. Advanced Classes Topics in Python
    https://www.codingninjas.com/studio/library/how-everything-in-python-is-an-object

* Class Attributes and Methods vs Instance Attributes and Methods in Python

    https://www.tutorialsteacher.com/articles/class-attributes-vs-instance-attributes-in-python

    https://www.digitalocean.com/community/tutorials/python-static-method 

* **Public, Protected, Private Members**

    https://www.tutorialsteacher.com/python/public-private-protected-modifiers

    https://www.linkedin.com/pulse/pythons-access-specifiers-public-protected-private-swarooprani-manoor/ 

* How To Use the __str__() and __repr__() Methods in Python:

    https://www.digitalocean.com/community/tutorials/python-str-repr-functions 

* **Duck Typing:**

    https://ioflood.com/blog/duck-typing/ 

* **Type Statements:**

    https://docs.python.org/3.12/reference/simple_stmts.html#the-type-statement 

* Python's .__call__() Method: Creating Callable Instances:

    https://realpython.com/python-callable-instances/

11. [Chapter 5 of Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter 3rd Edition](https://www.amazon.com/Python-Data-Analysis-Wrangling-Jupyter/dp/109810403X/ref=sr_1_1)
12. [Python in Microsoft Excel Second Editon ](https://www.linkedin.com/posts/financial-modeling-world-cup_python-in-excel-ugcPost-7118239470105075712-5xFJ)

Additional Readings:

https://towardsdatascience.com/python-type-hinting-duck-type-compatibility-and-consistent-with-72e8b348d8ac 

## Projects

[Comprehensive Data Analysis with Pandas](https://www.kaggle.com/code/prashant111/comprehensive-data-analysis-with-pandas)

[Pandas Project: Make a Gradebook With Python & Pandas](https://realpython.com/pandas-project-gradebook/)
