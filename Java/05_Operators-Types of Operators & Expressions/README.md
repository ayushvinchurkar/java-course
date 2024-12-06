# Operators in Java

Operators in Java are symbols used to perform operations on variables and values. These operations can be arithmetic, logical, relational, or bitwise.

---

## Types of Operators

### 1. **Arithmetic Operators**
Arithmetic operators are used for basic mathematical calculations like addition, subtraction, etc.

| Operator | Description                          | Example (x=7, y=2) | Result  |
|----------|--------------------------------------|---------------------|---------|
| `+`      | Addition                             | `x + y`             | `9`     |
| `-`      | Subtraction                          | `x - y`             | `5`     |
| `*`      | Multiplication                       | `x * y`             | `14`    |
| `/`      | Division                             | `x / y`             | `3`     |
| `%`      | Modulus (remainder)                  | `x % y`             | `1`     |
| `++`     | Increment (increases value by 1)     | `x++` (post-increment) | `8`     |
| `--`     | Decrement (decreases value by 1)     | `y--` (post-decrement) | `1`     |

---

### 2. **Comparison (Relational) Operators**
Comparison operators are used to compare two values. They return a boolean (`true` or `false`).

| Operator | Description                          | Example (x=7, y=2) | Result  |
|----------|--------------------------------------|---------------------|---------|
| `==`     | Equal to                             | `x == y`            | `false` |
| `!=`     | Not equal to                         | `x != y`            | `true`  |
| `>`      | Greater than                         | `x > y`             | `true`  |
| `<`      | Less than                            | `x < y`             | `false` |
| `>=`     | Greater than or equal to             | `x >= y`            | `true`  |
| `<=`     | Less than or equal to                | `x <= y`            | `false` |

---

### 3. Logical Operators
Logical operators determine the logic in an expression containing two or more values or variables.

Let `x = 8` and `y = 2`.

| Operator | Description                                             | Example                       | Result  |
|----------|---------------------------------------------------------|-------------------------------|---------|
| `&&`     | Logical AND (returns true if both operands are true)    | `x < y && x != y`              | `True`  |
| `\|\|`   | Logical OR (returns true if at least one operand is true) | `x < y \|\| x == y`             | `True`  |
| `!`      | Logical NOT (reverses the result)                       | `!(x < y && x == y)`          | `False` |

---

### 4. Bitwise Operators

These operators perform operations on every bit of a number.  
Let `x = 2` and `y = 3`. In binary, `x` is `010` and `y` is `011`.

| Operator | Description                                              | Example                                   |
|----------|----------------------------------------------------------|-------------------------------------------|
| `&`      | Performs bitwise AND. `1&1=1`, `0&1=0`, `1&0=0`, `0&0=0` | `(x & y) = (010 & 011) = 010 = 2`         |
| `\|`     | Performs bitwise OR. `1\|0=1`, `0\|1=1`, `1\|1=1`, `0\|0=0` | `(x \| y) = (010 \| 011) = 011 = 3`     |
| `^`      | Performs bitwise XOR. `1^0=1`, `0^1=1`, `1^1=0`, `0^0=0` | `(x ^ y) = (010 ^ 011) = 001 = 1`         |
| `<<`     | Left shift: Moves bits to the left by a specified amount.| `13 << 2 = 52` (decimal)                  |
| `>>`     | Right shift: Moves bits to the right by a specified amount.| `13 >> 2 = 3` (decimal)                |

---

### 5. **Assignment Operators**
Assignment operators are used to assign values to variables.

| Operator | Description                          | Example             | Result  |
|----------|--------------------------------------|---------------------|---------|
| `=`      | Assign                              | `x = 5`             | `x = 5` |
| `+=`     | Add and assign                      | `x += 3`            | `x = 8` |
| `-=`     | Subtract and assign                 | `x -= 2`            | `x = 6` |
| `*=`     | Multiply and assign                 | `x *= 2`            | `x = 12`|
| `/=`     | Divide and assign                   | `x /= 2`            | `x = 6` |
| `%=`     | Modulus and assign                  | `x %= 4`            | `x = 2` |

---

## Precedence of Operators

The operators are applied and evaluated based on precedence. For example, `+` and `-` have less precedence compared to `*` and `/`. Hence, `*` and `/` are evaluated first.

In case we want to change this order, we use parentheses `()`.


### Example Code
Here’s an example to demonstrate the usage of these operators:

```java
public class Main {
    public static void main(String[] args) {
        int x = 7, y = 2;

        // Arithmetic Operators
        System.out.println("Addition: " + (x + y)); // 9

        // Comparison Operators
        System.out.println("x > y: " + (x > y)); // true

        // Logical Operators
        System.out.println("x > y && x != y: " + (x > y && x != y)); // true

        // Bitwise Operators
        System.out.println("Bitwise AND: " + (x & y)); // 2

        // Assignment Operators
        x += 5;
        System.out.println("x after += 5: " + x); // 12
    }
}
