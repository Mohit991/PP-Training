# Java Basics
## History
## Java History

Java is a high-level, class-based, object-oriented programming language that was designed to have as few implementation dependencies as possible. It was originally developed by James Gosling and his team at Sun Microsystems in the early 1990s.

### Origins

Java's development began in 1991 as part of the "Green Project" at Sun Microsystems. The goal was to create a language that could be used to program a wide range of consumer electronic devices. Initially, the language was called **Oak**, named after an oak tree that stood outside Gosling’s office. However, the name was later changed to **Java**, inspired by Java coffee, due to a trademark issue with the name Oak.

### Public Release

Java was officially released in **1995** with the slogan **"Write Once, Run Anywhere" (WORA)**. This concept highlighted Java’s key feature: the ability to run the same program on different platforms without modification, thanks to the Java Virtual Machine (JVM).

---

## Java Version History

Below is a list of major Java versions with their release years and notable features:

| Version         | Release Year | Notable Features |
|-----------------|--------------|------------------|
| JDK 1.0         | 1996         | Initial release |
| JDK 1.1         | 1997         | Inner classes, JavaBeans, JDBC |
| J2SE 1.2        | 1998         | Swing, Collections Framework |
| J2SE 1.3        | 2000         | HotSpot JVM, RMI enhancements |
| J2SE 1.4        | 2002         | Assertions, NIO, Logging API |
| J2SE 5.0 (1.5)  | 2004         | Generics, Enums, Annotations, Enhanced for-loop |
| Java SE 6       | 2006         | Scripting API, improvements to Web Services |
| Java SE 7       | 2011         | try-with-resources, Diamond operator, NIO.2 |
| Java SE 8       | 2014         | Lambda expressions, Streams API, Date and Time API |
| Java SE 9       | 2017         | Project Jigsaw (Modules), JShell |
| Java SE 10      | 2018 (Mar)   | Local variable type inference (`var`) |
| Java SE 11 (LTS)| 2018 (Sep)   | New HTTP Client API, String methods, LTS release |
| Java SE 12      | 2019 (Mar)   | Switch expression (preview) |
| Java SE 13      | 2019 (Sep)   | Text blocks (preview) |
| Java SE 14      | 2020 (Mar)   | Records (preview), Helpful NullPointerExceptions |
| Java SE 15      | 2020 (Sep)   | Text blocks (final), Sealed classes (preview) |
| Java SE 16      | 2021 (Mar)   | Records (final), Pattern matching for `instanceof` |
| Java SE 17 (LTS)| 2021 (Sep)   | Sealed classes (final), New macOS rendering pipeline |
| Java SE 18      | 2022 (Mar)   | UTF-8 by default, Simple web server |
| Java SE 19      | 2022 (Sep)   | Virtual threads (preview), Record patterns (preview) |
| Java SE 20      | 2023 (Mar)   | Continued preview of virtual threads and pattern matching |
| Java SE 21 (LTS)| 2023 (Sep)   | Virtual threads (final), Sequenced collections, String templates (preview) |
| Java SE 22      | 2024 (Mar)   | Stream gatherers, Foreign Function & Memory API (2nd preview) |
| Java SE 23      | 2024 (Sep)   | Features TBD (if already released) |
| Java SE 24      | 2025 (Mar)   | Latest version with cutting-edge enhancements |

> **Note:** LTS stands for Long-Term Support, meaning these versions receive extended updates and support.

---

### Modern Java

Today, Java continues to be widely used in enterprise applications, Android development, scientific computing, and cloud platforms. Java has embraced rapid evolution with a six-month release cadence since Java 9, encouraging quicker innovation and feature integration.

### Conclusion

Java's design philosophy of platform independence, security, and robust community support has helped it remain one of the most enduring and influential programming languages in the world.



The latest release of the Java SE Platform is Java 24, according to Oracle. 
Java 24 was released in March 2025. Oracle strongly recommends users upgrade to Java 24.0.1, the latest version of the Java SE Platform. 

## Java Editions

Java is available in multiple editions, each designed for specific development needs. Below are the main editions of Java:

---

### Java Standard Edition (Java SE)

**Purpose:**  
Core Java programming for general-purpose desktop and server-side applications.

**Features:**
- Fundamental libraries: `java.lang`, `java.util`, `java.io`, etc.
- Core APIs for collections, threading, networking, etc.
- Tools: `javac`, `java`, `JVM`, `JRE`, `JDK`.

**Use Cases:**
- Desktop applications  
- Command-line tools  
- Utility software

---

### Java Enterprise Edition (Java EE)  
**Note:** Now known as **Jakarta EE**

**Purpose:**  
Developing large-scale, distributed, and multi-tier enterprise applications.

**Features:**
- Builds on Java SE  
- APIs for:
  - Servlets  
  - JSP (JavaServer Pages)  
  - EJB (Enterprise JavaBeans)  
  - JPA (Java Persistence API)  
  - Web Services (SOAP/REST)  
- Supports dependency injection and annotations

**Use Cases:**
- Web applications  
- Enterprise systems (ERP, CRM, banking apps)  
- Backend APIs

---

### Java Micro Edition (Java ME)

**Purpose:**  
Developing applications for embedded systems and mobile devices with limited resources.

**Features:**
- Lightweight version of Java SE  
- Smaller library set  
- Uses configurations and profiles:
  - CLDC (Connected Limited Device Configuration)  
  - MIDP (Mobile Information Device Profile)

**Use Cases:**
- Feature phones  
- IoT devices  
- Embedded systems

---

### JavaFX

**Purpose:**  
Creating rich client GUI applications for desktops.

**Features:**
- Modern UI components  
- Support for CSS-style styling  
- Scene Graph-based UI model  
- Integrated with Java SE

**Use Cases:**
- GUI-based desktop applications  
- Multimedia-rich apps

---

### Summary Table

| Edition     | Target Area             | Main Features                                     |
|-------------|--------------------------|--------------------------------------------------|
| Java SE     | General-purpose          | Core libraries, OOP, threading, collections      |
| Java EE     | Enterprise/web apps      | Servlets, JSP, EJB, JPA, Web Services            |
| Java ME     | Mobile/embedded systems  | Lightweight APIs, CLDC/MIDP profiles             |
| JavaFX      | GUI desktop apps         | Rich UI toolkit with media and 2D/3D support     |


## Java Development Kit (JDK)

The **Java Development Kit (JDK)** is a software development environment used for developing Java applications and applets. It is a core component of the Java platform and is required for compiling, debugging, and running Java programs.

---

### What Is Included in the JDK?

The JDK comes bundled with several essential tools and components:

| Component | Description |
|----------|-------------|
| **javac** | The Java compiler – translates Java source code (`.java`) into bytecode (`.class`) files that can be executed by the JVM. |
| **java** | The Java application launcher – runs Java applications by loading and invoking the `main()` method in a class. |
| **javadoc** | A documentation generator – extracts specially formatted comments from Java source files to generate HTML API documentation. |
| **jar** | A tool for packaging Java applications – combines multiple `.class` files and resources into a single JAR (Java Archive) file. |
| **jdb** | The Java Debugger – allows developers to find and fix bugs in Java programs by stepping through code, setting breakpoints, and inspecting variables. |
| **JVM (Java Virtual Machine)** | An abstract machine that runs compiled Java bytecode on any platform. It ensures platform independence through the “Write Once, Run Anywhere” model. |
| **JRE (Java Runtime Environment)** | A subset of the JDK – provides the libraries, JVM, and other components to run Java applications, but not tools like `javac`. |
| **jshell** | An interactive Java REPL (Read-Eval-Print Loop) introduced in JDK 9 – allows for quick prototyping and testing of Java expressions and code snippets. |
| **javap** | A class file disassembler – helps examine the bytecode of compiled `.class` files for debugging or learning purposes. |
| **jlink** | A tool introduced in JDK 9 to create custom runtime images with only the required modules – useful for modular applications. |
| **jdeps** | A dependency analysis tool – helps identify dependencies and modularize applications by analyzing the class-level dependencies. |
| **jstat, jstack, jconsole, jvisualvm** | Monitoring and diagnostic tools – used to monitor JVM performance, analyze memory usage, inspect thread dumps, and profile applications. |

---

### Summary Table

| Package Type | Includes | Purpose |
|--------------|----------|---------|
| **JDK** | JRE + development tools | For developers writing and compiling Java programs |
| **JRE** | JVM + runtime libraries | For users who only need to run Java applications |
| **JVM** | Core execution engine | Executes Java bytecode and provides platform independence |

---

### Why Do You Need the JDK?

If you are developing Java applications, you need the JDK. It provides all the necessary tools to:

- Write Java code
- Compile it into bytecode
- Run and test applications
- Generate documentation
- Debug and monitor programs

---

### Conclusion

The Java Development Kit is more than just a compiler – it's a full suite of tools essential for Java development. Whether you're writing desktop apps, web services, or enterprise software, the JDK provides the foundation to build, document, and optimize your Java programs effectively.

## Difference Between JDK and JRE

Understanding the difference between **JDK (Java Development Kit)** and **JRE (Java Runtime Environment)** is essential for Java developers and users.

---

### 📦 What Is JDK?

The **Java Development Kit (JDK)** is a full-featured software development kit used for developing Java applications. It includes the **compiler**, **debugging tools**, **documentation tools**, and everything in the JRE.

- 🔧 Used by: Developers
- 🧰 Contains: JRE + Development tools
- 🔤 Includes: `javac`, `java`, `javadoc`, `jar`, `jdb`, and more

---

### 🖥️ What Is JRE?

The **Java Runtime Environment (JRE)** is a subset of the JDK and is used to **run** Java applications. It does **not** include development tools like the compiler or debugger.

