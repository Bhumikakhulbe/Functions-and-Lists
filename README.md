Collatz function: 
Firstly a fucntion named "Collatz(number)" is defined with number as a parameter.
Then the if and else conditions are applied to check whether that number is even or odd. 
If the number is even, the function will return number//2 and if the number will be odd the function will return 3*number+1. 
In the main function the number is taken as input from user and the while loop will run until the function is not equal to 1.
Inside the loop the result of the function will be displayed and the result of the function will now be the new value of the number.
This process will run until the function returns 1 and when it does, 1 will be printed and the loop will break. This is the collatz sequence in python

Coin Experiment: 
The random module will be imported as to access the function named 'randint()'.
A for loop is given that will run this code 1000 times.
An empty list will be created inside the loop first and the initial values of the variables will be assigned.
The number of tosses is taken as an input from the user and the next loop will run accordingly. The random values of H and T are generated and appended in the list.
The final list will be printed. 
The loop will now run for all values in the list and the number of heads is counted and if the number of heads will be six times in a row then the streak of heads will be incremented by 1 otherwise the count of Head will again be 0.
The loop will again run for all values in the list and the number of tails will be counted this time and Tail occurs six times in a row the streak of tail will be incremented by 1 otherwise the count of tail will be 0.
After the loop is through all the elements in the list the final answer will be printed and this whole code will run again.
