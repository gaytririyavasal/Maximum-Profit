
PROJECT DESCRIPTION AND GUIDELINES PROVIDED ON ASSIGNMENT INSTRUCTIONS

An investor wants to invest a specific amount in real estate. He wants to purchase as much as he has money
and likes to get maximum profit when he sells the houses next year. Each house is in located in a different
city district and has a different 1-year forecasted value increase. He can only select from the listed houses
to buy.

For example, he wants to invest 10 million dollars and he can select properties from a list of 4 houses in
4 Austin’s districts.

Houses 						1. N. Austin 		2. 	S. Austin 		3. E. Austin 		4. Rainy St.
House Values in Millions 				3.1 			2.3 				4.5 			3.6
1-year forecasted value increase in percent % 	12 			6 				1 			9

Table 1: List of Houses prices and 1-year forecasted value increase for the next year.

Input:

Input is a follow like following text file to read from standard input.

10
4
3 , 2 , 4 , 5
1 2 , 6 , 1 , 9

• The first line is the amount of investment in million USD which is an integer number.

• The second line includes an integer number which is the number of houses listed for sale.

• The third line is a list of house prices in million dollar which is a list of integer numbers (Consider that house prices can be an integer number in million dollar only).

• The fourth line is a list of 1-year forecasted value increase for each of the listed houses in percent.

Output:

Your output is a single float number with 2 decimal points only which is the maximum possible profit by purchasing a subset of the listed houses and selling them the next year.

0.93

3 ×0.12 + 2 ×0.06 + 5 ×0.09 = 0.93

Your implementation file should be named maximum profit.py
