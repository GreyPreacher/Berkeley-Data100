# Berkeley-Data100
This is UC Berkeley Data100 fa21 by GreyPreacher(Alvin Zhang).  
The official website of the course is https://ds100.org/fa21/.

# Resource
All course resources can be found at https://ds100.org/fa21/.  
The textbook is at https://www.textbook.ds100.org/intro.html.

# Attention About Lab and Homework
For some reason the test files(e.g. q1a.py) need *OK_FORMAT = True* in the first line. You may need to add this by shell command. For me, I use bash command like  
  
    #! /bin/bash  
    sed '1i OK_FORMAT = True' *.py -i  

to fix the problem
