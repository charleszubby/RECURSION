_FOR DECISION.ALGO_
line 2-4
we enter the age and price in an integer.

line 7:
The function reads the user's age by using a series of if-else statements to determine the ticket price based on age ranges:
Age <= 12: Price is set to $10 (child price).
Age <= 17: Price is set to $15 (teenager price).
Age > 17: Price is set to $20 (default adult price).

line 17
The calculated price is displayed.

Line 23-25
we use integer to represent the temprature.
we use Boolean value(TRUE or FALSE) to indicate whether it's raining.

line 27 & 29
The function reads the temperature and raining status.

we recommend clothing using if-else statements:
If it's raining:
For low temperatures (< 10), we recommend a warm coat and umbrella.
For moderate temperatures (< 20), we recommend a jacket and umbrella.
Otherwise, we recommend light clothing and an umbrella.
If it's not raining:
For low temperatures (< 10), we recommend a warm coat.
For moderate temperatures (< 20), we recommend a jacket.
Otherwise, we recommend light clothing.

_RECURSION.algo_
fibonacci sequence
line 2-4
we use an integer to represent the index of the Fibonacci number.

line 7-15
The function uses recursion to calculate the Fibonacci number.
The base cases are defined for n = 0 (result is 0) and n = 1 (result is 1).
For other values of n, the function calls itself recursively with n-1 and n-2 to calculate the sum.

power function
line 20 - 22
we use integer to represent the base and exponent

line 23 - 33
use of function handles different cases for the exponent:
If the exponent is 0, the result is 1 (any number raised to the power of 0).
If the exponent is positive, the function uses recursion to calculate base multiplied by power(base, exponent-1).
The provided implementation optionally handles negative exponents by calculating the inverse of the power for a positive exponent of the absolute value.
Note:
