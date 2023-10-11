# Java Variables and Operators

Java, like other programming languages, allows you to store data in variables. These variables can be manipulated using operators. This guide will help you understand the basic variables and operators available in Java.

## Variables

Variables are named memory locations used to store data. The value stored in a variable can be changed during program execution.

### Data Type Declaration
```java
int number;
char letter;
double decimalValue;
```

### Variable Initialization
```java
int age = 25;
String name = "John";
boolean isActive = true;
```

### Variable Re-assignment
```java
int score = 50;
score = 70;  // re-assigning the value
```

## Operators

Operators allow you to perform operations on variables and values.

### Arithmetic Operators
```java
int a = 10, b = 20;
int sum = a + b;
int diff = a - b;
int product = a * b;
double quotient = (double) a / b;
```

### Relational Operators
```java
boolean isEqual = a == b;
boolean isNotEqual = a != b;
boolean isGreater = a > b;
boolean isLess = a < b;
```

### Logical Operators
```java
boolean andResult = (a < 15) && (b > 15);
boolean orResult = (a < 15) || (b < 15);
boolean notResult = !(a == b);
```

### Assignment Operators
```java
int c = a + b;
c += a;  // equivalent to c = c + a
c -= a;  // equivalent to c = c - a
```

### Increment and Decrement Operators
```java
a++;  // equivalent to a = a + 1
b--;  // equivalent to b = b - 1
```

### Conditional Operator
```java
int result = (a > b) ? a : b;  // Assigns the greater value between a and b to result
```

## Conclusion

Variables and operators form the basis for constructing logic and functionality in Java. Mastery of these is essential for creating effective Java programs.

[⬅️ Previous: Data Types](./DataTypes.md) | [🔝 Back to Table of Contents](../README.md) | [➡️ Next: Control Structures](./ControlStructures.md)
