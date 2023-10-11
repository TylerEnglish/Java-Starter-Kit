# Java Control Structures

Control structures dictate the flow of a program's execution. Java provides a variety of control structures to handle the decision-making process and to manage the flow of the program's execution based on specified conditions. This guide will introduce you to the fundamental control structures in Java.

## Conditional Statements

### 1. If Statement
```java
int age = 20;
if (age >= 18) {
    System.out.println("Eligible to vote.");
}
```

### 2. If-Else Statement
```java
if (age >= 18) {
    System.out.println("Eligible to vote.");
} else {
    System.out.println("Not eligible to vote.");
}
```

### 3. Nested If-Else
```java
int score = 85;
if (score >= 90) {
    System.out.println("Grade A");
} else if (score >= 80) {
    System.out.println("Grade B");
} else {
    System.out.println("Grade C");
}
```

### 4. If-Else-If Ladder
```java
if (score >= 90) {
    System.out.println("Grade A");
} else if (score >= 80) {
    System.out.println("Grade B");
} else if (score >= 70) {
    System.out.println("Grade C");
} else {
    System.out.println("Grade D");
}
```

### 5. Switch Case
```java
int day = 3;
switch(day) {
    case 1: 
        System.out.println("Monday");
        break;
    case 2: 
        System.out.println("Tuesday");
        break;
    case 3: 
        System.out.println("Wednesday");
        break;
    //... other cases
    default:
        System.out.println("Invalid day");
}
```

## Looping Structures

### 1. For Loop
```java
for (int i = 0; i < 5; i++) {
    System.out.println("Loop iteration: " + i);
}
```

### 2. While Loop
```java
int i = 0;
while (i < 5) {
    System.out.println("Loop iteration: " + i);
    i++;
}

```

### 3. Do-While Loop
```java
i = 0;
do {
    System.out.println("Loop iteration: " + i);
    i++;
} while (i < 5);
```

### 4. Enhanced For Loop (For-each loop)
```java
int[] numbers = {1, 2, 3, 4, 5};
for (int number : numbers) {
    System.out.println("Number: " + number);
}
```

## Jump Statements

### 1. Break
```java
for (int j = 0; j < 10; j++) {
    if (j == 5) {
        break;
    }
    System.out.println("Number: " + j);
}
```

### 2. Continue
```java
for (int j = 0; j < 10; j++) {
    if (j == 5) {
        continue;
    }
    System.out.println("Number: " + j);
}
```

### 3. Return
```java
public int add(int a, int b) {
    return a + b;
}
```

## Conclusion

Understanding control structures is crucial for designing algorithms and flow in your Java applications. Mastery of these constructs will enable you to craft more complex and dynamic applications.

[⬅️ Previous: Variables & Operators](./VariablesAndOperators.md) | [🔝 Back to Table of Contents](../README.md) | [➡️ Next: Methods](./Methods.md)