- 🧑‍💻 Used by: End-users who only run Java programs
- 🧩 Contains: JVM + Runtime libraries + Core classes
- 🔤 Includes: `java`, standard Java class libraries

---

### 🔍 Key Differences

| Feature         | JDK                          | JRE                        |
|-----------------|------------------------------|----------------------------|
| Purpose         | Develop and run Java programs| Only run Java programs     |
| Includes Compiler (`javac`) | ✅ Yes              | ❌ No                      |
| Includes Debugging Tools | ✅ Yes               | ❌ No                      |
| Includes JVM     | ✅ Yes                        | ✅ Yes                     |
| Includes Core Libraries | ✅ Yes               | ✅ Yes                     |
| Target Audience  | Developers                   | End-users                  |

---

### 📌 Example Use Cases

- **Use JDK** if you're writing, compiling, and debugging Java code.
- **Use JRE** if you're just running Java apps, like Minecraft or enterprise software.

---

### 🧠 Tip

If you install the JDK, you **automatically get the JRE** bundled with it.

---

### ✅ Conclusion

- **JDK = JRE + development tools**
- If you're coding in Java, install the JDK.
- If you're only running Java apps, JRE is sufficient (but often bundled automatically).


## Java Distribution

### What Is a Java Distribution?

A **Java distribution** is a packaged version of the Java platform that includes the Java Development Kit (JDK) and sometimes additional tools, libraries, and support for various platforms and use cases.

Different organizations and vendors provide their own Java distributions, each tailored with different features, licenses, and support options. These distributions are based on the **OpenJDK** project, which is the open-source reference implementation of Java.

---

### Why Are There Multiple Java Distributions?

- **Licensing:** Oracle JDK used to be the primary distribution, but licensing changes led many to adopt open-source or vendor-specific builds.
- **Support & Updates:** Some vendors offer long-term support (LTS), security patches, and performance improvements.
- **Additional Tools:** Certain distributions bundle extra tools or enhancements specific to enterprise or cloud environments.
- **Platform Optimization:** Some builds are optimized for specific operating systems or hardware.

---

### Popular Java Distributions

| Distribution      | Provider         | Description                                      | License              | LTS Support          |
|-------------------|------------------|-------------------------------------------------|----------------------|----------------------|
| **Oracle JDK**    | Oracle           | Official Oracle build, commercial features, requires license for production use (since JDK 11) | Commercial / Oracle Binary License | Yes                  |
| **OpenJDK**       | OpenJDK community| Open-source reference implementation of Java. Base for most other distributions | GPL with Classpath Exception | Community support    |
| **Amazon Corretto** | Amazon          | Free, multiplatform, production-ready OpenJDK distribution | Open source (GPL)    | Yes                  |
| **Adoptium (Eclipse Temurin)** | Eclipse Foundation | Popular OpenJDK build with community and vendor support | Open source (GPL)    | Yes                  |
| **Zulu OpenJDK**  | Azul Systems     | Certified OpenJDK builds with support options and extended platform coverage | Open source (GPL)    | Yes                  |
| **Liberica JDK**  | BellSoft         | Full OpenJDK with additional features like JavaFX included | Open source (GPL)    | Yes                  |
| **Red Hat OpenJDK**| Red Hat          | Enterprise-supported OpenJDK builds | Open source (GPL)    | Yes                  |

---

### How to Choose a Java Distribution?

- **For Development:** Most developers use OpenJDK or distributions like Temurin or Corretto, which are free and open source.
- **For Enterprise:** Oracle JDK (with commercial license) or supported builds like Azul Zulu or Red Hat OpenJDK provide guaranteed support and compliance.
- **For Cloud/Containers:** Lightweight distributions or customized builds (e.g., with jlink) are preferred.

---

### How Are Java Distributions Delivered?

- **Binaries:** Downloadable installers or ZIP/TAR archives for different operating systems (Windows, macOS, Linux).
- **Package Managers:** Many distributions are available through package managers like `apt`, `yum`, `brew`, or SDKMAN.
- **Containers:** Java runtime images can be included in Docker containers for cloud-native deployments.

---

### Summary

Java distributions ensure that Java runs reliably across many platforms and environments. With multiple vendors offering builds suited to different needs, users and organizations have the flexibility to choose the best option for their applications.


