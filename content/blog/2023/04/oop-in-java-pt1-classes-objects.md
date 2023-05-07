---
title: "OOP principles in Java, pt. 1: Objects and Classes"
date: 2023-04-23
draft: true
tags:
  - object-oriented-programming
  - java
---

# Objects and Classes

Java's object oriented programming philosophy is distancing itself from the earlier programming methodologies
of procedural programming and structured programming.

## Introduction to Object-Oriented Programming

Object-Oriented Programming (OOP) is or better was the dominant programming methodology of the 1990s and 2000s. This
changed a lot, however, less agile parts of the industry and education systems (e.g. Germany) still teach it as the
silver bullet to programing. It has its perks, though, and it's worth to have a good idea about OOP. Java is one of
those languages that heavily bought into OOP and is widely known for its heavy enterprise-y concepts. But with Version 8
(2014) that changed a lot and the development of the Java language got a lot more traction.

In a Java program, literally everything is an Object. The core idea of OOP is to encapsulate (also called _information
hiding_) data and its related methods into the same kind of container. Before, it was common to design a set of
procedures ("computer, do this then do that") and then design the data structures that would be passed through these
procedures. Java not only lets a programmer define custom _Classes_, i.e. aforementioned containers of data and
procedures but also provides a set of standard classes in its Standard library that can be used to build programs, e.g.
for handling Calendar, Time, Strings, etc.

Every user-defined class and every class in the standard library inherits from the `Object` class and therefore reuses a set of methods it gains by _Inheritance_.

[Part 2: Relationships between Classes and Objects](/blog/2023/04/oop-in-java-pt2-relationships-classes-objects/)
