# Relational and Logical Operators in Java

## **Relational Operators**
Relational operators are used to evaluate conditions (`true` or `false`) in Java. These operators are commonly used within `if` statements to compare values.

| Operator | Meaning                      |
|----------|------------------------------|
| `==`     | Equals                       |
| `>=`     | Greater than or equals to    |
| `>`      | Greater than                 |
| `<`      | Less than                    |
| `<=`     | Less than or equals to       |
| `!=`     | Not equals                   |

### **Note**:
- `=` is used for assignment.
- `==` is used for equality check.

---

## **Logical Operators**
Logical operators provide logic to Java programs. They help in combining multiple conditions or reversing the logic of a condition.

### **Types of Logical Operators**

### 1. **`&&` - AND**
Evaluates to `true` if *both* conditions are `true`.

| Condition 1 | Condition 2 | Result (`&&`) |
|-------------|-------------|---------------|
| `True`      | `True`      | `True`        |
| `True`      | `False`     | `False`       |
| `False`     | `True`      | `False`       |
| `False`     | `False`     | `False`       |

**Convention**:  
- `Y` = `True`  
- `N` = `False`

---

### **`||` - OR**
Evaluates to `true` when at least one condition is `true`.

| Condition 1 | Condition 2 | Result (OR) |
|-------------|-------------|---------------|
| `True`      | `True`      | `True`        |
| `True`      | `False`     | `True`        |
| `False`     | `True`      | `True`        |
| `False`     | `False`     | `False`       |

**Convention**:  
- `Y` = `True`  
- `N` = `False`

---

### 3. **`!` - NOT**
Negates the given logic (i.e., `true` becomes `false` and vice-versa).

| Condition | Result (`!`) |
|-----------|--------------|
| `True`    | `False`      |
| `False`   | `True`       |

---

These operators are essential in implementing conditional logic and decision-making processes in Java programs.
