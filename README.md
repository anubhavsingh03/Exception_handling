# Exception_handling
. Eligibility checker- uses exceptions to check a user's age and determine whether they are eligible or when they will be eligible. Algorithm:

Start the program.

Prompt the user to enter their age.

Use a try-catch block to handle exceptions: a. If the entered age is less than or equal to 15: i. Throw an exception with a message "Under Age!". b. If the entered age is between 16 and 17 (exclusive): i. Calculate the number of years required for eligibility (18 - age). ii. Throw an exception with the number of years. c. If none of the above exceptions occur, display "Eligible".

In the catch block for a string exception, catch the exception message "Under Age!" and display it.

In the catch block for an int exception, catch the number of years and display "Account can be created after X years."

End of the program.

B. Division- uses exceptions to handle division by zero. Algorithm for Division by Zero Exception Handling:

Start the program.

Prompt the user to enter the numerator (num) and denominator (dem).

Use a try-catch block to handle exceptions: a. If the denominator (dem) is equal to 0: i. Throw an exception with the message "Division not possible by 0." b. If the denominator is not 0, calculate the result of num / dem.

In the catch block for a string exception, catch the exception message "Division not possible by 0." and display it.

If no exception is thrown, display the result of the division (num / dem).

End of the program.
