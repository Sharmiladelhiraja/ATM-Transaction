# ATM-Transaction
C Program to Display the ATM Transaction

DESCRIPTION:
This C Program performs ATM transaction. The types of ATM transaction are
*	Balance checking
*  Cash withdrawal
*  Cash deposition.
After getting the pin number from the user, it does the operation requested by the user and if terminates once the operation is done. If the pin number is not valid operations are not performed. First initialize the ATM pin and amount with some random number. Then Take the ATM pin as input. If the input pin is equal to the initialized pin, then do the further operations. Use switch statement to do the operations like Balance checking, Cash withdrawal, Cash deposition etc. Use while loop to terminate or restart the process.	

PROGRAM EXPLANATION:
*	Initialize the variables pin, amount and transaction with 1520, 1000 and ‘y’ respectively.
*	Ask for the pin from user. If the input pin is equal to 1520, then allow for the further operations.
*	Use switch statement to do the operations like Check Balance, Withdraw Cash, Deposit Cash and Quit.
*	For Check Balance simply print the variable amount as output and exit.
*	For cash Withdraw , first ask the amount to withdraw and store it in the variable withdraw.
* If withdraw % 100! = 0, then ask user to enter the amount in multiplies of 100.
*	If withdraw amount is greater than (amount-500), then print the output as “INSUFFICENT BALANCE”.
*	Otherwise subtract the variable withdraw from variable amount, print the amount and exit.
* For deposit operation, ask the user for amount and store it in the variable deposit.
*	Add the variable deposit to variable amount, print the amount and exit.
*	If quit, then finally ask the user if they wish to continue or not. Ask them to type y/n and store it in the variable transaction.
*	If variable transaction is y/Y, then continue the operation. Otherwise terminate the while loop by assigning 1 to variable k.

