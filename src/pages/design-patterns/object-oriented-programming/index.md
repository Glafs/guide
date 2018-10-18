---
title: Object Oriented Programming (OOP)
---

## Outline
* Why Object Oriented (henceforth abbreviated as OO)?
* OO concepts
* What next?

## Why OO?
In this paradigm, entities are represented as real world data. For instance, we want to represent a dog. In OO paradigm, we simply create a class named "dog", and give it attributes (colour, age, sex, etc) and behaviour (bark, run, eat, etc). Behaviour is changed through "methods" (functions in simple words) that make changes to attributes.

Efficiency is a key factor of OO, let us say that we have created an object with many methods, which we use often and maybe in connection with other objects. Instead of having to rewrite code and fit it into an procedural way, we can just switch our methods with optimized methods, which we have written at a later stage or even switch whole objects. A good comparison would be your computers motherboard, in many cases we can just switch RAMs or insert more RAMs into the machine, well the same can be done with other components. As the computer components work in harmony, we can construct an OO program with objects that act like components in a machine. 

## OO concepts
What makes OO programming powerful is its ability to do the following:
* Inheritence
* Polymorphism
* Encapsulation
* Abstraction

In procedural programming, we simply create variables and change them when required. However in OO programming, we can literally simulate real world objects. Encapsulation is achieved by creating a specific class for an entity, for example dog. Objects of this class are then created, which are nothing but instances of the class. Each object has its own attribute values.

Another extremely useful concept is that of inheritance. The idea is that a class can inherit attributes and behaviour from a base class. For example, while creating a game, we have a player and enemy. We can create a base class called person, and give it attributes like name, age, gender, etc. Person's behaviour can be walk and jump. A player and enemy can then inherit these "qualities" from person, and can have added qualities like kill, score, eat, etc.

This helps with reusing your code and makes its structure cleaner. Data hiding is another cool feature, in OO, we have the notion of private and public attributes. Private attributes can be accessed and modified only by methods of that particular class, while public data can be modified from anywhere in the program (within scope obviously).

## What next?
Pick an OO language, and build a basic terminal based game to illustrate these concepts.
