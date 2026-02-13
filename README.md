README: Experiment 7 - Study of While Loop in Python
Name: RUDRANSH SHARMA

PRN: 25070123096

Aim: Study and implementation of the while loop in Python.

📋 Algorithms
This experiment demonstrates the use of the while loop to solve various computational problems. Below are the formalized step-by-step algorithms for each script.

1. Print Numbers from 1 to NStart.Input: Read the value of $n$ from the user.Initialize: Set $i = 1$.Condition: While $i \le n$, repeat steps 5-6.Display: Print the value of $i$.Increment: Set $i = i + 1$.Stop.2. Factorial of a NumberStart.Input: Read an integer $n$.Initialize: Set fact = 1.Condition: While $n > 0$, repeat steps 5-6.Calculate: Set fact = fact * n.Decrement: Set $n = n - 1$.Display: Print the final value of fact.Stop.3. Fibonacci Series (N Terms)Start.Input: Read the number of terms $n$.Initialize: Set $a = 0, b = 1, i = 1$.Condition: While $i \le n$, repeat steps 5-8.Display: Print the value of $a$.Calculate: Set $c = a + b$.Update: Set $a = b$ and $b = c$.Increment: Set $i = i + 1$.Stop.4. Reverse a NumberStart.Input: Read integer num.Initialize: Set rev = 0.Condition: While num > 0, repeat steps 5-7.Extract: Set digit = num % 10.Reconstruct: Set rev = (rev * 10) + digit.Reduce: Set num = num // 10.Display: Print the value of rev.Stop.5. Check Palindrome NumberStart.Input: Read integer num and store in temp.Process: Follow the Reverse a Number algorithm to find rev.Compare: If temp == rev, display "Palindrome".Else: Display "Not Palindrome".Stop.6. Linear Search in a ListStart.Initialize: Define list nums and read key.Set Pointer: Set index $i = 0$.Condition: While $i < \text{length of nums}$, repeat steps 5-6.Check: If nums[i] == key, display index and break.Increment: Set $i = i + 1$.Else Block: If loop finishes without break, display "element not found".Stop.📝 ConclusionBy completing this experiment, I have effectively applied the while loop to solve iterative problems including mathematical sequences (Fibonacci, Factorial), data manipulation (reversing numbers, counting digits), and searching algorithms. I also demonstrated how to control loop execution using break and continue for optimized performance.
