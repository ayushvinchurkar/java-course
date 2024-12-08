# Java Arithmetic Operations and Increment/Decrement Operators

## Resulting Data Types After Arithmetic Operations

| Expression                  | Resulting Data Type |
|-----------------------------|---------------------|
| `byte + short`              | `int`              |
| `short + int`               | `int`              |
| `long + float`              | `float`            |
| `int + float`               | `float`            |
| `char + int`                | `int`              |
| `char + short`              | `int`              |
| `long + double`             | `double`           |
| `float + double`            | `double`           |

### Key Notes:
- Mixed data type operations follow type promotion rules.
- The result is promoted to the higher type based on Java's type hierarchy.

---

## Increment and Decrement Operators

### Operators:
- `a++` / `++a` : Increment operators
- `a--` / `--a` : Decrement operators

### Behavior:
- **`a++`**: Use the current value of `a`, then increment.
- **`++a`**: Increment `a`, then use the updated value.
- **`a--`**: Use the current value of `a`, then decrement.
- **`--a`**: Decrement `a`, then use the updated value.

### Supported Data Types:
- These operators work on all primitive data types **except `boolean`**.

---

## Quick Quiz

Try increment and decrement operators on a Java variable to observe the behavior:
```java
int a = 5;
System.out.println(a++); // Outputs: 5, then a becomes 6
System.out.println(++a); // Outputs: 7, a is already incremented
System.out.println(a--); // Outputs: 7, then a becomes 6
System.out.println(--a); // Outputs: 5, a is decremented

