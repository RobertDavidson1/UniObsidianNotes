- Valid numbers satisfy the following the following sum check, known as **Luhn Algorithm**
	- Starting from the right most digit, add up every other digit
	- Starting from the second digit, multiply every other digit by 2
		- If number > 9, add those two digits to get single digit
			- or mod(9)
	- Add these numbers and the resulit should be $\equiv mod 10$