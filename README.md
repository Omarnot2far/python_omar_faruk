# Advanced Python: Data analysis and machine learning @ stepbystepcompetence.se

The course covers the use of Python libraries such as Pandas, NumPy and Matplotlib in 5 weeks.

# Week-1: 

# Learning Jupyter Notebook, Python concepts and Git & Github

1: **Anaconda**: A platform of data science where all the tools are included. Learned about Installation.

2: **Jupyter Notebook**: Jupiter Notebook is a webbased environment which can be found in Anaconda Platform where you write Python code and execute.
  
Some Basic Python concepts @ basic_python file:

- Variables store data
    
- Lists are mutable, ordered collections
    
- Tuples are immutable, ordered collections

- Dictionaries store key-value pairs
    
- Sets contain unique, unordered elements
    
- For loops iterate over collections
    
- Functions define reusable code blocks
    
- If statements control program flow based on conditions

3. **Git & Github**: Git is a version control system that helps developers track changes in their code over time. GitHub is a web-based platform that uses Git. It's like a social network for code. Included a file **git Cheatsheet**


# week 2

# Learning NumPy and OpenCV (cv2)

This project demonstrates basic image processing techniques using NumPy and OpenCV in Python. Here's what we've learned:

## Libraries Used
- **NumPy**: For numerical operations and array manipulation.
- **Matplotlib**: For creating visualizations of our images.
- **OpenCV (cv2)**: For advanced image processing tasks.
- **urllib**: For fetching images from URLs.

## Key Concepts Learned

1. **Image Retrieval**: 
   - Fetching images from URLs using `urllib`.
   - Converting byte data to NumPy arrays.

2. **Image Representation**:
   - Understanding images as 3D NumPy arrays (height, width, color channels).
   - Converting between BGR and RGB color spaces.

3. **Image Manipulation**:
   - Resizing images using cv2.resize().
   - Accessing image dimensions and pixel values.
   - Modifying specific pixel values based on conditions.

4. **Array Operations**:
   - Copying arrays to avoid modifying original data.
   - Reshaping arrays (flattening a 2D image to 1D).

5. **Visualization**:
   - Using Matplotlib to display images.

## Code Highlights

- Created a function to fetch and process images from URLs.
- Implemented a function to resize images and extract dimensions.
- Demonstrated pixel manipulation.
- Showed how to flatten image array.

## Future Learning Directions

- OpenCV functions for image processing.
- image filtering and edge detection algorithms.
- image segmentation and object detection.
- computer vision tasks

# week 3

# Learning Panda
Panda is a python library for data analysis and especially for working with large data sets. 
Built-in functions enable data manipulation, visualization and preprocessing. Excellent tool for handling file formats such as .csv or XML

## Data type

- Nominal (Football player numbers, colors. No order and no clear difference between them, least informative)
- Ordinal (Position in a race, rating of a movie. Can be ordered but no clear measurement of distance between them)
- Range (pH, the clock. There is order and spacing between the values. The difference between two values ​​is important)
- Quotient (Kelvin, number of children. Very similar range but with the addition of an absolute zero point)

## Data Cleaning
- Are there NaN values? (empty columns, rows)
- Are there any major outliers? (do they seem reasonable?)
- Are there the wrong data types in the wrong places? (among a column of integers there is, for example, a date)
- Duplicate

## Data Statistics 
- Count: Number of data points for each feature.
- Mean: The average value for each feature.
- Standard Deviation (std): It measures the variability or spread in the data.
- Min: The minimum value observed for each feature.
- 25% (First Quartile): 25% of the data falls below this value.
- 50% (Median): 50% of the data falls below this value.
- 75% (Third Quartile): 75% of the data falls below this value.
- Max: The maximum value observed for each feature.

## The 5-number summary

It is a statistical tool for understanding data distribution and identifying outliers. It consists of five key values,

1. the minimum (smallest data point),
2. the first quartile 25% (Q1),
3. the median 50% (Q2 or the second quartile),
4. the third quartile 75% (Q3), and
5. the maximum (largest data point).


## To detect outliers

we focus on the interquartile range (IQR)

calculated as: 

**IQR = Q3 - Q1** (This IQR represents the middle 50% of the data)

Outliers are identified as values that fall significantly lower fence and higher fence.

**Lower fence = Q1 - 1.5 * IQR**

**Higher fence = Q3 + 1.5 * IQR**

Essentially, the 5-number summary with IQR helps us pinpoint unusual data points that might deviate from the overall pattern and warrant closer investigation.


# week 4

# Learning Object-Oriented Programming (OOP) in Python

Object-Oriented Programming (OOP) is a programming centered around the concept of objects. Objects are instances of classes that represent real-world entities with attributes (data) and behaviors (methods). OOP helps make your code more organized, modular, and reusable.

# Why OOP?
- Modularity: Organizes code into smaller, manageable sections.
- Reusability: Encourages the reuse of code via inheritance and polymorphism.
- Encapsulation: Hides complex details and exposes only necessary parts of the object.
- Maintainability: Makes it easier to maintain and extend code over time.

# The key concepts of Object-Oriented Programming (OOP) in Python: 

- Classes and Objects
- Attributes and Methods
- The Constructor (__init__)
- The self parameter
- Encapsulation
- Class and Static Methods
- Inheritance

# Classes and Objects
A class is a blueprint for creating objects (instances). It defines attributes and methods that the objects will have.

An object is an instance of a class. Think of a class as the blueprint for a car, and the object as an actual car built from that blueprint.

# Attributes (Variables)
Attributes are variables that store data related to the object. In OOP, we define attributes inside the class and they belong to the objects created from the class.

# Methods
Methods are functions defined inside a class. They describe behaviors or actions that objects of the class can perform.

# The Constructor: __init__()
The constructor is a special method called __init__() that is automatically executed when a new object is created. The constructor is used to initialize an object’s attributes.

# The self Parameter
The self parameter refers to the current instance of the class and is used to access instance attributes and methods.

# Encapsulation (Public vs Private)
Encapsulation is the process of restricting access to certain attributes or methods and exposing only what's necessary. In Python, attributes are public by default, but we can make them private using a double underscore (__).

# Class and Static Methods
There are two types of methods apart from instance methods:

- Class Methods: Use the @classmethod decorator and take cls (the class) as their first argument.
- Static Methods: Use the @staticmethod decorator and don’t require access to the class or object.

# Inheritance
Inheritance allows a class (child class) to inherit attributes and methods from another class (parent class), promoting code reuse.


# week 5

# Learning Ploting the Data useing Matplotlib Library
