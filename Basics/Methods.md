# Java Methods

Methods in Java are blocks of code that are designed to perform a particular task. They are used to execute specific functionality and can be reused across a program. This guide will help you understand the basics of methods in Java, their definition, usage, and types.

## Introduction to Methods

```java
public void greet() {
    System.out.println("Hello, World!");
}
```

## Declaring a Method

```java
public int square(int number) {
    return number * number;
}
```

## Calling a Method

```java
greet();

int result = square(5);
System.out.println(result);  // Outputs: 25
```

## Method Parameters

### 1. Passing Primitive Data Types
```java
public void showDouble(double value) {
    System.out.println("Double value: " + value);
}

showDouble(3.142);
```

### 2. Passing Objects as Parameters
```java
class Person {
    String name;
}

public void printPersonName(Person p) {
    System.out.println(p.name);
}

Person person = new Person();
person.name = "John";
printPersonName(person);  // Outputs: John
```

## Return Types

### 1. Returning Primitive Data Types
```java
public int add(int a, int b) {
    return a + b;
}

int sum = add(5, 3);  // sum = 8
```

### 2. Returning Objects
```java
public Person createPerson(String personName) {
    Person newPerson = new Person();
    newPerson.name = personName;
    return newPerson;
}

Person person = createPerson("Alice");
```

## Method Overloading

```java
public void display(int a) {
    System.out.println("Integer: " + a);
}

public void display(double b) {
    System.out.println("Double: " + b);
}

display(5);        // Outputs: Integer: 5
display(5.5);      // Outputs: Double: 5.5
```

## Varargs (Variable-Length Argument Lists)

```java
public void displayNumbers(int... numbers) {
    for (int num : numbers) {
        System.out.print(num + " ");
    }
}

displayNumbers(1, 2, 3, 4, 5);  // Outputs: 1 2 3 4 5
```

## Recursive Methods

```java
public int factorial(int n) {
    if (n == 0) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}

int result = factorial(5);  // result = 120
```

## Conclusion

Methods are crucial building blocks in Java applications, enabling modularization and reusability. Understanding how to declare, call, and manipulate methods paves the way for building robust and maintainable Java programs.

[⬅️ Previous: Control Structures](./ControlStructures.md) | [🔝 Back to Table of Contents](../README.md) | [➡️ Next: Classes & Objects](../Intermediate/ClassesAndObjects.md)
