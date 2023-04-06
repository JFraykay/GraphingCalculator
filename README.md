# GraphingCalculator
""" 
The Graphing Calculator is primarily for graphing calculations.For instance, one thing you can do is solve for y for the slope-intercept form equation; not only will it solve for y but it will graph the line you've created as well. It is supposed to visually aid those who wish to understand math. I was going to continue the project further but there are so many fantastic graphing and formula sites already such as symbolab.
Note:  A normal calculator is better for quick successive basic arithmetic, this is not.

For this project I used Jupyter Notebook which comes pre-loaded with all necessary data analysis and data science libraries. There are so many resources out there that it is hard to choose.

The code for the calculator can definitely be reduced and more concise, but I don't plan on updating it, although I will  add this to my website for an easier user experience once I import Jupyter to my server and figure out how to keep the back end communicating and send commands to the notebook as well as returning them to front end.

In order to make this work you must first download Jupyter Notebook (which runs on your local machine) and then use my code. If you're unfamiliar with Python I made a class for each type of formula. Some functions in the class require more parameters or attributes than others. For instance, in the Areas class only Square requires one dimension while the others requires two. If you are lost I will show you an example below. For a more complex class like Graphs I had to allow many parameters for integrals, so if you wanted to only use Line (slope intercept formula) it is reccommended you define a through g, although you can always make the others None if you don't wish to use Integral.

You can ignore the functions before the classes, they are used to hold the formulas to calculate each instance and the method of graphing that object, although some are more intricate than others.

A quick run through for classes:
Arithmetic is your basic calculations although not necessarily useful especially since it doesn't graph anything.
Areas calculates your total area of a 2d shape.
Volumes calculates your total volume of a 3d shape.
Triginometry provides simple trig equations, this is a pretty lackluster class.
Graph provides mainly algebraic formulas (aside from Integrals) and their paths.

## How to Use
For those who don't know Jupyter you must run all the cells first in order (similar to Google Collab).
In a new cell we'll use Areas as an example, and we'll find the area of a Square:
  First we'll make an object from our class as well as define the parameters:
    area = Areas(2, 4)
   And now we have our object using 2 for our first input and 4 for our second input (which is useless for Square)
   So now we call the square function:
    area.square()
   And our answer is 4
   You can also set Areas second parameter to None if you're only using Square but that is not encouraged
   
"""
