Conditions are expressions that evaluate to a boolean expression (true or false). To check conditions, we can use if, if-else, if-elif-else and nested conditionals.

The structure of conditional statements is as follows:

if...then...fi statements
if...then...else...fi statements
if..elif..else..fi
if..then..else..if..then..fi..fi.. (Nested Conditionals)


Syntax

if [[ condition ]]
then
	statement
elif [[ condition ]]; then
	statement 
else
	do this by default
fi


To create meaningful comparisons, we can use AND -a and OR -o as well.

The below statement translates to: If a is greater than 40 and b is less than 6.

if [ $a -gt 40 -a $b -lt 6 ]


Task 
?find the triangle type by reading the lengths of its sides.