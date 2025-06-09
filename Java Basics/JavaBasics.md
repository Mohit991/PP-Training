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

