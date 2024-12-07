# Java Operator Precedence and Associativity

## Associativity
Associativity determines the direction in which operators of the same precedence are evaluated. It can either be **Left-to-Right (L to R)** or **Right-to-Left (R to L)**.

### Examples:
- `/`, `*` -> **L to R**
- `+`, `-` -> **L to R**
- `++`, `=` -> **R to L**

# Precedence and Associativity Table

| Precedence | Operator                                   | Type                                       | Associativity        |
|------------|-------------------------------------------|--------------------------------------------|----------------------|
| 15         | `()` `[]` `.`                             | Parentheses, Array subscript, Member selection | Left to Right        |
| 14         | `++` `--`                                 | Unary post-increment, Unary post-decrement | Left to Right        |
| 13         | `++` `--` `+` `-` `!` `~` `(type)`        | Unary pre-increment, Unary pre-decrement, Unary plus, Unary minus, Unary logical negation, Unary bitwise complement, Unary type cast | Right to Left |
| 12         | `*` `/` `%`                               | Multiplication, Division, Modulus          | Left to Right        |
| 11         | `+` `-`                                   | Addition, Subtraction                      | Left to Right        |
| 10         | `<<` `>>` `>>>`                           | Bitwise left shift, Bitwise right shift with sign extension, Bitwise right shift with zero extension | Left to Right |
| 9          | `<` `<=` `>` `>=` `instanceof`            | Relational less than, Relational less than or equal, Relational greater than, Relational greater than or equal, Type comparison (objects only) | Left to Right |
| 8          | `==` `!=`                                 | Relational is equal to, Relational is not equal to | Left to Right |
| 7          | `&`                                       | Bitwise AND                                | Left to Right        |
| 6          | `^`                                       | Bitwise exclusive OR                       | Left to Right        |
| 5          | `|`                                       | Bitwise inclusive OR                       | Left to Right        |
| 4          | `&&`                                      | Logical AND                                | Left to Right        |
| 3          | `\|\|`                                    | Logical OR                                 | Left to Right        |
| 2          | `? :`                                     | Ternary conditional                        | Right to Left        |
| 1          | `=` `+=` `-=` `*=` `/=` `%=`              | Assignment and compound assignments        | Right to Left        |

**Note**: Larger numbers indicate higher precedence.

---

### How to Use This Table
1. **Precedence** determines which operator is evaluated first in expressions with multiple operators.
2. **Associativity** resolves the order when two operators have the same precedence.

### Example:
For the expression `a + b * c`, the multiplication (`*`) is evaluated before addition (`+`) because it has a higher precedence. In the expression `a = b = c`, assignment (`=`) is right-to-left associative, so `c` is assigned to `b`, and then `b` is assigned to `a`.


---

## How to Use This Table
- **Precedence**: Operators with higher precedence are evaluated first.
- **Associativity**: If operators have the same precedence, associativity determines the order of execution.

### Example:
Consider the expression `a + b * c`.  
- `*` has higher precedence than `+`, so `b * c` is evaluated first.
- If associativity comes into play (e.g., `a - b + c`), both `-` and `+` have the same precedence, and associativity (L to R) determines the execution order.

Use this table to clarify how expressions are evaluated in Java programs!