![image](https://github.com/user-attachments/assets/54907af3-a117-44d9-afb1-a108c072f7fc)  

## Java Platform Independence

### What Is Platform Independence?

**Platform independence** means that Java programs can run on any device or operating system without needing to be rewritten or recompiled for each platform.

This is one of Java’s most important features, often summarized by the slogan:

> **"Write Once, Run Anywhere" (WORA)**

---

### How Does Java Achieve Platform Independence?

Java achieves platform independence through the use of:

- **Java Source Code (`.java` files):** Written by developers, platform-neutral.
- **Java Compiler (`javac`):** Compiles source code into **bytecode** (`.class` files), which is not specific to any hardware or OS.
- **Java Virtual Machine (JVM):** An interpreter that runs the bytecode on the underlying hardware and operating system.

The JVM is platform-specific — there is a different JVM implementation for Windows, macOS, Linux, etc. But the bytecode remains the same across all platforms.

---

### Why Is This Important?

- **Portability:** Developers don’t need to write different versions of their program for each platform.
- **Efficiency:** Saves time and resources since one compiled program can run everywhere.
- **Security:** JVM acts as a sandbox, controlling program execution and preventing unsafe operations.
- **Consistency:** Ensures the same behavior of Java programs regardless of where they run.


![image](https://github.com/user-attachments/assets/9013fe20-9d08-4220-a02f-57d4a5f2b8be)  

![image](https://github.com/user-attachments/assets/375c195e-669e-47b4-bd16-3c09f51e4f2a)  

![image](https://github.com/user-attachments/assets/aedc2a5b-0dd2-40c4-adfc-90d28c5e4b8f)


## OOPS: Object Oriented Programming

---

### 1. Class

A **class** is a blueprint or template that defines the properties (attributes) and behaviors (methods) common to all objects of that type. It represents a concept or a thing.

- Think of a class as a blueprint for creating objects.
- Classes encapsulate data for the object and methods to manipulate that data.

### Example:

```java
class Dog {
    // Attributes (properties)
    String breed;
    int age;
    String color;

    // Behavior (method)
    void bark() {
        System.out.println("Woof! Woof!");
    }
}
```


### Object
An object is an instance of a class. When a class is defined, no memory is allocated until an object of that class is created.

- Objects have states and behaviors defined by their class.

- Each object can have different values for its attributes.


```java
Dog myDog = new Dog();  // Creating an object of class Dog
myDog.breed = "Labrador";
myDog.age = 5;
myDog.color = "Black";
myDog.bark();  // Output: Woof! Woof!
```

### Encapsulation
Encapsulation is the mechanism of restricting direct access to some of an object’s components and protecting the internal state of the object. This is done by:

- Declaring variables as private.
- Providing public getter and setter methods to access and update the value.

Benefits:

- Protects data integrity by controlling how it’s accessed or modified.
- Improves maintainability and flexibility.

```java
class Person {
    private String name;
    private int age;

    // Getter method for name
    public String getName() {
        return name;
    }

    // Setter method for name
    public void setName(String name) {
        this.name = name;
    }

    // Getter method for age
    public int getAge() {
        return age;
    }

    // Setter method for age
    public void setAge(int age) {
        if(age > 0) {  // validation
            this.age = age;
        }
    }
}
```

### Inheritance
Inheritance allows a new class (subclass or child class) to acquire the properties and behaviors of an existing class (superclass or parent class).

Benefits:

- Promotes code reuse.
- Establishes a natural hierarchical relationship.  

```java
class Animal {
    void eat() {
        System.out.println("Eating...");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Barking...");
    }
}

public class TestInheritance {
    public static void main(String[] args) {
        Dog myDog = new Dog();
        myDog.eat();  // Inherited method
        myDog.bark(); // Dog's own method
    }
}
```

### Polymorphism
Polymorphism means "many forms". It allows one interface to be used for a general class of actions.

Types:

- Method Overloading: Same method name, different parameter lists within the same class (compile-time polymorphism).

```java
class Calculator {
    int add(int a, int b) {
        return a + b;
    }

    int add(int a, int b, int c) {
        return a + b + c;
    }
}
```

- Method Overriding: Subclass provides a specific implementation of a method already defined in its superclass (runtime polymorphism).

```java
class Bird {
    void sound() {
        System.out.println("Some sound");
    }
}

class Parrot extends Bird {
    @Override
    void sound() {
        System.out.println("Squawk");
    }
}

public class TestPolymorphism {
    public static void main(String[] args) {
        Bird myBird = new Parrot();
        myBird.sound();  // Output: Squawk
    }
}
```

### Abstraction
Abstraction is the concept of hiding complex implementation details and showing only the necessary features to the user.

- Achieved using abstract classes and interfaces.

- Helps to reduce complexity and isolate impact of changes.

```java
abstract class Vehicle {
    abstract void move();

    void stop() {
        System.out.println("Vehicle stopped.");
    }
}

class Car extends Vehicle {
    @Override
    void move() {
        System.out.println("Car is moving");
    }
}

public class TestAbstraction {
    public static void main(String[] args) {
        Vehicle myCar = new Car();
        myCar.move();  // Output: Car is moving
        myCar.stop();  // Output: Vehicle stopped.
    }
}
```

### Summary
- Class: Blueprint for objects.

- Object: Instance of a class.

- Encapsulation: Data hiding using private variables and public methods.

- Inheritance: Creating new classes from existing ones.

- Polymorphism: Many forms of methods (overloading and overriding).

- Abstraction: Hiding complexity using abstract classes/interfaces.


## Class Example
### Student.java

```java
public class Student {
    private String studentName;
    private int studentId;
    private float qualifyingMarks;
    private int yearOfEngineering;
    private char residentialStatus;

    // Setters
    public void setStudentName(String name) {
        this.studentName = name;
    }

    public void setStudentId(int id) {
        this.studentId = id;
    }

    public void setQualifyingMarks(float marks) {
        this.qualifyingMarks = marks;
    }

    public void setYearOfEngineering(int year) {
        this.yearOfEngineering = year;
    }

    public void setResidentialStatus(char status) {
        this.residentialStatus = status;
    }

    // Getters
    public String getStudentName() {
        return studentName;
    }

    public int getStudentId() {
        return studentId;
    }

    public float getQualifyingMarks() {
        return qualifyingMarks;
    }

    public int getYearOfEngineering() {
        return yearOfEngineering;
    }

    public char getResidentialStatus() {
        return residentialStatus;
    }

    // Helper method to return residential status as full word
    public String getFullResidentialStatus() {
        if (residentialStatus == 'H' || residentialStatus == 'h') {
            return "Hostellers";
        } else if (residentialStatus == 'D' || residentialStatus == 'd') {
            return "Day Scholar";
        } else {
            return "Unknown";
        }
    }
}
```

### StudentTester.java

```java
public class StudentTester {

    public static void main(String[] args) {  // ✅ String must be capitalized
        Student student1 = new Student();
        student1.setStudentName("Jacob");
        student1.setStudentId(1001);
        student1.setQualifyingMarks(80.0f);
        student1.setYearOfEngineering(3);
        student1.setResidentialStatus('H');

        System.out.println("Student Name       :   " + student1.getStudentName());
        System.out.println("Student Id         :   " + student1.getStudentId());
        System.out.println("Qualifying marks   :   " + student1.getQualifyingMarks());
        System.out.println("Year of Engineering:   " + student1.getYearOfEngineering());
        System.out.println("Residential status :   " + student1.getFullResidentialStatus());
    }
}

```

## JShell - Java Shell Tool

**JShell** is an interactive **REPL (Read-Eval-Print Loop)** tool introduced in **Java 9**. It allows developers to write, evaluate, and test Java code snippets quickly without needing to create full classes or `main()` methods.

---

## 🔹 Key Features

- **Interactive**: Evaluate code line-by-line.
- **Lightweight**: No need for boilerplate Java code.
- **Quick Testing**: Great for trying new APIs or logic.
- **Beginner-Friendly**: Easy for learning Java syntax and behavior.
- **Prototyping Tool**: Efficient for rapid experimentation.

---

## 🛠️ How to Start JShell

Open terminal/command prompt and type:

```bash
jshell
```

```
jshell> int x = 10;
x ==> 10

jshell> x + 5
$2 ==> 15
```

### Why Use JShell?
- Explore Java features quickly.

- Learn Java without setting up full projects.

- Test logic or algorithms rapidly.

- Practice for interviews or experiments.

- Debug small snippets interactively.

## Java Operators

Java provides a rich set of operators to manipulate variables and values. Operators are special symbols or keywords that perform operations on one or more operands.

---

### 1. Arithmetic Operators

Used for basic mathematical operations.

| Operator | Description        | Example         | Result                  |
|----------|--------------------|-----------------|-------------------------|
| `+`      | Addition           | `5 + 3`         | `8`                     |
| `-`      | Subtraction        | `5 - 3`         | `2`                     |
| `*`      | Multiplication     | `5 * 3`         | `15`                    |
| `/`      | Division           | `10 / 2`        | `5`                     |
| `%`      | Modulus (remainder)| `10 % 3`        | `1`                     |
| `++`     | Increment          | `int x = 5; x++;` | `6` (x after increment) |
| `--`     | Decrement          | `int x = 5; x--;` | `4` (x after decrement) |

---

### 2. Relational Operators

Used to compare two values and return a boolean result.

| Operator | Description           | Example     | Result     |
|----------|-----------------------|-------------|------------|
| `==`     | Equal to              | `5 == 3`    | `false`    |
| `!=`     | Not equal to          | `5 != 3`    | `true`     |
| `>`      | Greater than          | `5 > 3`     | `true`     |
| `<`      | Less than             | `5 < 3`     | `false`    |
| `>=`     | Greater than or equal | `5 >= 5`    | `true`     |
| `<=`     | Less than or equal    | `5 <= 3`    | `false`    |

---

### 3. Logical Operators

Used with boolean (true/false) values.

| Operator | Description           | Example               | Result     |
|----------|-----------------------|-----------------------|------------|
| `&&`     | Logical AND           | `(5 > 3) && (2 < 4)`  | `true`     |
| `||`     | Logical OR            | `(5 > 3) || (2 > 4)`  | `true`     |
| `!`      | Logical NOT           | `!(5 > 3)`            | `false`    |

---

### 4. Assignment Operators

Used to assign values to variables.

| Operator | Description           | Example       | Result            |
|----------|-----------------------|---------------|-------------------|
| `=`      | Simple assignment     | `x = 5`       | `x` becomes 5     |
| `+=`     | Add and assign        | `x += 3`      | `x = x + 3`       |
| `-=`     | Subtract and assign   | `x -= 3`      | `x = x - 3`       |
| `*=`     | Multiply and assign   | `x *= 3`      | `x = x * 3`       |
| `/=`     | Divide and assign     | `x /= 3`      | `x = x / 3`       |
| `%=`     | Modulus and assign    | `x %= 3`      | `x = x % 3`       |

---

### 5. Bitwise Operators

Operate on bits and perform bit-level operations.

| Operator | Description          | Example    | Result        |
|----------|----------------------|------------|---------------|
| `&`      | Bitwise AND          | `5 & 3`    | `1`           |
| `|`      | Bitwise OR           | `5 \| 3`   | `7`           |
| `^`      | Bitwise XOR          | `5 ^ 3`    | `6`           |
| `~`      | Bitwise NOT          | `~5`       | `-6`          |
| `<<`     | Left shift           | `5 << 1`   | `10`          |
| `>>`     | Right shift          | `5 >> 1`   | `2`           |
| `>>>`    | Unsigned right shift | `5 >>> 1`  | `2`           |

---

### 6. Ternary Operator (Conditional)

Short-hand for an `if-else` statement.

```java
// variable = (condition) ? expression1 : expression2;
int a = 10, b = 20;
int max = (a > b) ? a : b;  // max will be 20
```

### 7. instanceof Operator
Tests whether an object is an instance of a specific class or implements an interface.

```java
String s = "Hello";
boolean result = s instanceof String;  // true
```

| Category      | Operators                           |                                  |         |
| ------------- | ----------------------------------- | -------------------------------- | ------- |
| Arithmetic    | `+`, `-`, `*`, `/`, `%`, `++`, `--` |                                  |         |
| Relational    | `==`, `!=`, `>`, `<`, `>=`, `<=`    |                                  |         |
| Logical       | `&&`, \`                            |                                  | `, `!\` |
| Assignment    | `=`, `+=`, `-=`, `*=`, `/=`, `%=`   |                                  |         |
| Bitwise       | `&`, \`                             | `, `^`, `\~`, `<<`, `>>`, `>>>\` |         |
| Ternary       | `? :`                               |                                  |         |
| Type Checking | `instanceof`                        |                                  |         |



## Java Data Types

In Java, data types specify the different sizes and values that can be stored in variables. Java is a **strongly typed language**, meaning every variable must be declared with a data type.

---

### 🔹 Categories of Data Types

Java has two main types of data types:

1. **Primitive Data Types**
2. **Non-Primitive (Reference/Object) Data Types**

---

## 1. Primitive Data Types

These are the most basic data types built into the Java language. There are **8 primitive types**, categorized as:

| Type     | Size      | Default Value | Description                            |
|----------|-----------|----------------|----------------------------------------|
| `byte`   | 1 byte    | 0              | Stores whole numbers from -128 to 127  |
| `short`  | 2 bytes   | 0              | Stores whole numbers from -32,768 to 32,767 |
| `int`    | 4 bytes   | 0              | Stores whole numbers from -2^31 to 2^31-1 |
| `long`   | 8 bytes   | 0L             | Stores large whole numbers from -2^63 to 2^63-1 |
| `float`  | 4 bytes   | 0.0f           | Stores decimal numbers, single precision |
| `double` | 8 bytes   | 0.0d           | Stores decimal numbers, double precision |
| `char`   | 2 bytes   | '\u0000'       | Stores a single character/letter or ASCII value |
| `boolean`| 1 bit     | false          | Stores only true or false              |

### 🧪 Examples:

```java
byte age = 25;
int salary = 50000;
float pi = 3.14f;
double largeValue = 123456.789;
char grade = 'A';
boolean isPassed = true;
```

### 2. Non-Primitive (Reference) Data Types
These refer to objects and are created by the programmer. They include:

Non-primitive types:
- Can be **null**
- Are **created by the programmer**
- **Store references** to memory locations (not the actual value)
- **Can have methods and properties**



- Strings
- Arrays
- Classes
- Interfaces
- Enums


### 🧪 Example Code for All Types

```java
// 1. String example
String message = "Hello, Java!";
System.out.println(message.toUpperCase()); // HELLO, JAVA!

// 2. Array example
int[] numbers = {10, 20, 30, 40};
System.out.println(numbers[2]); // Output: 30

// 3. Class example
class Student {
    String name;
    int age;
}

Student s1 = new Student();
s1.name = "Alice";
s1.age = 20;
System.out.println("Student Name: " + s1.name + ", Age: " + s1.age);

// 4. Interface example
interface Animal {
    void makeSound();
}

class Dog implements Animal {
    public void makeSound() {
        System.out.println("Bark");
    }
}

Dog dog = new Dog();
dog.makeSound(); // Bark

// 5. Enum example
enum Day {
    MONDAY, TUESDAY, WEDNESDAY
}

Day today = Day.MONDAY;
System.out.println(today); // MONDAY
```



## Java Typecasting

### What is Typecasting?

**Typecasting** in Java is the process of converting a variable from one data type to another. Java supports two types of typecasting:

---

### 1. Widening Typecasting (Implicit)

- Also known as **automatic type conversion**.
- Performed **automatically** when converting a smaller type to a larger type size.
- No data is lost.

#### Example

```java
int num = 10;
double d = num; // int to double
System.out.println(d); // Output: 10.0
```


```
byte → short → int → long → float → double
```


### Narrowing Typecasting (Explicit)

- Also known as manual type conversion.
- Must be done explicitly using a cast operator.
- There might be data loss or truncation.


```java
dataType variableName = (dataType) value;
```


```java
double d = 10.5;
int num = (int) d; // double to int
System.out.println(num); // Output: 10
```



```java
public class TypeCastingExample {
    public static void main(String[] args) {
        // Widening
        int a = 100;
        double b = a;
        System.out.println("Widening: " + b);

        // Narrowing
        double x = 55.89;
        int y = (int) x;
        System.out.println("Narrowing: " + y);
    }
}
```

## Java Conditional Statements

Java provides several types of conditional statements to control the flow of execution based on conditions.

---

### 1. if Statement

Executes a block of code if the condition is true.

```java
int number = 10;
if (number > 0) {
    System.out.println("The number is positive.");
}
```

---

### 2. if-else Statement

Executes one block if the condition is true, another if false.

```java
int number = -5;
if (number > 0) {
    System.out.println("Positive number.");
} else {
    System.out.println("Non-positive number.");
}
```

---

### 3. if-else-if Ladder

Multiple conditions are checked sequentially.

```java
int number = 0;
if (number > 0) {
    System.out.println("Positive");
} else if (number < 0) {
    System.out.println("Negative");
} else {
    System.out.println("Zero");
}
```

---

### 4. Nested if Statement

An `if` inside another `if` block.

```java
int number = 10;
if (number >= 0) {
    if (number == 0) {
        System.out.println("Zero");
    } else {
        System.out.println("Positive");
    }
}
```

---

### 5. switch Statement

Used to select one of many code blocks to be executed.

```java
int day = 3;
switch (day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    case 3:
        System.out.println("Wednesday");
        break;
    default:
        System.out.println("Invalid day");
}
```

---

### Summary Table

| Statement       | Description                                  |
|----------------|----------------------------------------------|
| `if`           | Executes block if condition is true          |
| `if-else`      | Chooses between two blocks                   |
| `if-else-if`   | Multiple condition checks                    |
| `nested if`    | `if` within `if` for multiple layers         |
| `switch`       | Checks value against multiple cases          |


## Java Loops

Loops in Java are used to execute a block of code repeatedly as long as a specified condition is true.

---

### 1. for Loop

The `for` loop is used when the number of iterations is known.

```java
for (int i = 1; i <= 5; i++) {
    System.out.println("Iteration: " + i);
}
```

---

### 2. while Loop

The `while` loop is used when the number of iterations is not known and depends on a condition.

```java
int i = 1;
while (i <= 5) {
    System.out.println("Iteration: " + i);
    i++;
}
```

---

### 3. do-while Loop

The `do-while` loop is similar to the `while` loop, but it guarantees that the loop body is executed at least once.

```java
int i = 1;
do {
    System.out.println("Iteration: " + i);
    i++;
} while (i <= 5);
```

---

### 4. Enhanced for Loop (for-each)

Used to iterate over arrays or collections easily.

```java
int[] numbers = {1, 2, 3, 4, 5};
for (int num : numbers) {
    System.out.println("Number: " + num);
}
```

---

### 5. break Statement

Used to exit a loop prematurely when a certain condition is met.

```java
for (int i = 1; i <= 10; i++) {
    if (i == 6) {
        break;
    }
    System.out.println("i = " + i);
}
```

**Output:**
```
i = 1
i = 2
i = 3
i = 4
i = 5
```

---

### 6. continue Statement

Skips the current iteration and moves to the next one.

```java
for (int i = 1; i <= 5; i++) {
    if (i == 3) {
        continue;
    }
    System.out.println("i = " + i);
}
```

**Output:**
```
i = 1
i = 2
i = 4
i = 5
```

---

### Summary Table

| Loop Type         | Description                                      | Use Case                              |
|-------------------|--------------------------------------------------|----------------------------------------|
| `for`             | Repeats with a counter                           | Known number of iterations             |
| `while`           | Repeats while condition is true                  | Unknown number of iterations           |
| `do-while`        | Like `while`, but runs at least once             | Must execute at least one iteration    |
| `for-each`        | Iterates over collections/arrays                 | Array or collection traversal          |
| `break`           | Exits loop early when condition is met           | Early termination                      |
| `continue`        | Skips to next iteration                          | Skip specific cases during looping     |


## Java Arrays

An array in Java is a container object that holds a fixed number of values of a single type.

---

### 1. Declaring and Creating an Array

```java
int[] numbers = new int[5]; // creates an array of size 5
```

---

### 2. Initializing an Array

```java
int[] numbers = {10, 20, 30, 40, 50};
```

---

### 3. Accessing Array Elements

```java
System.out.println(numbers[0]); // Output: 10
System.out.println(numbers[2]); // Output: 30
```

---

### 4. Modifying Array Elements

```java
numbers[1] = 25; // Change 20 to 25
System.out.println(numbers[1]); // Output: 25
```

---

### 5. Iterating Over an Array (using for loop)

```java
for (int i = 0; i < numbers.length; i++) {
    System.out.println("Element at index " + i + ": " + numbers[i]);
}
```

---

### 6. Iterating Over an Array (using for-each loop)

```java
for (int num : numbers) {
    System.out.println("Element: " + num);
}
```

---

### 7. Length of an Array

```java
System.out.println("Array length: " + numbers.length);
```

---

### 8. Multidimensional Arrays

```java
int[][] matrix = {
    {1, 2, 3},
    {4, 5, 6}
};

System.out.println(matrix[0][1]); // Output: 2
```

---

### 9. Iterating Over 2D Arrays

```java
for (int i = 0; i < matrix.length; i++) {
    for (int j = 0; j < matrix[i].length; j++) {
        System.out.print(matrix[i][j] + " ");
    }
    System.out.println();
}
```

---

### Summary Table

| Concept               | Example                                       |
|------------------------|-----------------------------------------------|
| Declaration            | `int[] arr;`                                  |
| Creation               | `new int[5]`                                  |
| Initialization         | `int[] arr = {1, 2, 3};`                      |
| Access/Modify          | `arr[0]`, `arr[1] = 10;`                      |
| Length                 | `arr.length`                                  |
| Loop (for)             | `for (int i = 0; i < arr.length; i++)`       |
| Loop (for-each)        | `for (int a : arr)`                           |
| 2D Array               | `int[][] matrix = new int[2][3];`            |


## Java Access Modifiers

Access modifiers in Java specify the accessibility (scope) of classes, methods, constructors, and other members.

Java provides four access modifiers:

---

### 1. `private`

- Accessible **only within the same class**.
- Not accessible from other classes, even subclasses.

```java
public class Example {
    private int data = 10;

    private void showData() {
        System.out.println("Data: " + data);
    }
}
```

---

### 2. `default` (no modifier)

- Accessible **within the same package**.
- Not accessible from outside the package.

```java
class Example {
    void display() {
        System.out.println("Default access method");
    }
}
```

---

### 3. `protected`

- Accessible **within the same package** and **by subclasses** in other packages.

```java
public class Example {
    protected int value = 42;

    protected void show() {
        System.out.println("Value: " + value);
    }
}
```

---

### 4. `public`

- Accessible from **anywhere** in the program.

```java
public class Example {
    public void greet() {
        System.out.println("Hello, World!");
    }
}
```

---

### Access Modifier Scope Table

| Modifier    | Class | Package | Subclass | World |
|-------------|:-----:|:-------:|:--------:|:-----:|
| `private`   |  ✅   |    ❌    |    ❌     |  ❌   |
| *(default)* |  ✅   |   ✅     |    ❌     |  ❌   |
| `protected` |  ✅   |   ✅     |   ✅      |  ❌   |
| `public`    |  ✅   |   ✅     |   ✅      |  ✅   |

---

### Notes

- Only **one public class** is allowed per `.java` file, and the file name must match the public class name.
- Use `private` for encapsulation.
- Use `protected` when designing inheritance across packages.
- Use `public` for classes or APIs that need to be accessed universally.

## Java Constructors

A **constructor** in Java is a special method used to initialize objects. It is called when an object of a class is created.

---

### Key Characteristics

- Constructor name must match the class name.
- It **does not have a return type**, not even `void`.
- It is **automatically called** when an object is created.

---

### 1. Default Constructor

A constructor that takes no arguments. If no constructor is defined, Java provides one by default.

```java
public class Car {
    Car() {
        System.out.println("Car object created.");
    }

    public static void main(String[] args) {
        Car c = new Car(); // Calls the default constructor
    }
}
```

---

### 2. Parameterized Constructor

Takes arguments to initialize the object with custom values.

```java
public class Car {
    String model;

    Car(String modelName) {
        model = modelName;
    }

    public static void main(String[] args) {
        Car c = new Car("Tesla");
        System.out.println("Model: " + c.model);
    }
}
```

---

### 3. Constructor Overloading

You can define multiple constructors in the same class with different parameter lists.

```java
public class Car {
    String model;
    int year;

    // Default constructor
    Car() {
        model = "Unknown";
        year = 0;
    }

    // Parameterized constructor
    Car(String modelName, int modelYear) {
        model = modelName;
        year = modelYear;
    }

    public void display() {
        System.out.println(model + " - " + year);
    }

    public static void main(String[] args) {
        Car c1 = new Car();
        Car c2 = new Car("Honda", 2022);

        c1.display(); // Unknown - 0
        c2.display(); // Honda - 2022
    }
}
```

---

### 4. Copy Constructor (Custom Implementation)

Java doesn't have a built-in copy constructor, but you can define one manually.

```java
public class Car {
    String model;

    Car(String modelName) {
        model = modelName;
    }

    // Copy constructor
    Car(Car other) {
        this.model = other.model;
    }

    public static void main(String[] args) {
        Car original = new Car("Ford");
        Car copy = new Car(original);

        System.out.println("Original: " + original.model);
        System.out.println("Copy: " + copy.model);
    }
}
```

---

### Summary Table

| Type                   | Description                                      |
|------------------------|--------------------------------------------------|
| Default Constructor    | No parameters; auto-provided if none defined     |
| Parameterized          | Accepts arguments to set initial values          |
| Overloaded Constructor | Multiple constructors with different parameters  |
| Copy Constructor       | Copies values from another object (manual)       |

---

### Notes

- Constructors can call other constructors using `this()`.
- If any constructor is explicitly declared, the default constructor is **not provided automatically**.
- Constructors **can’t be `static`, `final`, or `abstract`**.

## Java `this` Keyword

The `this` keyword in Java is a reference variable that refers to the **current object** of a class.

---

### 1. Referring to Instance Variables

When a method parameter or local variable has the same name as an instance variable, `this` is used to distinguish them.

```java
public class Student {
    String name;

    Student(String name) {
        this.name = name; // 'this.name' refers to instance variable
    }

    public void display() {
        System.out.println("Name: " + this.name);
    }

    public static void main(String[] args) {
        Student s = new Student("Alice");
        s.display(); // Output: Name: Alice
    }
}
```

---

### 2. Calling Another Constructor in the Same Class

Use `this()` to call another constructor from within a constructor. Must be the **first statement**.

```java
public class Student {
    String name;
    int age;

    Student(String name) {
        this(name, 18); // Calls the other constructor
    }

    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public void display() {
        System.out.println(name + " - " + age);
    }

    public static void main(String[] args) {
        Student s = new Student("Bob");
        s.display(); // Output: Bob - 18
    }
}
```

---

### 3. Returning the Current Class Instance

`this` can be returned from a method to enable **method chaining**.

```java
public class Student {
    String name;

    Student setName(String name) {
        this.name = name;
        return this;
    }

    void display() {
        System.out.println("Name: " + name);
    }

    public static void main(String[] args) {
        new Student().setName("Charlie").display();
    }
}
```

---

### 4. Passing `this` as a Method Argument

You can pass the current object as an argument to another method.

```java
public class Student {
    void print(Student s) {
        System.out.println("Method received object: " + s);
    }

    void callPrint() {
        print(this); // passing current object
    }

    public static void main(String[] args) {
        Student s = new Student();
        s.callPrint();
    }
}
```

---

### 5. Using `this` with Inner Classes

To distinguish the outer class reference from inner class context.

```java
public class Outer {
    int x = 10;

    class Inner {
        int x = 20;

        void print() {
            System.out.println("Inner x: " + x);
            System.out.println("Outer x: " + Outer.this.x);
        }
    }

    public static void main(String[] args) {
        Outer.Inner obj = new Outer().new Inner();
        obj.print();
    }
}
```

---

### Summary Table

| Use Case                            | Description                                       |
|-------------------------------------|---------------------------------------------------|
| `this.variable`                     | Refers to current object's instance variable      |
| `this()`                            | Calls another constructor in the same class       |
| `return this`                       | Returns current object (method chaining)          |
| `this` as argument                  | Pass current object to methods or constructors    |
| `Outer.this`                        | Refers to outer class from inner class            |

---

### Notes

- Cannot use `this` in static methods because `this` refers to an object, and static methods do not belong to an object.
- `this()` must be the **first line** in a constructor if used.


## Java Packages

A **package** in Java is a namespace that organizes a set of related classes and interfaces. It helps avoid name conflicts and makes classes easier to locate and use.

---

### Types of Packages

1. **Built-in Packages** – Provided by Java (e.g., `java.util`, `java.io`)
2. **User-defined Packages** – Created by the programmer

---

### 1. Declaring a Package

The `package` keyword is used at the top of a Java source file.

```java
package mypackage;

public class MyClass {
    public void display() {
        System.out.println("Inside mypackage");
    }
}
```

---

### 2. Using a Class from Another Package

Use the `import` statement to access classes from other packages.

**Example: Using a user-defined package**

```java
import mypackage.MyClass;

public class Test {
    public static void main(String[] args) {
        MyClass obj = new MyClass();
        obj.display();
    }
}
```

> 💡 Make sure the class files are compiled and in the correct directory structure:
> ```
> mypackage/MyClass.java
> Test.java
> ```

Compile with:
```
javac mypackage/MyClass.java
javac -cp . Test.java
```

Run with:
```
java Test
```

---

### 3. Accessing Built-in Packages

```java
import java.util.Scanner;

public class InputExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter your name: ");
        String name = sc.nextLine();
        System.out.println("Hello, " + name);
    }
}
```

---

### 4. Static Import

You can import static members of a class to use them without class reference.

```java
import static java.lang.Math.*;

public class StaticImportExample {
    public static void main(String[] args) {
        System.out.println(sqrt(16)); // no need to use Math.sqrt()
        System.out.println(PI);       // directly access PI
    }
}
```

---

### Advantages of Packages

- **Modularity** – Helps organize code better.
- **Reusability** – Classes in packages can be reused across projects.
- **Encapsulation** – Provides access protection.
- **Namespace Management** – Avoids class name conflicts.

---

### Summary Table

| Feature             | Example                           |
|---------------------|------------------------------------|
| Declare a package   | `package mypackage;`               |
| Import a class      | `import mypackage.MyClass;`        |
| Import all classes  | `import mypackage.*;`              |
| Static import        | `import static java.lang.Math.*;` |
| Built-in package    | `import java.util.*;`              |

---

### Notes

- The package name must match the directory structure.
- The `package` statement **must be the first statement** in the file (except comments).
- To compile classes in packages, directory paths must reflect the package name.

## Java `static` Modifier

The `static` modifier in Java is used for memory management. It can be applied to variables, methods, blocks, and nested classes. Static members belong to the **class** rather than to any particular instance.

---

### 1. Static Variables (Class Variables)

- Shared among all instances of the class.
- Only one copy exists regardless of the number of objects created.

```java
public class Counter {
    static int count = 0;

    Counter() {
        count++;
    }

    public static void main(String[] args) {
        Counter c1 = new Counter();
        Counter c2 = new Counter();
        System.out.println("Count: " + Counter.count); // Output: Count: 2
    }
}
```

---

### 2. Static Methods

- Can be called without creating an instance of the class.
- Can only directly access other static members.
- Cannot use `this` or `super` keywords.

```java
public class MathUtil {
    public static int square(int num) {
        return num * num;
    }

    public static void main(String[] args) {
        int result = MathUtil.square(5);
        System.out.println("Square of 5 is " + result);
    }
}
```

---

### 3. Static Blocks

- Used for static initialization.
- Executed once when the class is loaded.

```java
public class InitExample {
    static int data;

    static {
        data = 50;
        System.out.println("Static block executed.");
    }

    public static void main(String[] args) {
        System.out.println("Data: " + data);
    }
}
```

---

### 4. Static Nested Classes

- Nested classes declared static do not require an instance of the outer class.
- Can access static members of the outer class.

```java
public class Outer {
    static int outerData = 100;

    static class Inner {
        void display() {
            System.out.println("Outer data is " + outerData);
        }
    }

    public static void main(String[] args) {
        Outer.Inner obj = new Outer.Inner();
        obj.display();
    }
}
```

---

### Summary Table

| Static Member       | Description                                      | Access                                    |
|---------------------|-------------------------------------------------|-------------------------------------------|
| Static Variable     | Shared across all instances                      | Access via class name or object           |
| Static Method       | Belongs to class; no instance needed             | Can access only static members directly   |
| Static Block        | Runs once when class loads                        | Used for initialization                    |
| Static Nested Class | Nested class that doesn’t need outer instance    | Can access outer class’s static members    |

---

### Notes

- Static members are loaded into memory once at class load time.
- Non-static members require object instances.
- Avoid using static variables for data that should be unique to each object.

## Java `super` Keyword

The `super` keyword in Java is a reference variable used to refer to the **immediate parent class** object. It is commonly used in **inheritance** to access parent class methods, constructors, or variables.

---

### Use Cases of `super`

1. **Access parent class variables**
2. **Call parent class methods**
3. **Invoke parent class constructor**

---

### 1. Accessing Parent Class Variables

If a subclass has a variable with the same name as the parent, use `super` to refer to the parent class variable.

```java
class Animal {
    String name = "Animal";
}

class Dog extends Animal {
    String name = "Dog";

    void printNames() {
        System.out.println("Child name: " + name);
        System.out.println("Parent name: " + super.name);
    }

    public static void main(String[] args) {
        Dog d = new Dog();
        d.printNames();
    }
}
```

**Output:**
```
Child name: Dog
Parent name: Animal
```

---

### 2. Calling Parent Class Methods

Use `super.methodName()` to call a method from the parent class that is overridden in the child class.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
        super.sound(); // Call parent class method
    }

    public static void main(String[] args) {
        Dog d = new Dog();
        d.sound();
    }
}
```

**Output:**
```
Dog barks
Animal makes a sound
```

---

### 3. Calling Parent Class Constructor

Use `super()` to call the constructor of the parent class. It must be the **first statement** in the subclass constructor.

```java
class Animal {
    Animal() {
        System.out.println("Animal constructor called");
    }
}

class Dog extends Animal {
    Dog() {
        super(); // Call parent constructor
        System.out.println("Dog constructor called");
    }

    public static void main(String[] args) {
        Dog d = new Dog();
    }
}
```

**Output:**
```
Animal constructor called
Dog constructor called
```

---

### Summary Table

| Usage                     | Purpose                                             |
|---------------------------|-----------------------------------------------------|
| `super.variable`          | Access parent class variable                        |
| `super.method()`          | Call parent class method                            |
| `super()`                 | Call parent class constructor                       |

---

### Notes

- `super()` must be the **first line** in the subclass constructor.
- Cannot be used in static contexts.
- Helps avoid code duplication by reusing parent class functionality.


## Java Inheritance

Inheritance is one of the key features of Object-Oriented Programming (OOP) in Java. It allows a new class (subclass) to inherit fields and methods from an existing class (superclass).

---

### Why Use Inheritance?

- **Code Reusability**: Avoid duplicating common code.
- **Extensibility**: Easily extend existing behavior.
- **Method Overriding**: Redefine inherited methods.
- **Polymorphism**: Parent class reference can point to child objects.

---

### Basic Syntax

```java
class Superclass {
    // fields and methods
}

class Subclass extends Superclass {
    // additional fields and methods
}
```

---

### Example: Animal and Dog

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal a = new Animal();
        a.sound();

        Dog d = new Dog();
        d.sound();

        Animal ref = new Dog();
        ref.sound();
    }
}
```

**Output:**
```
Animal makes a sound
Dog barks
Dog barks
```

---

### Types of Inheritance

Java supports the following types of inheritance:

- Single Inheritance
- Multilevel Inheritance
- Hierarchical Inheritance

Java does **not** support **multiple inheritance with classes**, but it does via interfaces.

---

#### Single Inheritance

```java
class Parent {
    void show() {
        System.out.println("Parent class");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child class");
    }
}
```

---

#### Multilevel Inheritance

```java
class Grandparent {
    void greet() {
        System.out.println("Grandparent class");
    }
}

