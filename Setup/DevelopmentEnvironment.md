# Java Development Environment Setup with VSCode

Visual Studio Code (VSCode) is a lightweight and versatile code editor developed by Microsoft. Though it's not an Integrated Development Environment (IDE) in the traditional sense, it can be configured to offer IDE-like functionalities for Java with the help of extensions. This guide will walk you through setting up Java with VSCode for a seamless development experience.

## Installing Java

Before diving into VSCode, ensure that you have Java installed and properly configured on your machine.

1. Visit the [official Java download page](https://www.oracle.com/java/technologies/javase-jdk16-downloads.html) and download the appropriate version for your OS.
2. Install the downloaded Java Development Kit (JDK).
3. Set up the `JAVA_HOME` environment variable pointing to the JDK installation directory.

## Configuring VSCode for Java Development

1. If you haven't already, [download and install VSCode](https://code.visualstudio.com/).
2. Open VSCode and head to the Extensions view by clicking on the square icon on the sidebar or pressing `Ctrl+Shift+X`.
3. Search for the `Java Extension Pack` by Microsoft. This pack bundles essential Java extensions, including Language Support, Debugger, and Test Runner.
4. Install the `Java Extension Pack`.
5. After installation, open a `.java` file, and VSCode will automatically recognize and configure the Java environment.
6. (Optional) For building projects, you might want to install the Maven for Java or Gradle for Java extensions, depending on your build tool preference.

## Verify Your Setup

1. Create a new file with a `.java` extension, for instance, `HelloWorld.java`.
2. Add the following code:

   ```java
   public class HelloWorld {
       public static void main(String[] args) {
           System.out.println("Hello, World!");
       }
   }
```

1. Right-click inside the file editor and choose "Run Java." You should see the output "Hello, World!" in the terminal.

Conclusion

Congratulations! You've now set up your VSCode for Java development. As you explore Java, consider diving into VSCode's plethora of extensions that cater to various Java development needs, from frameworks to databases.

[⬅️ Back to Table of Contents](../README.md)
