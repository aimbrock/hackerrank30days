# hackerrank30days
https://www.hackerrank.com/domains/tutorials/30-days-of-code

## Day 0 'Hello World':

Input Format

A single line of text denoting  (the variable whose contents must be printed).

Output Format

Print Hello, World. on the first line, and the contents of  on the second line.

Sample Input

Welcome to 30 Days of Code!
Sample Output

Hello, World. 
Welcome to 30 Days of Code!
Explanation

On the first line, we print the string literal Hello, World.. On the second line, we print the contents of the  variable which, for this sample case, happens to be Welcome to 30 Days of Code!. If you do not print the variable's contents to stdout, you will not pass the hidden test case.

## Day 1 'Data Types':

Objective 
Today, we're discussing data types. Check out the Tutorial tab for learning materials and an instructional video!

Task 
Complete the code in the editor below. The variables i, d, s and  are already declared and initialized for you. You must:

1/ Declare 3  variables: one of type int, one of type double, and one of type String.
2/ Read 3 lines of input from stdin (according to the sequence given in the Input Format section below) and initialize your 3 variables.
3/ Use the + operator to perform the following operations: 
	* Print the sum of i plus your int variable on a new line.
	* Print the sum of d plus your double variable to a scale of one decimal place on a new line.
	* Concatenate s with the string you read as input and print the result on a new line.

	Note: If you are using a language that doesn't support using  for string concatenation (e.g.: C), you can just print one variable immediately following the other on the same line. The string provided in your editor must be printed first, immediately followed by the string you read as input.

Input Format

The first line contains an integer that you must sum with i. 
The second line contains a double that you must sum with d. 
The third line contains a string that you must concatenate with s.

Output Format

Print the sum of both integers on the first line, the sum of both doubles (scaled to 1 decimal place) on the second line, and then the two concatenated strings on the third line.

Sample Input

12
4.0
is the best place to learn and practice coding!

Sample Output

16
8.0
HackerRank is the best place to learn and practice coding!
Explanation

When we sum the integers  4 and 12, we get the integer 16. 
When we sum the floating-point numbers 4.0 and 4.0, we get 8.0. 
When we concatenate 'HackerRank' with 'is the best place to learn and practice coding!', we get 'HackerRank is the best place to learn and practice coding!'.

You will not pass this challenge if you attempt to assign the Sample Case values to your variables instead of following the instructions above and reading input from stdin.

## Day 2 Operators:

Objective 
In this challenge, you'll work with arithmetic operators. Check out the Tutorial tab for learning materials and an instructional video!

Task 
Given the meal price (base cost of a meal), tip percent (the percentage of the meal price being added as tip), and tax percent (the percentage of the meal price being added as tax) for a meal, find and print the meal's total cost.

Note: Be sure to use precise values for your calculations, or you may end up with an incorrectly rounded result!

Sample Input

12.00	// mealCost
20	// tipPercent
8	// taxPercent

Sample Output

15

Calculations:

tip = 12 x (20/100) = 2.4
tax = 12 x (8/100) = 0.96
totalCost = mealCost + tip + tax = 12 + 2.4 + 0.96 = 15.36
round(totalCost = 15 // Round totalCost ot hte nearest dollar (integer) and print out result, 15.

----