class Parent extends Grandparent {
    void show() {
        System.out.println("Parent class");
    }
}

class Child extends Parent {
    void display() {
        System.out.println("Child class");
    }
}
```

---

#### Hierarchical Inheritance

```java
class Animal {
    void eat() {
        System.out.println("This animal eats food");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Dog barks");
    }
}

class Cat extends Animal {
    void meow() {
        System.out.println("Cat meows");
    }
}
```

---

### The `super` Keyword

The `super` keyword refers to the immediate parent class. It is used to:

- Call the parent class method
- Access the parent class variable
- Call the parent class constructor

---

#### Call Parent Method

```java
class Animal {
    void sound() {
        System.out.println("Animal sound");
    }
}

class Dog extends Animal {
    void sound() {
        super.sound();
        System.out.println("Dog barks");
    }
}
```

**Output:**
```
Animal sound
Dog barks
```

---

#### Call Parent Constructor

```java
class Animal {
    Animal() {
        System.out.println("Animal constructor");
    }
}

class Dog extends Animal {
    Dog() {
        super(); // must be the first statement
        System.out.println("Dog constructor");
    }
}
```

**Output:**
```
Animal constructor
Dog constructor
```

---

### Summary Table

| Concept              | Description                                 |
|----------------------|---------------------------------------------|
| `extends`            | Inherit from another class                  |
| `super`              | Reference parent class                      |
| Method Overriding    | Redefine method from superclass             |
| Polymorphism         | Parent reference → child object             |

---

### Conclusion

Inheritance is essential in Java for building maintainable and reusable object-oriented code. It enables hierarchical relationships, method overriding, and polymorphism, which together lead to more flexible and scalable applications.


## Java Polymorphism

Polymorphism is a core concept of Object-Oriented Programming (OOP) that allows objects of different classes to be treated as objects of a common superclass. It enables a single method or interface to operate on different types of objects.

---

### Types of Polymorphism in Java

1. **Compile-time Polymorphism (Method Overloading)**
2. **Run-time Polymorphism (Method Overriding)**

---

### 1. Compile-time Polymorphism (Method Overloading)

In method overloading, multiple methods in the same class have the same name but different parameter lists.

```java
class Calculator {
    int add(int a, int b) {
        return a + b;
    }

