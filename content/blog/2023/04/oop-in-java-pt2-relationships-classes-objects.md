---
title: "OOP principles in Java, pt. 2: Relationships between Classes and Objects"
date: 2023-04-23
draft: true
tags:
  - object-oriented-programming
  - java
---

# Classes and Objects

Frequently, OOP people describe the relationship between _Class_ and _Object_ as cookie cutters
and cookies. This metaphor, however, fails to bring any enlightenment to what Inheritance,
Aggregation, Overloading, and Polymorphism are meant to be.

- _Class_ is a blueprint for _Object_, e.g. class Shirt is a blueprint for a concrete shirt of your favorite band
- _Object_ is said to be of type _Class_ which is a useful discrimination if your program has a list of items in a
  shopping cart that each have a different kind of taxation and you need to calculate the cart's total price
- _Object_ is some kind of container for data with its related methods (functions) on that data
- Every _Class_ defined by the user and in the standard library inherits from the _Object_ class

OOP people encourage to encapsulate all data (_instance variables_) and make them only accessible to the public
world through so-called _getter_- and _setter_-methods.

In practice getters and setters lead to a lot of boilerplate code that is of no real use. Thankfully, Oracle (Java's trademark owner and main driver) stopped this nonsense and [introduced the `record` keyword](https://openjdk.org/jeps/359) in Java 14 (2020) which serves as a pure immutable data container with a type defined by the user.

Inheritance ("is-a relationship") was supposed to enable code reuse between classes sharing similar characteristics,
e.g. class Shirt and class Pants share the same attribute color

Inheritance, however, is a very strict relationship between classes and subclasses for modeling business Domains. It's hard to get right the first time and its even harder to change later on. Unfortunately, no textbook will tell you that.

I vividly remember me reading books on _C++_ in my teenage years and putting myself under pressure to "get it right". After 15+ years of industry experience I can definitely tell: It's bullshit, getting it right the first time is rarely the case. Instead: Stay happy!

# Composition over Inheritance

Another often referred principle is the so called "has-a relationship" ("composition over inheritance").

- Inheritance, however makes sense to express a such a strict supertype-subtype relationship as part of the Domain

# Recap

## Relationships between Classes

- Dependence ("uses-a")
- Aggregation ("has-a")
- Inheritance ("is-a")

# Overloading

# Object Lifetime

- Construction
- Destruction

# Memory representation

# Objects in the Standard Library

[Part 3: Object Lifetime](/blog/2023/04/oop-in-java-pt3-object-lifetime/)
