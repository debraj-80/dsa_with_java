## **Introduction to Java**

James Gosling developed Java at Sun Microsystems in 1995. It is an object-oriented, class-based, secure, platform-independent, and general-purpose programming language.

One of Java’s biggest strengths is its **“Write Once, Run Anywhere (WORA)”** principle. This means that once Java code is compiled, it can run on any system that has a Java Virtual Machine without needing recompilation.

Java programs are compiled into **bytecode**, which is not tied to any specific operating system. The JVM executes this bytecode, making Java highly portable.

---

## **Different Editions of Java**

Java is divided into four main editions based on use cases:

- Java Platform, Standard Edition (Java SE)
- Java Platform, Enterprise Edition (Java EE)
- Java Platform, Micro Edition (Java ME)
- JavaFX
---

### **1. Java SE (Standard Edition)**

Also known as **Core Java**, this is the foundation of the Java platform.

- Provides core libraries like `java.lang`, `java.util`
- Used for:
    - Desktop applications
    - Basic networking
    - Database access
    - GUI development
- Covers everything from basic syntax to advanced APIs

👉 Think of Java SE as the **base layer** of Java.

---

### **2. Java EE (Enterprise Edition)**

Built on top of Java SE for large-scale applications.

- Used for:
    - Web applications
    - Enterprise systems
    - REST APIs and web services
- Works with technologies like HTML, CSS, JavaScript
- Includes tools for:
    - Server-side programming
    - Security
    - Scalability

👉 This is what you’ll use heavily in **Spring Boot and backend development**.

---

### **3. Java ME (Micro Edition)**

Designed for **resource-constrained devices**.

- Used in:
    - Mobile phones (older generation)
    - Embedded systems
    - Set-top boxes
- Lightweight version of Java SE

👉 Not very relevant today for modern app development, but still used in some embedded systems.

---

### **4. JavaFX**

A framework for building **modern graphical user interfaces (GUI)**.

- Used for:
    - Rich desktop applications
    - UI components and animations
- Integrated with Java SE (from Java 8)

👉 Think of it as a **modern replacement for Swing** for UI development.

---

## **Quick Summary**

- Java is platform-independent because of the JVM
- Java SE is the foundation
- Java EE is for enterprise/web apps
- Java ME is for small devices
- JavaFX is for GUI applications