    double add(double a, double b) {
        return a + b;
    }

    int add(int a, int b, int c) {
        return a + b + c;
    }
}

public class Main {
    public static void main(String[] args) {
        Calculator calc = new Calculator();
        System.out.println(calc.add(2, 3));
        System.out.println(calc.add(2.5, 3.5));
        System.out.println(calc.add(1, 2, 3));
    }
}
```

**Output:**
```
5
6.0
6
```

---

### 2. Run-time Polymorphism (Method Overriding)

In method overriding, a subclass provides a specific implementation of a method that is already defined in its superclass.

```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}

class Cat extends Animal {
    @Override
    void sound() {
        System.out.println("Cat meows");
    }
}

public class Main {
    public static void main(String[] args) {
        Animal a;

        a = new Dog();
        a.sound();  // Dog barks

        a = new Cat();
        a.sound();  // Cat meows
    }
}
```

**Output:**
```
Dog barks
Cat meows
```

---

### Key Benefits of Polymorphism

- **Extensibility**: Easily extend functionality by overriding methods.
- **Maintainability**: Write cleaner and more manageable code.
- **Flexibility**: Code can work with objects of different types through a common interface or superclass.

---

### Summary Table

| Type                   | Description                                  | Example            |
|------------------------|----------------------------------------------|--------------------|
| Method Overloading     | Same method name, different parameters       | `add(int, int)` vs `add(double, double)` |
| Method Overriding      | Subclass changes behavior of superclass method | `Dog.sound()` overrides `Animal.sound()` |
| Polymorphic Behavior   | Parent reference points to child object      | `Animal a = new Dog();` |

---

### Conclusion

Polymorphism increases the flexibility and scalability of Java programs by allowing the same interface or method to behave differently based on the object at runtime. It works closely with inheritance and interfaces to support powerful object-oriented design.

## Java `final` Keyword

The `final` keyword in Java is used to restrict modification. It can be applied to **variables**, **methods**, and **classes**.

---

### Uses of `final` Keyword

- **Final Variable**: Value cannot be changed (constant).
- **Final Method**: Cannot be overridden by subclasses.
- **Final Class**: Cannot be inherited.

---

### 1. Final Variable

Once assigned, a final variable cannot be reassigned.

```java
class Example {
    final int MAX_VALUE = 100;

