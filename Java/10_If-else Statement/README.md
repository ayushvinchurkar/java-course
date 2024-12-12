# **If-Else Statements in Java**

Decision-making is a fundamental concept in programming. In Java, **if-else statements** allow you to execute specific blocks of code based on conditions. They help implement flow control in a program based on certain criteria.

---

## **Overview**

### **Decision-Making in Java**
Java provides multiple decision-making constructs:
1. **If-Else Statement**
2. **Switch Statement**

This repository focuses on explaining **If-Else Statements**, including their syntax, flow control, and examples.

---
## **Flow Control of If-Else in Java**

The following table represents the flow of an **if-else** statement:

| **Step**              | **Action**                                | **Next Step**                                  |
|-----------------------|-------------------------------------------|-----------------------------------------------|
| **1. Start**          | Program starts                           | Evaluate the condition                        |
| **2. Condition**      | Check if the condition is true or false  | If **True**, go to Step 3; If **False**, Step 4 |
| **3. If Block**       | Execute code inside the **if block**     | Go to Step 5 (Remaining code)                 |
| **4. Else Block**     | Execute code inside the **else block**   | Go to Step 5 (Remaining code)                 |
| **5. Remaining Code** | Continue executing the remaining code    | End                                           |
| **6. End**            | Program execution ends                   |                                               |

This table captures the same flow as the visual diagram. Let me know if you need further adjustments!


---

## **If-Else Ladder in Java**

An **If-Else Ladder** is used when we need to check multiple conditions. Instead of using multiple `if` statements, we can use `else if` along with `if`, forming an **if-else-if-else ladder**. This approach helps in reducing code indentation and improves readability.

### **Syntax**

```java
if (condition1) {
    // Statements for condition1
} else if (condition2) {
    // Statements for condition2
} else if (condition3) {
    // Statements for condition3
} else {
    // Statements if all conditions fail
}


### **Syntax**
```java
if (condition) {
    // Code to execute if condition is true
} else {
    // Code to execute if condition is false
}
