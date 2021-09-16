# Testing a legacy program and reporting on testing results
## Author
Jose J. Cruz

## Description
Sometimes you will be given a program that someone else has written, and you will be asked to fix, update and enhance that program.   In this assignment you will start with an existing implementation of the classify triangle program that will be given to you.   You will also be given a starter test program that tests the classify triangle program, but those tests are not complete.  

These are the two files:  
- **Triangle.py**:  is a starter implementation of the triangle classification program
- **TestTriangle.py**: Contains a starter set of unittest test cases to test the classifyTriangle() function in the file Triangle.py file
 
In order to determine if the program is correctly implemented, you will need to update the set of test cases in the test program.  You will need to update the test program until you feel that your tests adequately test all of the conditions.   Then you should run the complete set of tests against the original triangle program to see how correct the triangle program is.    Capture and then report on those results in a formal test report described below.   For this first part you should not make any changes to the classify triangle program.  You should only change the test program.

Based on the results of your initial tests, you will then update the classify triangle program to fix all defects.  Continue to run the test cases as you fix defects until all of the defects have been fixed.   Run one final execution of the test program and capture and then report on those results in a formal test report described below.   

Note that you should NOT simply replace the logic with your logic from Assignment 1.  Test teams typically don't have the luxury of rewriting code from scratch and instead must fix what's delivered to the test team.   

```
Triangle.py contains an implementation of the classifyTriangle() function with a few bugs.  

TestTriangle.py contains the initial set of test cases
```

## Summary
I created 20 Tests in total, I test happy paths and also enforce sad paths to make sure that if it breaks it returns the correct type of error.

_What did you learn?_ That personally if a bug is produced because the code is too entangle I would rewrite the entire thing to pay off the technical debt right away. (Personal preference)

## Honor Pledge
```
The pledge signifies that the work submitted by a student is indeed his/her own. There is one designated pledge to be used for tests, homework assignments, lab reports, and computer projects. The pledge shall be written in full and signed by the student on all submitted academic work. Any references used (including texts, tutors, classmates, etc.) should be listed below the written pledge.


"I pledge my honor that I have abided by the Stevens Honor System."
```

## Detail Results
I use unit testing to try to find the bug
1. I test to make sure to throw errors in case the function do not receive all the arguments, 
2. I test to make sure that all the inputs are the datatype I expected
3. Review if with the information send the triangle es a valid triangle
4. The last thing I did is actually test what type of triangle

There are two constraints I did for my self:
1. Make sure the same code style as the previous version
2. Try to use less lines of code 

I test with multiple datatypes to make sure that the exceptions were raised. 