    void show() {
        // MAX_VALUE = 200; // Error: cannot assign a value to final variable
        System.out.println("Max value: " + MAX_VALUE);
    }
}
```

**Output:**
```
Max value: 100
```

---

### 2. Final Method

A method declared as final cannot be overridden in a subclass.

```java
class Parent {
    final void display() {
        System.out.println("This is a final method.");
    }
}

class Child extends Parent {
    // void display() {   // Error: Cannot override final method
    //     System.out.println("Attempting to override.");
    // }
}
```

---

### 3. Final Class

A final class cannot be extended by any other class.

```java
final class ConstantClass {
    void show() {
        System.out.println("Final class method");
    }
}

// class SubClass extends ConstantClass { // Error: cannot inherit from final class
// }
```

---

### Final with Reference Variables

Final reference variables cannot be reassigned to another object, but their internal state can still be changed (if mutable).

```java
class Book {
    String title = "Java";

    void setTitle(String t) {
        this.title = t;
    }
}

public class Main {
    public static void main(String[] args) {
        final Book b = new Book();
        b.setTitle("Advanced Java"); // allowed
        // b = new Book();           // Error: cannot assign a new object
        System.out.println(b.title);
    }
}
```

**Output:**
```
Advanced Java
```

---

### Summary Table

| Usage           | Effect                                       |
|------------------|-----------------------------------------------|
| `final` variable | Value cannot be changed after initialization  |
| `final` method   | Cannot be overridden in a subclass            |
| `final` class    | Cannot be inherited                           |

---

### Conclusion

The `final` keyword is useful for defining constants, securing methods from being overridden, and preventing classes from being extended. It helps enforce immutability and protects critical parts of your code.


## Java `abstract` Keyword

The `abstract` keyword in Java is used to define **abstract classes** and **abstract methods**. These are meant to be **incomplete** and must be **extended or implemented** by other classes.

---

### Key Points

- An **abstract class** cannot be instantiated.
- An **abstract method** has no body and must be implemented in a subclass.
- An abstract class can have both abstract and concrete (regular) methods.
- If a class has one or more abstract methods, it must be declared abstract.

---

### 1. Abstract Class and Method

```java
abstract class Animal {
    abstract void sound(); // abstract method

    void eat() {
        System.out.println("This animal eats food");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}
```

---

### 2. Usage Example

```java
public class Main {
    public static void main(String[] args) {
        // Animal a = new Animal(); // Error: Cannot instantiate abstract class
        Animal dog = new Dog();
        dog.sound(); // Output: Dog barks
        dog.eat();   // Output: This animal eats food
    }
}
```

**Output:**
```
Dog barks
This animal eats food
```

---

### 3. Abstract Class with Constructor and Fields

Abstract classes can have constructors, fields, and methods with implementations.

```java
abstract class Vehicle {
    String type;

    Vehicle(String type) {
        this.type = type;
    }

    abstract void start();

    void displayType() {
        System.out.println("Vehicle type: " + type);
    }
}

class Car extends Vehicle {
    Car() {
        super("Car");
    }

