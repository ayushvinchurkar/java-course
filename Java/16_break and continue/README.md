# Break Statement in Java

The `break` statement is used to exit a loop irrespective of whether the condition is `true` or `false`.  
Whenever a `break` is encountered inside the loop, the control is sent **outside** the loop.


# Flowchart Representation of `break` Statement

| **Step**                           | **Description**                              |
|------------------------------------|----------------------------------------------|
| **Start**                          | The program or loop begins execution.        |
| **Loop condition**                 | Check if the loop condition is `True` or `False`. |
| **True (Condition met)**           | If the condition is `True`, proceed inside the loop. |
| **Break?**                         | Check if the `break` statement is triggered. |
| **True (Break encountered)**       | Exit the loop immediately.                   |
| **False (Break not encountered)**  | Execute the code inside the loop body.       |
| **Exit loop**                      | After the loop is exited, control is passed to the next statement outside the loop. |



# Continue Statement in Java

The `continue` statement is used to immediately move to the next iteration of the loop.  
The control is taken to the next iteration, thus skipping everything below `continue` inside the loop for that iteration.

## Flowchart Representation of `continue` Statement

| **Step**                           | **Description**                                                      |
|------------------------------------|----------------------------------------------------------------------|
| **Start**                          | The program or loop begins execution.                                |
| **Loop condition**                 | Check if the loop condition is `True` or `False`.                    |
| **True (Condition met)**           | If the condition is `True`, proceed inside the loop.                 |
| **Continue?**                      | Check if the `continue` statement is triggered.                       |
| **True (Continue encountered)**    | Skip the remaining code in the current iteration and move to the next iteration. |
| **False (Continue not encountered)**| Execute the code inside the loop body.                               |
| **Exit loop**                      | After the loop is exited, control is passed to the next statement outside the loop. |


## In a Nutshell …

- The `break` statement completely exits the loop.
- The `continue` statement skips the particular iteration of the loop.


## Break and Continue Statements in Java

### Break Statement

The `break` statement is used to completely exit the loop.

#### Syntax and Example:

```java
// Syntax:
break;

// Example to demonstrate the use of `break` inside a `for` loop:
public class CWH_break {  
    public static void main(String[] args) {  
        // Using for loop  
        for(int i = 10; i > 0; i--) {  
            if(i == 7) {  
                break;   // Break the loop
            }  
            System.out.println(i);  
        }  
    }  
}


// Syntax:
continue;

// Example to demonstrate the use of `continue` statement inside a `for` loop:
public class CWH_continue {  
    public static void main(String[] args) {  
        for(int i = 7; i > 0; i--) {  
            if(i == 3) {  
                continue;  // Continue skips the rest of the statement
            }  
            System.out.println(i);  
        }  
    }  
}
