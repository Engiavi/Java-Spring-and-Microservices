# Java Overview

Java is a high-level, class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.

## JDK (Java Development Kit)

The JDK is a software development environment used for developing Java applications and applets. It includes the Java Runtime Environment (JRE), an interpreter/loader (Java), a compiler (javac), an archiver (jar), a documentation generator (Javadoc) and other tools needed in Java development. Essentially, the JDK is a package of tools for developing Java-based software.

## JRE (Java Runtime Environment)

The JRE is a part of the Java Development Kit (JDK), but can be downloaded separately. It is the runtime portion of Java software, which is all you need to run it in your Web browser. The JRE consists of the Java Virtual Machine (JVM), core classes, and supporting files. It is what is required to run Java applications.

## JVM (Java Virtual Machine)

The JVM is an engine that provides a runtime environment to drive the Java Code or applications. It converts Java bytecode into machine language. JVM is a part of the JRE (Java Runtime Environment). The JVM is responsible for ensuring Java applications run on any device or operating system, thus enabling the WORA functionality. It does this by emulating a platform-independent computing environment that hides the details of the underlying hardware and operating system.

Java's platform independence consists not only of its hardware independence but also its OS independence, which makes Java a highly versatile and widely used programming language.

## JShell: Interactive Java REPL

Introduced in Java 9, JShell (Java Shell) is an interactive Read-Evaluate-Print Loop (REPL) tool that significantly enhances the Java development experience. It allows developers to quickly test Java code snippets without the need for a full development environment, making it an invaluable tool for learning, experimentation, and rapid prototyping.

### Key Features of JShell:

- **Immediate Feedback**: Execute Java statements, including variable definitions, method declarations, and expressions, and see the results instantly.
- **Ease of Use**: Ideal for beginners learning Java or seasoned developers exploring new features or APIs.
- **Enhanced Productivity**: Supports tab completion, automatic semicolon insertion, and other features to speed up the development process.
- **Session Management**: Save and load JShell sessions to resume work or share snippets with others.

JShell opens up new possibilities for Java developers, offering a flexible and efficient way to test ideas and understand complex code behaviors quickly.


## Running a Java File

To run a Java file, you must first compile it into bytecode and then execute the bytecode with the Java Virtual Machine (JVM). Here's a step-by-step guide to compile and run a Java file named `Hello.java`.

### Step 1: Compile the Java File

Open a terminal or command prompt and navigate to the directory containing your `Hello.java` file. Then, compile the file using the Java compiler `javac`:

```bash```
javac Hello.java

This command will compile Hello.java and generate a Hello.class file, which is the bytecode version of your Java program.

``Step 2: Run the Compiled Java Program``
After compiling, you can run the program using the java command followed by the name of the class that contains the main method (without the .class extension):

`java Hello`

This command will execute the main method in the Hello class, and you should see the output of your program in the terminal.

```Note```
Ensure that you have the Java Development Kit (JDK) installed on your system and that the javac and java commands are available in your system's PATH to compile and run Java programs.