---
title: "OOP principles in Java"
date: 2023-04-23
draft: true
tags:
  - object-oriented-programming
  - java
---

# Classes and Objects

Frequently, OOP people describe the relationship between _Class_ and _Object_ as cookie cutters
and cookies. This metaphor, however, fails to bring any enlightenment to what Inheritance,
Aggregation, Overloading, and Polymorphism are.

They obviously borrowed the word _Inheritance_ from biology (todo: research who and where the
term _Inheritance_ was first described. I can vividly imagine some legendary white male computer
scientist who happened to be a hobby ornithologist) and immediately fumble explaining what _Inheritance_ tries to
express in OOP and execute the ejection seat into yet another metaphor (cookie cutters and cookies). Sigh.

I think that educating about OOP is better done either in direct abstract terms, people are smart enough for that, remember natural numbers? We're teaching that concept to 6 year old kids at school. Or, if you really want to
introduce a metaphor, the one with Recipes and Meals is much better to grasp and doesn't even break when explaining
further concepts.

So let's say we want to cook a lovely vegan meal of Indian origin, a Dal.

To make matters easy to grasp, think of Objects as logical containers of data together with methods
(functions) applicable to this container. For example, a Person object could have a first name and a
last name, an age and a height. Traditionally, OOP people then would add 6 (six!) so called getter-methods and
setter-methods to be able to "set the first name" on the Person object or "get the age" from the
Person object; technically this is not needed but is always added "because tradition". Along with those
getter and setter methods (functions) you could actually add some useful functionality like "calculate
the full name, which would be the first name concatenated with the last name" or something like "calculate when the person will go into retirement".

So, how are Person objects created and who defines their properties? This is where Classes come into play. Classes are an abstract thing, like a blueprint in which a developer can express which properties and methods (functions) an Object described by this Class should have.

# Relationships between Classes

A class as a sole blueprint for a container of data and its associated methods is not a very useful thing. In fact, there
are programming languages that allow you to directly create objects just as a containment of data and glue some functions
to them. But in Java philosophy there's a whole set of tools to describe relationships between classes and thus the relationships of the objects they describe.

- Dependence ("uses-a")
- Aggregation ("has-a")
- Inheritance ("is-a")

Overloading

Object Lifetime

- Construction
- Destruction

Code reuse
