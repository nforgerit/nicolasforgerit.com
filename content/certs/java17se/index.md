---
author: Nicolas Forgerit
title: "Oracle: Java 17 SE"
date: 2023-04-23
description: A brief guide to setup KaTeX
# math: true
image: 2.png
categories:
  - Development
  - Software Engineering
draft: false
---

[![Oracle: Java 17 SE](./2.png)](https://mylearn.oracle.com/ou/learning-path/java-se-17-developer/99487)

# Java SE 17 Course

Programming Complete

## 1. Introduction to Java

- Introduction to Java
- [Object Oriented Principles](/blog/2023/04/oop-principles-in-java/)
- Inheritance
- Use Access Modifiers
- Practices for Lesson 1: Overview

## 2. Primitive Types, Operators, and Flow Control Statements

- Primitive Types, Operators, and Flow Control Statements
- Assignment and Arithmetic Operators
- Binary Number Representation
- Flow Control Using /switch/ Construct
- Practices for Lesson 2: Primitive Types, Operators, and Flow Control Statements
- Practice 2-2: Use the if/else and switch Constructs and the Ternary Operator

## 3. Text, Date, Time, and Numeric Objects

- Text, Date, Time, and Numeric Objects
- Text Blocks
- Wrapper Classes for Primitives
- Local Date and Time
- Represent Languages and Countries
- Format and Parse Date and Time Values
- Practice 3-1: Explore String and StringBuilder Objects
- Practice 3-2: Use BigDecimal Class and Format Numeric Values
- Practice 3-3: Use and Format Date and Time Values
- Practice 3-4: Apply Localization and Format Messages

## 4. Classes and Objects

- Classes and Objects
- Local Variable Type Inference
- IntelliJ IDE Introduction
- Practice 4-1: Create the Product Management Application
- Practice 4-2: Enhance the Product Class
- Practice 4-3: Document Classes

## 5. Improved Class Design

- Improved Class Design
- Access Modifiers Summary
- Enumerations
- Practice 5-3: Make Objects Immutable

## 6. Implement Inheritance and Use Records

- Implement Inheritance and Use Records
- Verify Object Type Before Casting the Reference
- Override Methods ans Use Polymorphism
- Sealed Classes, Inheritance Under Control
- Factory Method Pattern
- Practice 6-2: Override Methods and Use Polymorphism
- Practice 6-3: Create Factory Methods
- Practice 6-6: Explore Java Records
- Practice 6-7: Implement Sealed Classes with Records

## 7. Interfaces and Generics

- Interfaces and Generics
- Default, Private, and Static Methods in Interfaces
- Generics
- Practice 7-3: Test the Product Review Functionality

## 8. Arrays and Loops

- Arrays and Loops
- The Arrays Class
- Practice 8-1: Allow Multiple Reviews for a Product

## 9. Collections

- Collections
- Create Set Object
- Create HashMap Object
- Access Collections Concurrently
- Practice 9-1: Organize Products and Reviews into a HashMap
- Practice 9-2: Implement Review Sort and Product Search Features

## 10. Nested Classes and Lambda Expressions

- Nested Classes and Lambda Expressions
- Define Lambda Expression Parameters and Body
- Practice 10-1: Refactor ProductManager to Use a Nested Class
- Practice 10-2: Produce Customized Product Reports

## 11. Java Streams API

- Java Streams API
- Bi-argument Variants of Functional Interfaces
- Aggregate Stream Data using reduce Operation
- Restrictions on Parallel Stream Processing
- Spliterator
- Practice 11-1: Modify ProductManage to Use Streams
- Practice 11-2: Add Discount Per Rating Calculation

## 12. Exception Handling, Logging, and Debugging

- Exception Handling, Logging, and Debugging
- Handling Exceptions
- Normal Program Flow with No Exceptions
- Practice 12-1: Use Exception Handling to Fix Logical Errors
- Practice 12-2: Add Text Parsing Operations

## 13. Java IO API

- Java IO API
- Serializable Object Graph
- Working with File Systems
- Delete Paths
- Practice 13-1: Print Product Report to a File
- Practice 13-2: Buld-Load Data from Files
- Practice 13-3: Implement Memory Swap Mechanism

## 14. Java Concurrency and Multithreading

- Java Concurrency and Multithreading
- Manage Executor Service Life Cycle
- Writing Thread-Safe Code
- Summary
- Practice 14-3: Simulate Concurrent Callers

## 15. Modules and Deployment

- Modules and Deployment
- JPMS Module Categories
- Open Module Content
- Multi-Release Module Archives
- Practice 15-1: Convert ProductManagement Application into a Module
- Practice 15-2: Separate Application into Several Modules

## 16. Annotations

- Annotations
- Annotations that Validate Design

## 17. Java Database Connectivity

- Java Database Connectivity
- Create and Execute Callable SQL Statements

## 18. Java Security

- Java Security
- Execute Privileged Code
- Erroneous Value Guards

## 19. Advanced Generics

- Advanced Generics
- Upper Bound Wildcard

## 20. Oracle Cloud Deployment

- Oracle Cloud Deployment
- Example of the Microservices Architecture for an Online Mobile Application
- Practice E-1: Present Application Logic as a Service Using Helidon SE

## 21. Miscellaneous Java Topics

- Miscellaneous Java Topics
- Bitwise Logical Operators
- Character Classes
- Using the /replaceAll/ Method
- Stream Examples
- Java IO, File Watch Service
- Factory Design Pattern code demo
- Singleton Pattern code demo
- Bitwise Logical Operators code demo
- Regular Expressions code demo
- Threads deadlock, livelock, and starvation code demos
- Streams code demos
- Java IO, File Watch Service code demos

# Exam Topics

## Handling date, time, text, numeric and boolean values

- Use primitives and wrapper classes including Math API, parentheses, type promotion, and casting to evaluate arithmetic and boolean expressions
- Manipulate text, including text blocks, using String and StringBuilder classes
- Manipulate date, time, duration, period, instant and time-zone objects using Date-Time API

## Controlling Program Flow

- Create program flow control constructs including if/else, switch statements and expressions, loops, and break and continue statements

## Utilizing Java Object-Oriented Approach

- Declare and instantiate Java objects including nested class objects, and explain the object life-cycle including creation, reassigning references, and garbage collection
- Create classes and records, and define and use instance and static fields and methods, constructors, and instance and static initializers
- Implement overloading, including var-arg methods
- Understand variable scopes, use local variable type inference, apply encapsulation, and make objects immutable
- Implement inheritance, including abstract and sealed classes. Override methods, including that of Object class. Implement polymorphism and differentiate object type versus reference type. Perform type casting, identify object types using instanceof operator and pattern matching
- Create and use interfaces, identify functional interfaces, and utilize private, static, and default interface methods
- Create and use enumerations with fields, methods and constructors

## Handling Exceptions

- Handle exceptions using try/catch/finally, try-with-resources, and multi-catch blocks, including custom exceptions

## Working with Arrays and Collections

- Create Java arrays, List, Set, Map, and Deque collections, and add, remove, update, retrieve and sort their elements

## Working with Streams and Lambda expressions

- Use Java object and primitive Streams, including lambda expressions implementing functional interfaces, to supply, filter, map, consume, and sort data
- Perform decomposition, concatenation and reduction, and grouping and partitioning on sequential and parallel streams

## Packaging and deploying Java code and use the Java Platform Module System

- Define modules and their dependencies, expose module content including for reflection. Define services, producers, and consumers
- Compile Java code, produce modular and non-modular jars, runtime images, and implement migration using unnamed and automatic modules

## Managing concurrent code execution

- Create worker threads using Runnable and Callable, manage the thread lifecycle, including automations provided by different Executor services and concurrent API
- Develop thread-safe code, using different locking mechanisms and concurrent API
- Process Java collections concurrently including the use of parallel streams

## Using Java I/O API

- Read and write console and file data using I/O Streams
- Serialize and de-serialize Java objects
- Create, traverse, read, and write Path objects and their properties using java.nio.file API

## Accessing databases using JDBC

- Create connections, create and execute basic, prepared and callable statements, process query results and control transactions using JDBC API

## Implementing Localization

- Implement localization using locales, resource bundles, parse and format messages, dates, times, and numbers including currency and percentage values

## Assume the following:

- Missing package and import statements: If sample code do not include package or import statements, and the question does not explicitly refer to these missing statements, then assume that all sample code is in the same package, or import statements exist to support them.
- No file or directory path names for classes: If a question does not state the file names or directory locations of classes, then assume one of the following, whichever will enable the code to compile and run:
  - All classes are in one file
  - Each class is contained in a separate file, and all files are in one directory
- Unintended line breaks: Sample code might have unintended line breaks. If you see a line of code that looks like it has wrapped, and this creates a situation where the wrapping is significant (for example, a quoted String literal has wrapped), assume that the wrapping is an extension of the same line, and the line does not contain a hard carriage return that would cause a compilation failure.
- Code fragments: A code fragment is a small section of source code presented without its context. Assume that all necessary supporting code exists and that the supporting environment fully supports the correct compilation and execution of the code shown and its omitted environment.
- Descriptive comments: Take descriptive comments, such as "setter and getters go here," at face value. Assume that correct code exists, compiles, and runs successfully to create the described effect.

## Candidates are also expected to:

- Understand the basics of Java Logging API.
- Use Annotations such as Override, Functionalnterface, Deprecated, SuppressWarnings, and SafeVarargs.
- Use generics, including wildcards.
