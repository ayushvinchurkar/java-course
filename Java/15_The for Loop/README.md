# Java `for` Loop

The `for` loop in Java is used to iterate a block of code multiple times.  
Use a `for` loop only when the exact number of iterations needed is already known to you.

## Components of a `for` Loop

1. **Initializer**: Initializes the value of a variable. This part is executed only once at the beginning of the loop.
2. **Condition (`check_bool_expression`)**: The code inside the `for` loop is executed only when this condition evaluates to `true`.
3. **Update**: Updates the value of the variable initialized in the loop, typically at the end of each iteration.

---


# Flow of a `for` Loop

The flow of a `for` loop can be understood using the following steps:

| Step                          | Description                                                                                   |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| **Start**                     | The loop starts execution.                                                                    |
| **Initialization Expression** | Initializes the loop variable. This step is executed only once at the beginning of the loop.  |
| **Condition**                 | Checks the condition. If `true`, the loop proceeds to execute the loop body. If `false`, the loop terminates. |
| **For Loop Body**             | Executes the code inside the loop body.                                                      |
| **Update Expression**         | Updates the loop variable (e.g., increment or decrement).                                     |
| **Repeat**                    | Goes back to check the condition. If the condition is still `true`, the loop continues; otherwise, it terminates. |
| **Terminate**                 | The loop ends when the condition becomes `false`.                                            |

This table represents the sequence of execution and conditions for a `for` loop in Java.



## Syntax:

```java
/* for (initialize; check_bool_expression; update) {

            // code;

} */

## Example

```java
for (int i = 7; i != 0; i--) {
    System.out.println(i);
}

