# Typedef in C – Temperature Example

## Overview

This project demonstrates the use of the **`typedef` keyword in C** to create an alias for an existing data type.

In this example, `float` is renamed as `Temperature`, making the code more readable and meaningful when working with temperature values.

---

## Concepts Covered

- `typedef` keyword
- Type aliases
- Floating-point variables
- Code readability
- Formatted output using `printf()`

---

## Project Description

The program creates a custom type called `Temperature` using `typedef`.

```c
typedef float Temperature;
```

After creating the alias, temperature values are declared using the new type name instead of directly using `float`.

The program stores and displays temperature values for today and tomorrow.

---

## Type Definition

```c
typedef float Temperature;
```

Here, `Temperature` becomes an alternative name for the `float` data type.

---

## Variable Declaration

```c
Temperature today = 25.5;
Temperature tomorrow = 18.6;
```

These variables are internally stored as floating-point values but are represented using a more meaningful name.

---

## Sample Output

```text
Today: 25.5 C
Tomorrow: 18.6 C
```

---

## Learning Outcomes

- Understanding the purpose of `typedef`
- Creating custom names for existing data types
- Improving code readability and maintainability
- Working with floating-point variables

---

## Real-World Applications

- Embedded Systems Development
- Sensor Data Processing
- Hardware Abstraction Layers
- Device Drivers
- Networking Applications
- Large-Scale Software Projects

Using `typedef` makes code easier to understand and maintain, especially in complex projects.

---

## Time Complexity

```text
O(1)
```

Variable assignment and printing occur in constant time.

---

## Space Complexity

```text
O(1)
```

Only two floating-point variables are stored.

---

## Key Takeaway

The `typedef` keyword allows programmers to create meaningful aliases for existing data types, making programs more readable, organized, and easier to maintain.

---

## Author

**Amrutha D N**
