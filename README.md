# arrays and matrices
##abstract
arrays are used to store multiple values in a single variable,instead of declaring sepaate values of each variable
these codes basically comprise of:
sum of array by iterating each element of the array and adding it to a variable called sum.
entering marks using array
key found or not found at location
sum of matrices
formation of matrix
transpose of a matrix

##algorithm of the codes

Here is the algorithm for the given C++ code:

              algorithm for key not found or found
Include the necessary header file for input and output, i.e., <iostream>.
Declare the main() function. In modern C++, it should be declared as int main(), but this code uses the older style.
Declare integer variables key and i.
Create an integer array marks of size 10 and initialize it with some values.
Output the message "enter the number" to prompt the user to enter a key value.
Read the value entered by the user into the variable key using cin.
Start a for loop with the loop variable i initialized to 0 and continue while i is less than 10.
Inside the loop, check if the current element marks[i] is equal to the key.
a. If they are equal, output the message "key found at location" followed by the value of i, and then break out of the loop.
After the loop, check if the loop variable i has reached the value 10.
a. If it has, output the message "key not found at location 10". Note that there is a semicolon (;) after the if statement, which is incorrect and should be removed to avoid any syntax errors.
End the main() function.

              algorithm for sum of array
Include the necessary header file for input and output, i.e., <iostream>.
Declare the main() function with a return type of int.
Declare integer variable n for the number of integers and double variables sum and average.
Prompt the user for the number of integers and store it in n.
Declare an integer array arr of size n.
Use a for loop to read n integers from the user into arr and calculate the sum as you go.
Calculate the average by dividing the sum by n.
Output the sum and average of the elements.
End the main() function and return 0 to indicate successful program execution

          algorithm for displaying marks
Include the necessary header file for input and output, i.e., <iostream>.
Declare the main() function with a return type of int.
Declare an integer array marks with a size of 5 to store the marks.
Output a message to instruct the user to enter 5 marks.
Use a for loop to read 5 marks from the user and store them in the marks array.
Output the message "the marks are:" to inform the user about the following display.
Use another for loop to display the entered marks, separated by spaces.
End the main() function and return 0 to indicate successful program execution.

          algorithm for formation of a matrix
Declare a 2x3 integer array A.
Declare integer variables i and j.
Display the message "array input."
Use nested loops to input values into the array A:
Loop i from 0 to 1.
Loop j from 0 to 2.
Read an integer and store it in A[i][j].
Use nested loops to display the elements of the array A:
Loop i from 0 to 1.
Loop j from 0 to 2.
Display the value of A[i][j]

       algorithm for sum of a matrix
Declare three 3x3 integer arrays: matA, matB, and matC.
Declare integer variables i and j.
Display "Enter Elements of First Matrix."
Use nested loops to input values into matA:
Loop i from 0 to 2.
Loop j from 0 to 2.
Read an integer and store it in matA[i][j].
Display "Enter Elements of Second Matrix."
Use nested loops to input values into matB in the same way as with matA.
Display "sum of matrices."
Use nested loops to calculate the sum of the two matrices and store the result in matC:
Loop i from 0 to 2.
Loop j from 0 to 2.
Calculate matC[i][j] as the sum of matA[i][j] and matB[i][j].
Display "Result of Two Given Matrix is:".
Use nested loops to print the elements of matC:
Loop i from 0 to 2.
Loop j from 0 to 2.
Display the value of matC[i][j] followed by a space.
Print a newline to move to the next row.
Return 0 to indicate successful program execution.

       algorithm of transpose of a matrix
Declare a 3x3 integer array mat and matT for the transpose, and integer variables i and j.
Input values into mat.
Display the original matrix mat.
Calculate the transpose and store it in matT.
Display the transpose matrix matT.
Return 0 to indicate successful program execution.

