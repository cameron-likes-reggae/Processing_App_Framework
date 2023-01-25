# Processing_App_Framework
Makes it easier to create Processing.org Applications with the PyPi processing-py module

Install:
`pip install Processing-Framework-py`


HOW TO USE:
1.  Create a file that has a class with the name of your choosing.
2.  Inside that class add two functions setup() and draw().
    The code within the setup function runs only once at at the start of the program.
    The code within the draw function runs every frame until exited.
3.  in the setup function for example, you can add something like "app = App(400, 400)" 
    to create a canvas object which has the specified width and height dimensions.
4.  There are many functions and variables that can be called as part of the App class.
    For example, code such as "app.background(255)" which will set the background to white.
    (Have a look at https://processing.org/reference for more information about the functions and variables)
5. Finally after your app class call the function Run(x) with x being the name of your class.

[Pypi Link](https://pypi.org/project/Processing-Framework-py)

