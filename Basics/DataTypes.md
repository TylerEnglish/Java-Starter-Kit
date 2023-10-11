# Java Data Types

In Java, every variable has a data type, which specifies the size and type of values it can hold. Java offers various data types to cater to different kinds of information that a program might need to store. This guide will explore the basic data types provided by Java.

## Primitive Data Types

Java defines eight basic (or "primitive") data types:

### 1. Byte
- Description: 8-bit signed integer
- Min Value: -128
- Max Value: 127
  ```java
  byte sampleByte = 100;
  System.out.println("Byte value: " + sampleByte);
  ```

### 2. Short
- Description: 16-bit signed integer
- Min Value: -32,768
- Max Value: 32,767
  ```java
  short sampleShort = 20000;
  System.out.println("Short value: " + sampleShort);
  ```

### 3. Int
- Description: 32-bit signed integer
- Min Value: -2^31
- Max Value: 2^31 -1
  ```java
  int sampleInt = 100000;
  System.out.println("Int value: " + sampleInt);
  ```

### 4. Long
- Description: 64-bit signed integer
- Min Value: -2^63
- Max Value: 2^63 -1
  ```java
  long sampleLong = 50000L + 10L * (sampleByte + sampleShort + sampleInt);
  System.out.println("Long value: " + sampleLong);
  ```

### 5. Float
- Description: 32-bit floating point
  ```java
  float sampleFloat = 5.25f;
  System.out.println("Float value: " + sampleFloat);
  ```

### 6. Double
- Description: 64-bit floating point
  ```java
  double sampleDouble = .123d;
  System.out.println("Double value: " + sampleDouble);
  ```

### 7. Char
- Description: 16-bit Unicode character
  ```java
  char sampleChar = 'A';
  System.out.println("Char value: " + sampleChar);
  ```

### 8. Boolean
- Description: Represents true or false values
  ```java
  boolean sampleBoolean = true;
  System.out.println("Boolean value: " + sampleBoolean);
  ```

## Non-primitive Data Types

Unlike primitive data types, non-primitive (or reference) data types don't store the actual values but rather a reference to those values.

### 1. Strings
- Description: Represents a sequence of characters
  ```java
  String sampleString = "Hello, Java!";
  System.out.println("String value: " + sampleString);
  ```

### 2. Arrays
- Description: A collection of data items of the same type
  ```java
  int[] sampleArray = {1, 2, 3, 4, 5};
  System.out.println("Array first element: " + sampleArray[0]);
  ```

### 3. Classes & Objects
  ```java
  class SampleClass {
      String name;

      SampleClass(String name) {
          this.name = name;
      }

      void display() {
          System.out.println("Name: " + name);
      }
  }

  SampleClass obj = new SampleClass("Java");
  obj.display();
  ```

## Conclusion

Understanding Java's data types is foundational to mastering the language. They form the building blocks upon which more complex data structures and algorithms are built.

[⬅️ Back to Table of Contents](../README.md) | [➡️ Next: Variables & Operators](./VariablesAndOperators.md)
