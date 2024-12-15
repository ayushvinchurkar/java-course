# Loops in Java

Loops are fundamental constructs in programming languages used to execute a particular statement or set of instructions repeatedly. They make tasks like printing numbers from 1 to 1000 or generating a multiplication table of 7 much easier.

## Why Loops?

Loops allow programmers to automate repetitive tasks by executing a block of code multiple times until a condition is met.

## Types of Loops in Java

In Java, there are primarily three types of loops:

1. **While loop**
2. **Do-while loop**
3. **For loop**

### 1. While Loops

- The **while loop** is used when we need to execute a block of code repeatedly based on a given boolean condition.
- This loop is particularly useful when the exact number of iterations is not known in advance.
- **Important:** If the condition never becomes false, the loop continues to execute indefinitely. Such a loop is called an **infinite loop**.

# While Loop in Java

The following table describes the flow of a **while loop** in Java based on the provided flowchart.

| **Step**                     | **Description**                                                                 |
|------------------------------|-------------------------------------------------------------------------------|
| **Start**                    | The process starts and moves to the initialization expression.                |
| **Initialization Expression**| This sets up the loop variable (e.g., `int i = 0`).                           |
| **Condition**                | Checks whether the condition is `True` or `False`.                            |
| **While Loop Code**          | If the condition is `True`, the block of code inside the loop executes.       |
| **Condition Re-check**       | After executing the loop, the condition is rechecked for the next iteration.  |
| **False Condition**          | If the condition is `False`, the loop terminates, and the program exits.      |
| **Loop Terminates**          | Final step where the loop ends.                                               |

---




# While Loop in Java

The **while loop** in Java is used to execute a block of code repeatedly based on a given condition.

---

## Syntax:
```java
/*
while (Boolean condition)
{
    // Statements -> This keeps executing as long as the condition is true.
}
*/

int i = 10;  
while (i > 0) {  
    System.out.println(i);  
    i--;  
}  

