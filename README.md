
# C++ Decision-Making Statements and Loops

## Aim <br>
To study and implement decision-making statements and loops in C++.<br>

## Software Used<br>
- Visual Studio Code (VS Code)<br>

## Theory<br>

In C++, loops are necessary to run a code block repeatedly. When the number of iterations is known ahead of time, the `for` loop is utilized. It is composed of an initialization, a condition, and an increment/decrement statement. <br>

When the number of iterations isn't preset, the `while` loop is handy because it keeps running as long as its condition holds true. <br>

Similar to the `while` loop, the `do-while` loop ensures that the code block executes at least once before the condition is tested.<br>

Loops improve program functionality by handling repetitive activities efficiently, minimizing the need for unnecessary code. Using loops correctly is essential to developing efficient and well-designed C++ programs.<br>

## Algorithm for loop <br>

1)Start.<br>

2)Initialize a loop counter i to 0.<br>

3)Loop:<br>

  -Repeat the following steps as long as i is less than or equal to 10:<br>
  -Check Condition:<br>
  -If i is equal to 3 or i is equal to 5, perform the following:<br>
  -Skip: Use the continue statement to skip the remaining steps in this iteration and go to the next iteration of the loop (i.e., skip printing i and directly go to incrementing i).<br>
  -If i is not 3 or 5, print the value of i.<br>
  -Increment i by 1.<br>
4)End the Loop when i becomes greater than 10.<br>
5)Stop.<br>

## Algorithm for loop counter <br>
1)Start.<br>

2)Initialize a loop counter i to 1.<br>

3)Loop:<br>

  -Repeat the following steps as long as i is less than or equal to 5:<br>
  -Print "SIT": Output the string "SIT".<br>
  -Increment i by 1.<br>
4)End the Loop when i becomes greater than 5.<br>

5)Stop<br>

## algorithm inerted star <br>

1)Start.<br>

2)Declare three integer variables: n, i, and j.<br>

3)Input:<br>

  -Prompt the user to "Enter your choice:" and store the input in variable n.<br>
4)Outer Loop (for i from 1 to 5):<br>

  -Inner Loop (for j from 5 down to i):<br>
  -Print "* " (a star followed by a space) on the same line.<br>
  -Print a newline character (endl) after the inner loop completes, to move to the next line.<br>
5)End the Outer Loop when i becomes greater than 5.<br>

6)Stop.<br>

## Algorithm for pyramid <br>

1)Start.<br>

2)Declare integer variables: n, i, j, and k.<br>

3)Input:<br>

  -Prompt the user with "Enter your choice: ".<br>
  -Read the user's input and store it in variable n.<br>
  -Set k to the value of n.<br>

4)Outer Loop (for i from 1 to n):<br>

5)Inner Loop (for j from 1 to n):<br>
  -Condition Check:<br>
  -If j is greater than or equal to k:<br>
  -Print "* " (a star followed by a space).<br>
  -Else:<br>
  -Print " " (a space).<br>
  -Decrement k by 1.<br>
  -Print a newline character (\n) after the inner loop completes, to move to the next line.<br>
6)End the Outer Loop when i becomes greater than n.<br>

7)Stop<br>

## conclusion :-<br>
We learnt about loops and their use case <br>



