## Switch Case-Control Instruction in Java

The `switch-case` statement is used when we need to choose between multiple alternatives for a given variable.

### Key Features:
1. **Variable Types**: `var` can be an integer, character, or string in Java.
2. **Default Case**: Every `switch-case` should contain a `default` case, which executes if none of the other cases match.
3. **Break Statement**: Always include a `break` statement after each `case` to prevent fall-through to the next case.
4. **Nested Switches**: A `switch` can occur within another `switch`, but this is rarely done in practice.


## Flow Control of Switch Case in Java

The following table describes the flow control of a switch case in Java:

| **Condition** | **Action**                | **Next Step**                                |
|---------------|---------------------------|----------------------------------------------|
| Case 1: False | Evaluate Case 2           | Move to Case 2                              |
| Case 1: True  | Execute Statement 1       | Exit after `break;`                         |
| Case 2: False | Evaluate Case 3           | Move to Case 3                              |
| Case 2: True  | Execute Statement 2       | Exit after `break;`                         |
| Case 3: False | Default Case (if present) | Execute the default statement if applicable |
| Case 3: True  | Execute Statement 3       | Exit after `break;`                         |
| No Case Match | Default Case              | Execute the default statement               |
| End of Switch | Exit                      | Continue with the statement after the switch|

### Notes:
- The switch statement evaluates each case sequentially.
- When a `true` condition is encountered, the corresponding block is executed.
- The `break;` statement terminates the switch execution and moves control outside of the switch.


### Syntax:
```java
switch(var) {
    case C1:
        // Code for case C1
        break;
    case C2:
        // Code for case C2
        break;
    case C3:
        // Code for case C3
        break;
    default:
        // Code for default case
}
