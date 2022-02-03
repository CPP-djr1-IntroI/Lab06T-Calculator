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

2 3 5 7 8 10 12 13 15 1 11 15 -999

Your program must print out to the screen each integer value (five
values per line right justified in a field of 3). After outputting all
values, output the number of integers read (excluding the sentinel
value), the sum of all numbers, and SORTED if the values are in order
from smallest to largest; otherwise, output NOT SORTED.\
\
HINT: Write and test the code to produce the Count, then the Sum, then
the SORTED portion of the project.

\*\*\* Files Are Fun \*\*\*

2 3 5 7 8

10 12 13 15 1

11 15

Count: 12

Sum: 102

NOT SORTED

Testing: Test your input on these input files.

**Sample #1**

1 2 3 4 5 6 7 8 -999

**Sample #2**

2 3 5 7 8 10 12 13 15 1 11 15 -999

**Sample #3**

-999

**Sample #4**

1 -999

**[Show the instructor or TA your solution]{.ul}**

1.  Your program is to compile without any errors or warnings.

2.  Do not use any magic constants in your program.

3.  Make sure your editor guideline is set to column 72 and that no
    > characters go past that column.

4.  Commit and push your solutions regularly. Remember, your final
    > solutions are due by this **Friday at 5PM.**
