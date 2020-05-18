# PythonBasics-ReadingFiles
In this tutorial, I tech how we can read the files in Jupyter Notebook

Reading and Writing Files in Python
Overview

When you’re working with Python, you don’t need to import a library in order to read and write files. It’s handled natively in the language, albeit in a unique manner.

The first thing you’ll need to do is use Python’s built-in open function to get a file object.

The open function opens a file. It’s simple.

When you use the open function, it returns something called a file object. File objects contain methods and attributes that can be used to collect information about the file you opened. They can also be used to manipulate said file.

For example, the mode attribute of a file object tells you which mode a file was opened in. And the name attribute tells you the name of the file that the file object has opened.

You must understand that a file and file object are two wholly separate – yet related – things.
 
File Types

What you may know as a file is slightly different in Python. 

In Windows, for example, a file can be any item manipulated, edited or created by the user/OS. That means files can be images, text documents, executables, and much more. Most files are organized by keeping them in individual folders. 


In Python, a file is categorized as either text or binary, and the difference between the two file types is important. 

Text files are structured as a sequence of lines, where each line includes a sequence of characters. This is what you know as code or syntax. 

Each line is terminated with a special character, called the EOL or End of Line character. There are several types, but the most common is the comma {,} or newline character. It ends the current line and tells the interpreter a new one has begun. 

A backslash character can also be used, and it tells the interpreter that the next character – following the slash – should be treated as a new line. This character is useful when you don’t want to start a new line in the text itself but in the code. 

A binary file is any type of file that is not a text file. Because of their nature, binary files can only be processed by an application that know or understand the file’s structure. In other words, they must be applications that can read and interpret binary.


Open ( ) Function

In order to open a file for writing or use in Python, you must rely on the built-in open () function. 

As explained above, open ( ) will return a file object, so it is most commonly used with two arguments.  

An argument is nothing more than a value that has been provided to a function, which is relayed when you call it. So, for instance, if we declare the name of a file as “Test File,” that name would be considered an argument. 
Reference: https://www.pythonforbeginners.com/files/reading-and-writing-files-in-python