    @Override
    void start() {
        System.out.println("Car starts with a key");
    }
}
```

---

### 4. Abstract vs Interface (Comparison)

| Feature              | Abstract Class                  | Interface                          |
|----------------------|----------------------------------|-------------------------------------|
| Can have constructors| Yes                             | No                                  |
| Can have fields      | Yes (with state)                | Yes (implicitly `public static final`) |
| Multiple inheritance | No                              | Yes                                 |
| Method body allowed  | Yes                             | Yes (from Java 8 using `default`)   |

---

### Summary

- Use **abstract classes** when you want to share code among several closely related classes.
- Use **abstract methods** when you want subclasses to provide specific implementations.
- Abstract classes help define a common base with shared logic and force subclasses to complete the contract.

---

### Conclusion

The `abstract` keyword in Java supports partial abstraction. It allows you to define a base template for other classes while forcing implementation of key behaviors in subclasses. This promotes consistency and reuse in your code structure.


## Java `interface`

An `interface` in Java is a reference type that contains only **abstract methods**, **default methods**, **static methods**, and **constants**. It is used to achieve **100% abstraction** and **multiple inheritance**.

---

### Key Characteristics

- All methods in an interface are **public** and **abstract** by default (except `default` and `static` methods).
- All fields are **public**, **static**, and **final** by default.
- A class **implements** an interface, not extends it.
- A class can **implement multiple interfaces**.

---

### 1. Basic Interface Example

```java
interface Animal {
    void sound(); // abstract method
}

class Dog implements Animal {
    @Override
    public void sound() {
        System.out.println("Dog barks");
    }
}
```

```java
public class Main {
    public static void main(String[] args) {
        Animal a = new Dog();
        a.sound();
    }
}
```

**Output:**
```
Dog barks
```

---

### 2. Interface with Constants

```java
interface Config {
    int MAX_USERS = 100; // public static final by default
}
```

---

### 3. Interface with `default` and `static` Methods (Java 8+)

```java
interface Vehicle {
    void start();

    default void stop() {
        System.out.println("Vehicle stopped");
    }

    static void clean() {
        System.out.println("Vehicle cleaned");
    }
}

class Car implements Vehicle {
    @Override
    public void start() {
        System.out.println("Car started");
    }
}
```

```java
public class Main {
    public static void main(String[] args) {
        Car c = new Car();
        c.start();
        c.stop();
        Vehicle.clean();
    }
}
```

**Output:**
```
Car started
Vehicle stopped
Vehicle cleaned
```

---

### 4. Multiple Interfaces

```java
interface Printable {
    void print();
}

interface Scannable {
    void scan();
}

class MultiFunctionPrinter implements Printable, Scannable {
    public void print() {
        System.out.println("Printing document");
    }

    public void scan() {
        System.out.println("Scanning document");
    }
}
```

---

### Interface vs Abstract Class

| Feature              | Interface                              | Abstract Class                        |
|----------------------|-----------------------------------------|----------------------------------------|
| Multiple Inheritance | Yes                                     | No                                     |
| Constructors         | No                                      | Yes                                    |
| Access Modifiers     | Only `public`                           | Can be any access modifier             |
| Fields               | `public static final` by default        | Instance variables allowed             |
| Method Bodies        | `default`/`static` (Java 8+), not regular| Yes (concrete and abstract methods)    |

---

### Summary

- Use **interfaces** to define capabilities or contracts (e.g., `Flyable`, `Runnable`).
- A class can **implement multiple interfaces** to inherit multiple behaviors.
- Interfaces promote **loose coupling** and **testability**.

---

### Conclusion

Interfaces in Java enable abstraction and multiple inheritance. They are a powerful way to define a contract that multiple classes can follow, promoting a clean and maintainable design.


## Java Sealed Classes and Interfaces

Sealed classes and interfaces restrict which other classes or interfaces may extend or implement them. This feature enhances **encapsulation** and **maintains control** over the class hierarchy.

---

### Why Use Sealed Classes/Interfaces?

- Control which classes can subclass or implement them.
- Improve security and maintainability.
- Useful in modeling restricted class hierarchies.

---

### Syntax Overview

- Use the `sealed` keyword to declare a class or interface as sealed.
- Use the `permits` clause to specify allowed subclasses or implementors.
- Subclasses of a sealed class must be declared as:
  - `final` (cannot be subclassed further),
  - `sealed` (further restrict subclassing), or
  - `non-sealed` (open to unrestricted subclassing).

---

### Example: Sealed Class

```java
public sealed class Vehicle permits Car, Truck {
    void start() {
        System.out.println("Vehicle starting");
    }
}

public final class Car extends Vehicle {
    @Override
    void start() {
        System.out.println("Car starting");
    }
}

public non-sealed class Truck extends Vehicle {
    @Override
    void start() {
        System.out.println("Truck starting");
    }
}
```

---

### Example: Sealed Interface

```java
public sealed interface Shape permits Circle, Rectangle {
    double area();
}

public final class Circle implements Shape {
    private double radius;

    public Circle(double radius) {
        this.radius = radius;
    }

    public double area() {
        return Math.PI * radius * radius;
    }
}

public non-sealed class Rectangle implements Shape {
    private double width, height;

    public Rectangle(double width, double height) {
        this.width = width;
        this.height = height;
    }

    public double area() {
        return width * height;
    }
}
```

---

### Notes

- Sealed classes/interfaces were introduced in **Java 15 (preview)** and became a standard feature in **Java 17**.
- The `permits` clause must explicitly list all permitted subclasses or implementors.
- Subclasses must explicitly specify their nature: `final`, `sealed`, or `non-sealed`.

---

### Summary Table

| Modifier      | Meaning                                  |
|---------------|------------------------------------------|
| `sealed`      | Restricts subclassing to specified types |
| `permits`     | Lists allowed subclasses or implementors |
| `final`       | No further subclassing allowed            |
| `non-sealed`  | Removes restriction, allows unrestricted subclassing |

---

### Conclusion

Sealed classes and interfaces provide fine-grained control over inheritance and implementation, making class hierarchies safer and easier to reason about. Use them when you want to tightly control which classes can extend or implement your types.


## Java Enum (Enumerated Data Type)

An `enum` in Java is a special data type used to define a set of named constants. It is useful when you have a fixed set of related values like days, directions, statuses, etc.

---

### Key Characteristics

- Enums are **type-safe**.
- Enums can have **fields**, **constructors**, and **methods**.
- Enum constants are implicitly `public`, `static`, and `final`.

---

### 1. Basic Enum Example

```java
enum Day {
    MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY, SUNDAY
}

public class Main {
    public static void main(String[] args) {
        Day today = Day.FRIDAY;

        switch (today) {
            case MONDAY -> System.out.println("Start of the week");
            case FRIDAY -> System.out.println("Almost weekend");
            case SUNDAY -> System.out.println("Rest day");
            default -> System.out.println("Midweek day");
        }
    }
}
```

**Output:**
```
Almost weekend
```

---

### 2. Enum with Fields and Constructor

```java
enum Planet {
    MERCURY(3.303e+23, 2.4397e6),
    EARTH(5.976e+24, 6.37814e6),
    MARS(6.421e+23, 3.3972e6);

    private final double mass;   // in kilograms
    private final double radius; // in meters

    Planet(double mass, double radius) {
        this.mass = mass;
        this.radius = radius;
    }

    double surfaceGravity() {
        final double G = 6.67300E-11;
        return G * mass / (radius * radius);
    }

    double surfaceWeight(double otherMass) {
        return otherMass * surfaceGravity();
    }
}

public class Main {
    public static void main(String[] args) {
        for (Planet p : Planet.values()) {
            System.out.printf("Gravity on %s: %.2f%n", p, p.surfaceGravity());
        }
    }
}
```

**Output:**
```
Gravity on MERCURY: 3.70
Gravity on EARTH: 9.80
Gravity on MARS: 3.71
```

---

### 3. Enum with Custom Methods

```java
enum Status {
    NEW, PROCESSING, COMPLETED, FAILED;

    boolean isFinal() {
        return this == COMPLETED || this == FAILED;
    }
}

public class Main {
    public static void main(String[] args) {
        Status s = Status.COMPLETED;

        System.out.println("Is final: " + s.isFinal());
    }
}
```

**Output:**
```
Is final: true
```

---

### Summary Table

| Feature                   | Enum Support |
|---------------------------|--------------|
| Constants                 | Yes          |
| Methods                   | Yes          |
| Fields                    | Yes          |
| Constructors              | Yes (private only) |
| Implements interfaces     | Yes          |
| Extends classes           | No (implicitly extends `java.lang.Enum`) |

---

### Conclusion

Java Enums are powerful tools for defining a fixed set of constants. They support fields, methods, and even interface implementation, making them ideal for modeling well-defined data sets with behavior.


## Java Enum (Enumerated Data Type)

An `enum` in Java is a special data type used to define a set of named constants. It is useful when you have a fixed set of related values like days, directions, statuses, etc.

---

### Key Characteristics

- Enums are **type-safe**.
- Enums can have **fields**, **constructors**, and **methods**.
- Enum constants are implicitly `public`, `static`, and `final`.

---

### 1. Basic Enum Example

```java
enum Day {
    MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY, SUNDAY
}

public class Main {
    public static void main(String[] args) {
        Day today = Day.FRIDAY;

        switch (today) {
            case MONDAY -> System.out.println("Start of the week");
            case FRIDAY -> System.out.println("Almost weekend");
            case SUNDAY -> System.out.println("Rest day");
            default -> System.out.println("Midweek day");
        }
    }
}
```

**Output:**
```
Almost weekend
```

---

### 2. Enum with Fields and Constructor

```java
enum Planet {
    MERCURY(3.303e+23, 2.4397e6),
    EARTH(5.976e+24, 6.37814e6),
    MARS(6.421e+23, 3.3972e6);

