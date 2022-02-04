## Intro to C++ I Lab 06

Calculator

**Date assigned:** 

**Program due:**

**Points:** 

**This is an individual assignment.**

**Goals:**

1.  Use more complicated nested logic

2.  Introduce files

3.  Write small amounts of code and debug


**Lab 6.1**

For this project, you are to write a complete C++ program that
implements a simple calculator. The operators are +, -, \*, and / and
any other operator is invalid. Assume that the user is entering only
integer values and that the output is an integer.

Here is a sample run showing how your program is to work. Notice, if the
user enters an illegal selection, keep asking until a valid selection is
entered. User input is bolded.

<pre>
*** Simple Calculator ***

Select Operator (+, -, \*, /, Q): <b>*</b>

Enter two operands: <b>5 3</b>

5 * 3 = 15

Select Operator (+, -, \*, /, Q): <b>/</b>

Enter two operands: <b>7 3</b>

7 / 3 = 2

Select Operator (+, -, \*, /, Q): <b>%</b>

Select Operator (+, -, \*, /, Q): <b>Q</b>
</pre>

This lab can be solved using a while loop or a do-while loop. You are to
use a do-while loop. Here is pseudo-code to help you with the logic.

<pre>
do {
  get operator
  if operator is +, -, *, / then
    enter two operands
    if operator is + then
      perform addition
    else if operator is - then
      ...
    endif
    output result
  endif
} while (operator is not 'q' or 'Q')
</pre>

**Lab 6.2**

Write a complete C++ program in the project called **Files** that reads
a number of integers from a text file named **numbers.txt**. The
sentinel value is -999. The following example data file has 12 values
and a sentinel value of -999.
<pre>
2 3 5 7 8 10 12 13 15 1 11 15 -999
</pre>

Your program must print out to the screen each integer value (five
values per line right justified in a field of 3). After outputting all
values, output the number of integers read (excluding the sentinel
value), the sum of all numbers, and SORTED if the values are in order
from smallest to largest; otherwise, output NOT SORTED.

HINT: Write and test the code to produce the Count, then the Sum, then
the SORTED portion of the project.

*** Files Are Fun ***
<pre>
 2  3  5  7  8
10 12 13 15  1
11 15

Count: 12
Sum: 102
NOT SORTED
</pre>
Testing: Test your input on these input files.
<pre>
<b>Sample #1</b>

1 2 3 4 5 6 7 8 -999

<b>Sample #2</b>

2 3 5 7 8 10 12 13 15 1 11 15 -999

<b>Sample #3</b>

-999

<b>Sample #4</b>

1 -999
</pre>

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Lab06 Link on The C++ Tutorials in the section Data Input to accept this
        assignment as we've done before. Once accepted, code up a
        complete solution to each project specified above. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic pdf (punetidLab06Calculator.pdf) 
of your program is to be emailed to ryandj@pacificu.edu**
