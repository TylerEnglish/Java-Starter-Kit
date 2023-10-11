# Java Classes and Objects

In object-oriented programming, classes and objects are fundamental concepts. A class is a blueprint for creating objects, and an object is an instance of a class. This guide will dive into the basics of classes and objects in Java.

## Introduction to Classes

```java
class Dog {
    String breed;
    int age;
}
```

## Creating Objects

```java
Dog myDog = new Dog();
myDog.breed = "Golden Retriever";
myDog.age = 5;
```

## Class Constructors

```java
class Cat {
    String breed;
    int age;

    Cat(String b, int a) {
        breed = b;
        age = a;
    }
}

Cat myCat = new Cat("Siamese", 3);
```

## Class Members

### 1. Fields (Attributes)
```java
class Bird {
    String species;
    boolean canFly;
}
```

### 2. Methods
```java
class Fish {
    String species;

    void swim() {
        System.out.println(species + " is swimming.");
    }
}
```

### 3. Nested Classes
```java
class OuterClass {
    int x = 10;

    class InnerClass {
        int y = 5;
    }
}

OuterClass outerObj = new OuterClass();
OuterClass.InnerClass innerObj = outerObj.new InnerClass();
```

## Access Modifiers

### 1. Public, Private, and Protected
```java
public class PublicClass {}

private class PrivateClass {}  // Note: This will cause a compilation error. You can't have a top-level private class.

protected class ProtectedClass {}  // Note: This will cause a compilation error for top-level classes. Protected works for inner classes.
```

### 2. The 'default' Access Modifier
```java
class DefaultModifierClass {
    // No access modifier is used, hence it's "default" or "package-private"
}
```

## 'this' Keyword

```java
class Rectangle {
    int width;
    int height;

    Rectangle(int width, int height) {
        this.width = width;
        this.height = height;
    }
}
```

## 'static' Keyword

```java
class StaticExample {
    static int staticVar = 5;

    static void staticMethod() {
        System.out.println("This is a static method.");
    }
}

System.out.println(StaticExample.staticVar);
StaticExample.staticMethod();
```

## 'final' Keyword

```java
final class FinalClass {
    // This class cannot be extended
}

class RegularClass {
    final int FINAL_VARIABLE = 10;  // This variable's value cannot be changed

    final void finalMethod() {
        // This method cannot be overridden in a subclass
    }
}
```

## Conclusion

Classes and objects form the core of Java's object-oriented paradigm. Understanding these concepts is pivotal for designing and developing efficient Java applications.

[⬅️ Previous: Methods](./Methods.md) | [🔝 Back to Table of Contents](../README.md) | [➡️ Next: OOP Concepts](./OOPConcepts.md)