    private final double mass;   // in kilograms
    private final double radius; // in meters

    Planet(double mass, double radius) {
        this.mass = mass;
        this.radius = radius;
    }

    double surfaceGravity() {
        final double G = 6.67300E-11;
        return G * mass / (radius * radius);
    }

    double surfaceWeight(double otherMass) {
        return otherMass * surfaceGravity();
    }
}

public class Main {
    public static void main(String[] args) {
        for (Planet p : Planet.values()) {
            System.out.printf("Gravity on %s: %.2f%n", p, p.surfaceGravity());
        }
    }
}
```

**Output:**
```
Gravity on MERCURY: 3.70
Gravity on EARTH: 9.80
Gravity on MARS: 3.71
```

---

### 3. Enum with Custom Methods

```java
enum Status {
    NEW, PROCESSING, COMPLETED, FAILED;

    boolean isFinal() {
        return this == COMPLETED || this == FAILED;
    }
}

public class Main {
    public static void main(String[] args) {
        Status s = Status.COMPLETED;

        System.out.println("Is final: " + s.isFinal());
    }
}
```

**Output:**
```
Is final: true
```

---

### Summary Table

| Feature                   | Enum Support |
|---------------------------|--------------|
| Constants                 | Yes          |
| Methods                   | Yes          |
| Fields                    | Yes          |
| Constructors              | Yes (private only) |
| Implements interfaces     | Yes          |
| Extends classes           | No (implicitly extends `java.lang.Enum`) |

---

### Conclusion

Java Enums are powerful tools for defining a fixed set of constants. They support fields, methods, and even interface implementation, making them ideal for modeling well-defined data sets with behavior.


## Java `String` Class

In Java, `String` is a **class** used to represent a sequence of characters. It is one of the most commonly used classes in the Java Standard Library and is **immutable**, meaning its value cannot be changed once created.

---

### Key Features of String

- Stored in **string pool** (memory optimization)
- **Immutable**
- Has many built-in methods for text manipulation
- Implements `CharSequence`, `Comparable`, and `Serializable` interfaces

---

### Creating Strings

```java
String s1 = "Hello";               // Using string literal
String s2 = new String("World");   // Using constructor
```

---

### Commonly Used String Methods

#### 1. `length()`

Returns the number of characters in the string.

```java
String str = "Hello";
System.out.println(str.length());
```

**Output:**
```
5
```

---

#### 2. `charAt(int index)`

Returns the character at the specified index.

```java
String str = "Hello";
System.out.println(str.charAt(1));
```

**Output:**
```
e
```

---

#### 3. `substring(int beginIndex, int endIndex)`

Returns a new string that is a substring of this string.

```java
String str = "Hello World";
System.out.println(str.substring(0, 5));
```

**Output:**
```
Hello
```

---

#### 4. `equals(String other)`

Compares two strings for exact equality.

```java
String a = "Java";
String b = "Java";
System.out.println(a.equals(b));
```

**Output:**
```
true
```

---

#### 5. `equalsIgnoreCase(String other)`

Compares two strings, ignoring case differences.

```java
String a = "java";
String b = "JAVA";
System.out.println(a.equalsIgnoreCase(b));
```

**Output:**
```
true
```

---

#### 6. `toLowerCase()` and `toUpperCase()`

Converts the string to lower or upper case.

```java
String str = "HeLLo";
System.out.println(str.toLowerCase());
System.out.println(str.toUpperCase());
```

**Output:**
```
hello
HELLO
```

---

#### 7. `trim()`

Removes leading and trailing whitespace.

```java
String str = "  Java  ";
System.out.println(str.trim());
```

**Output:**
```
Java
```

---

#### 8. `contains(CharSequence s)`

Checks if the string contains the specified sequence.

```java
String str = "OpenAI GPT";
System.out.println(str.contains("GPT"));
```

**Output:**
```
true
```

---

#### 9. `replace(CharSequence old, CharSequence new)`

Replaces all occurrences of a specified sequence.

```java
String str = "abc abc";
System.out.println(str.replace("a", "x"));
```

**Output:**
```
xbc xbc
```

---

#### 10. `split(String regex)`

Splits the string into an array using the specified regex.

```java
String str = "apple,banana,orange";
String[] fruits = str.split(",");

for (String fruit : fruits) {
    System.out.println(fruit);
}
```

**Output:**
```
apple
banana
orange
```

---

### String Immutability Example

```java
String original = "Java";
String modified = original.concat(" Programming");

System.out.println("Original: " + original);
System.out.println("Modified: " + modified);
```

**Output:**
```
Original: Java
Modified: Java Programming
```

---

### Summary Table of Common Methods

| Method              | Description                                 |
|---------------------|---------------------------------------------|
| `length()`          | Returns the length of the string            |
| `charAt(index)`     | Returns character at specified index        |
| `substring(start, end)` | Returns substring from start to end       |
| `equals(str)`       | Compares two strings for equality           |
| `equalsIgnoreCase()`| Compares strings ignoring case              |
| `toLowerCase()`     | Converts to lowercase                       |
| `toUpperCase()`     | Converts to uppercase                       |
| `trim()`            | Removes whitespace from both ends           |
| `contains(seq)`     | Checks if string contains a sequence        |
| `replace(old, new)` | Replaces all occurrences of old with new    |
| `split(regex)`      | Splits the string using a regex             |

---

### Conclusion

The `String` class in Java is a powerful and essential tool for text manipulation. It provides a wide range of methods for working with characters and sequences efficiently. Because strings are immutable, all operations return new `String` objects instead of modifying the original.



# StringBuilder Class in Java

The `StringBuilder` class in Java is used to create mutable (modifiable) sequences of characters. Unlike `String`, which is immutable, `StringBuilder` allows modification without creating new objects.

## Package
```java
java.lang.StringBuilder
```

## Constructors

| Constructor | Description |
|-------------|-------------|
| `StringBuilder()` | Creates an empty StringBuilder with an initial capacity of 16. |
| `StringBuilder(int capacity)` | Creates a StringBuilder with the specified capacity. |
| `StringBuilder(String str)` | Creates a StringBuilder containing the specified string. |
| `StringBuilder(CharSequence seq)` | Creates a StringBuilder that contains the same characters as the specified `CharSequence`. |

## Commonly Used Methods

| Method | Description |
|--------|-------------|
| `append(String str)` | Appends the specified string to this character sequence. |
| `insert(int offset, String str)` | Inserts the string into this character sequence at the specified position. |
| `replace(int start, int end, String str)` | Replaces the characters in the specified range with the specified string. |
| `delete(int start, int end)` | Removes the characters in the specified range. |
| `deleteCharAt(int index)` | Removes the character at the specified position. |
| `reverse()` | Reverses the sequence of characters. |
| `toString()` | Converts the `StringBuilder` to a `String`. |
| `length()` | Returns the number of characters. |
| `capacity()` | Returns the current capacity. |
| `setLength(int newLength)` | Sets the length of the character sequence. |

## Example
```java
public class StringBuilderExample {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder("Hello");
        sb.append(" World");
        System.out.println(sb);  // Output: Hello World
        sb.insert(5, ",");
        System.out.println(sb);  // Output: Hello, World
        sb.replace(6, 11, "Java");
        System.out.println(sb);  // Output: Hello, Java
        sb.delete(5, 6);
        System.out.println(sb);  // Output: Hello Java
        sb.reverse();
        System.out.println(sb);  // Output: avaJ olleH
    }
}
```

## Differences Between String and StringBuilder

| Feature | `String` | `StringBuilder` |
|--------|----------|----------------|
| Mutability | Immutable | Mutable |
| Thread Safety | Yes | No |
| Performance | Slower for frequent modifications | Faster |


# Wrapper Classes in Java

Wrapper classes provide a way to use primitive data types (int, boolean, etc.) as objects. Each primitive type has a corresponding wrapper class in the `java.lang` package.

## List of Wrapper Classes

| Primitive Type | Wrapper Class   |
|----------------|-----------------|
| `byte`         | `Byte`          |
| `short`        | `Short`         |
| `int`          | `Integer`       |
| `long`         | `Long`          |
| `float`        | `Float`         |
| `double`       | `Double`        |
| `char`         | `Character`     |
| `boolean`      | `Boolean`       |

## Why Use Wrapper Classes?

- Needed when working with collections (e.g., `ArrayList<Integer>`)
- Allow primitives to be treated as objects
- Provide useful utility methods (parsing, conversion, etc.)

## Commonly Used Methods

| Wrapper Class | Common Methods                                   |
|---------------|-------------------------------------------------|
| `Integer`     | `parseInt(String)`, `valueOf(String)`, `toString()` |
| `Double`      | `parseDouble(String)`, `valueOf(String)`, `toString()` |
| `Boolean`     | `parseBoolean(String)`, `valueOf(String)`          |
| `Character`   | `isDigit(char)`, `isLetter(char)`, `toUpperCase(char)` |

## Example
```java
public class WrapperExample {
    public static void main(String[] args) {
        // Boxing - converting primitive to wrapper
        Integer intObj = Integer.valueOf(100);
        Double doubleObj = Double.valueOf(55.5);

        // Unboxing - converting wrapper to primitive
        int num = intObj.intValue();
        double d = doubleObj.doubleValue();

        // Autoboxing - automatic conversion
        Integer autoBoxed = 50;

        // Auto-unboxing - automatic conversion
        int autoUnboxed = autoBoxed;

        // Parsing string to primitive
        int parsedInt = Integer.parseInt("123");

        System.out.println("intObj: " + intObj);
        System.out.println("num: " + num);
        System.out.println("autoBoxed: " + autoBoxed);
        System.out.println("autoUnboxed: " + autoUnboxed);
        System.out.println("parsedInt: " + parsedInt);
    }
}
```



