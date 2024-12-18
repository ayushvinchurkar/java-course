## Do-while Loop

The **do-while loop** is similar to a `while` loop except for the fact that it is **guaranteed to execute at least once**.

- Use a `do-while` loop when the **exact number of iterations is unknown**, but you need to **execute a code block at least once**.
- After executing a part of a program **once**, the rest of the code gets executed based on the given **boolean condition**.

---

## Difference Between `while` Loop and `do-while` Loop

- **`while` Loop:**
  - The condition is checked before the code is executed.
  - If the condition is false initially, the code inside the loop will not execute.

- **`do-while` Loop:**
  - The code inside the loop is executed at least once, even if the condition is false.
  - The condition is checked after executing the code.

### Example:

#### `do-while` Loop:
```java
int i=1;  
do{  
System.out.println(i);  
i++;  
}while(i<=10); 

### **Syntax**

```java
/* do {

     // code

} while (condition);  // Note this semicolon */
