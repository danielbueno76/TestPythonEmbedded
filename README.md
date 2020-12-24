# Test for Cython in Embedded Python

We open the file .py and execute the content through c++. The goal here is to generate an executable file. 

In my experience I have created GUI application in Python and in order to not use the interpreter, I have used Pyinstaller to generate an exe file, but it creates a file too large.

So in order to  use a small exe file, I have created this test.

Be careful: The exe file and the py file must be in the same path.

I have created two files: helloworld.pyx contains a print function and main.py contains cython to call the helloworld module. In order to work I have created a file [setup.py](https://cython.readthedocs.io/en/latest/src/tutorial/cython_tutorial.html#cython-hello-world) and execute in the interpreter **python setup.py install** to install the package


Acknowledge to :
[Tutorial Embedded Python](https://www.codeproject.com/Articles/820116/Embedding-Python-program-in-a-C-Cplusplus-code)
[Tutorial Cython](https://cython.readthedocs.io/en/latest/)
