# Java String Methods

String methods operate on Java Strings and are used to perform various operations like finding the length of a string, converting it to lowercase, etc.


# Commonly Used String Methods

| **Method**                     | **Description**                                                                 |
|--------------------------------|---------------------------------------------------------------------------------|
| `length()`                     | Returns the length of `name`. (5 in this case)                                  |
| `toLowerCase()`                | Converts all characters of the string to lowercase letters.                     |
| `toUpperCase()`                | Converts all characters of the string to uppercase letters.                     |
| `trim()`                       | Removes leading and trailing spaces from the string.                            |
| `substring(int start)`         | Returns a substring from the `start` index to the end. `substring(3)` returns `"sh"`. |
| `substring(int start, int end)`| Returns a substring from the `start` index to the `end` index (exclusive).      |
| `replace('u', 'o')`            | Replaces all occurrences of `u` with `o`. `"Ayush"` becomes `"Ayosh"`.          |
| `startsWith("Ay")`             | Returns `true` if `name` starts with `"Ay"`.                                    |
| `endsWith("sh")`               | Returns `true` if `name` ends with `"sh"`.                                      |
| `charAt(2)`                    | Returns the character at the specified index. (e.g., `u` for index `2`).        |
| `indexOf("y")`                 | Returns the index of the first occurrence of `"y"`. (e.g., `1`).                |
| `lastIndexOf("u")`             | Returns the last index of the specified character. (e.g., `2` for `"u"`).       |
| `equals("Ayush")`              | Returns `true` if `name` is exactly `"Ayush"`, `false` otherwise (case-sensitive). |
| `equalsIgnoreCase("ayush")`    | Returns `true` if `name` equals `"ayush"` ignoring case differences.            |

---

# Escape Sequence Characters

Escape sequence characters consist of more than one character but represent a single character when used within strings. These are useful for formatting strings.

| **Escape Sequence** | **Description**                |
|----------------------|--------------------------------|
| `\n`                | Inserts a new line.           |
| `\t`                | Inserts a tab.                |
| `\'`                | Inserts a single quote.       |
| `\\"`               | Inserts a double quote.       |
| `\\`                | Inserts a backslash.          |

### Example:
```java
String name = "Ayush";
// Indexes: 0-A, 1-y, 2-u, 3-s, 4-h
