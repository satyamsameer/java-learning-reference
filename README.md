# Learning Reference for Java Programming

Inspired by [Google Interview University](https://github.com/jwasham/google-interview-university).
Language: English

## What is it?
This is a study plan or say reference from the basics to the advance concepts for the JAVA computer programming language.

My main goal is to find an approach for studying the JAVA computer language and during this I've created a topic wise summary for quick review containing various references and tutorials.
This approach is unconventional because it’s the top-down approach and relatively quick.
 
Please, feel free to make any contributions you feel will make it better.

---


## Table of Contents

- [What is it?](#what-it-is)
- [Parts](#parts)
	- [Basic](#basic)
	- [Advance](#advance)
- [Basic](#basic)
	- [Introduction](#introduction)
		- [What is JAVA?](#what-is-java)
		- [History](#history)
		- [Features of JAVA](#features-of-java)
		- [JIT](#jit)
		- [Bytecode (.class file)](#bytecode)
		- [Platform Independence](#platform-independence)
		- [OOPs](#oops)
			- [Objects](#objects)
			- [Classes](#classes)
			- [Inheritance](#inheritance)
			- [Polymorphism](#polymorphism)
				-[Runtime Polymorphism](#runtime-polymorphism)
			- [Aggregation](#aggregation)
			- [Abstraction](#abstraction)
			- [Encapsulation](#encapsulation)
			- [Data Binding](#data-binding)
			
- [Program Structure](#program-structure)
	- [Unicode System](#unicode-system)
	- [Syntax](#syntax)
	- [Imports](#imports)
		- [Packages](#packages)
		- [Libraries](#libraries)
		- [Classes](#classes)
	- [Naming Conventions](#naming-conventions) Classes, methods and variables
	- [Keywords](#keywords)
	- [Comments](#comments)
		- [Single Line Comments](#single-line-comments)
		- [Multiple Line Comments](#multiple-line-comments)
		- [Documentation Comment](#documentation-comment)
	- [Java Programs](#java-programs)
	- [Code Block {}](#code-block)
	- [Code Line End ;](#code-line-end)
	- [Constituents](#constituents)
		- [Data Types](#data-types)
			- [Primitive Datatypes](#primitive-datatypes)
				- [Integers (Long and Short)](#integers)
				- [Floating Point](#floating-point)
				- [Double](#double)
				- [Characters](#characters)
				- [Boolean](#boolean)
				- [Byte](#byte)
			- [Reference/Object Datatypes](#reference)
				- [Static Binding](#static-binding)
				- [Dynamic Binding](#dynamic-binding)
			- [Java Literals](#java-literals)
			- [Non Primitive Datatypes](#non-primitive-datatypes)
				- [String Type](#string-type)
				- [Arrays](#arrays) Datatype and Index in one-dimensional or multi-dimensional arrays
		- [Variables](#variables)
			- [Data Type](#data-type)
			- [Identifier](#identifier)
			- [Initializer](#initializer)
		- [Modifier Types](#modifier-types)
			- [Java Access Modifiers](#java-access-modifiers)
				- [Public](#public)
				- [Protected](#protected)
				- [Private](#private)
			- [Java Non Access Modifiers](#java-non-access-modifiers)
				- [Static](#static)
				- [Final](#final)
				- [Abstract](#abstract)
				- [Synchronized](#synchronized)
			- [this Keyword](#this-keyword)
		- [Operators](#operators)
			- [Unary](#unary)
			- [Increment](#increment) Postfix and Prefix
			- [Decrement](#decrement) Postfix an Prefix
			- [Binary](#binary)
				- [Arithematic Operators](#arithematic-operators)
				- [Relational Operators](#relational-operators)
				- [Bitwise Operators](#bitwise-operators)
				- [Logical Operators](#logical-operators)
				- [Assignment Operators](#assignment-operators)
				- [Miscellaneous Operators](#miscellaneous-operators)
			- [Ternary](#ternary) Conditional Operator (:?)
			- [instanceof Operator](#instanceof-operator)
			- [Precedence of Operators](#precedence-of-operators)
		- [Control Statements](#control-statements)
			- [if-else](#if-else)
			- [for Loop](#for-loop)
			- [while Loop](#while-loop)
			- [do-while Loop](#do-while-loop)
			- [Break Statement](#break-statement)
			- [Continue Statement](#continue-statement)
		- [Classes Forms](#classes-forms)
			- [Abstract Class](#abstract-class)
			- [Interface Class](#interface-class)
			- [Base and Super Class](#base-and-super-class)
				- [super Keyword](#super-keyword)
				- [extends Keyword](#extends-keyword)
		- [Objects](#objects)
		- [Class Members](#class-members)
			- [Class Variables](#class-variables)
			- [Class Methods](#class-methods) dot operator
				- [Method Overriding and Overloading](#method-overriding-and-overloading)
				- [Driving method main()](#driving-method-main)
				- [Abstract Methods](#abstract-methods)
				- [Constructor](#constructor)
					- [Constructor Overriding and Overloading](#constructor-overriding-and-overloading)
				- [Return Type](#return-type)
				- [Call By Value](#call-by-value)
			- [Inner Class](#inner-class)
				- [Nested Classes](#nested-classes)
					- [Non Static Inner Classes](#non-static-inner-classes)
						- [Inner Classes](#inner-classes)
						- [Method Local Inner Classes](#method-local-inner-classes)
						- [Anonymous Inner Classes](#anonymous-inner-classes)
			- [Outer Class](#outer-class)
			- [Wrapper Class](#wrapper-class) Autoboxing and Unboxing
		- [Blockc(Instance Intializer Block)](#block-instance-initializer-block)
		- [Exception Handling](#exception-handling)
		- [Exception Handling Components](#exception-handling-components)
			- [try Block](#try-block)
			- [catch Block](#catch-block) Multiple Catch Blocks
			- [finally Vs final Vs finalize](#finally-vs-final)
			- [throw](#throw)
			- [throws](#throws)
		- [Exception Propogation](#exception-propogation)
		- [Exception Handling with Method Overriding](#exception-handling-with-method-overriding)
		- [Custom Exception](#custom-exception)
		
		
- [Advance](#advance)
	Work Remaining
		
---


## Parts

- Basics - 

- Advance - 

---

## Basic

### Introduction
#### What is JAVA?
Java is a powerful and versatile programming language for developing software running on mobile devices, desktop computers, and servers.

Java is simple, object oriented, distributed, interpreted, robust, secure, architecture neutral, portable, high performance, multi-threaded, and dynamic. With advancement various versions are released like J2EE and J2ME. Sun Microsystems has renamed the new J2 versions as Java SE, Java EE and Java ME, respectively. Java is guaranteed to be Write Once, Run Anywhere.

#### History
Java was developed by a team led by James Gosling at Sun Microsystems. Sun Microsystems was purchased by Oracle in 2010. Originally called Oak, Java was designed in 1991 for use in embedded chips in consumer electronic appliances. In 1995, renamed Java, it was redesigned for developing Web applications.

#### Features of JAVA
There are carious features possessed by the JAVA programming language some of them are given below-
* Simple- It is designed for simplicity i.e., if you know OOPs concepts it is easy to master.
* Object Oriented- Java treat everything as objects hence it can be easily extended as it is based on object model.
* Distributed- Java is best suited for distributed environment such as internet.
* Interpreted- Java byte code is translated on the fly to native machine instructions and is not stored anywhere. The development process is more rapid and analytical since the linking is an incremental and lightweight process.
* Robust- Java negotiates erroneous situations by emphasizing mainly on compile and run time only.
* Secure- Java is designed to apply security features with ease like authentiaction based on public key cryptography.
* Architectural Neutral- Java compiler creates a bytecode from the source which is gives the ability to write once and run on any platform.
* Portable- As it is architectural neutral and having no dependencies makes it portable. Compiler in Java is written in ANSI C with a clean portability boundary which is POSIX subset.
* High Performance- Wiith its Just-In-Time compiler it gives high performance.
* Multithreaded- It gives capability for developers to write programs which can do multiple works at the same time.
* Dynamic- More dynamic than C or C++ as it adapts to evolving environment. Each java programs holds extensive amount of run time information that can be used to verify and resolve accesses to objects on run-time.

#### JIT

#### Bytecode (.class file) 

#### Platform Independence

#### OOPs
##### Objects
##### Classes
##### Inheritance
##### Polymorphism
###### Runtime Polymorphism
##### Aggregation
##### Abstraction
##### Encapsulation
##### Data Binding

---


## Program Structure

### Unicode System

### Syntax
 
### Imports
....

#### Packages

-

#### Libraries

-

#### Classes

-

### Naming Conventions 
	
	Classes, methods and variables

### Keywords

### Comments

-

#### Single Line Comments

-

#### Multiple Line Comments

-

#### Documentation Comment

-

### Java Programs

### Code Block {}

### Code Line End ;

### Constituents

-

#### Data Types
##### Primitive Datatypes
- Integers (Long and Short)
- Floating Point
- Double
- Characters
- Boolean
- Byte

##### Reference/Object Datatypes
- Static Binding
- Dynamic Binding

##### Java Literals

##### Non Primitive Datatypes
- String Type
- Arrays - Datatype and Index in one-dimensional or multi-dimensional arrays

-

#### Variables
##### Data Type
##### Identifier
##### Initializer

-

#### Modifier Types
##### Java Access Modifiers
- Public
- Protected
- Private

##### Java Non Access Modifiers
- Static
- Final
- Abstract
- Synchronized

##### this Keyword

-

#### Operators
##### Unary
##### Increment
	Postfix and Prefix
##### Decrement
	Postfix an Prefix
##### Binary
- Arithematic Operators
- Relational Operators
- Bitwise Operators
- Logical Operators
- Assignment Operators
- Miscellaneous Operators

##### Ternary
	Conditional Operator (:?)
##### instanceof Operator
##### Precedence of Operators

-

#### Control Statements
##### if-else
##### for Loop
##### while Loop
##### do-while Loop
##### Break Statement
##### Continue Statement

-

#### Classes Forms
##### Abstract Class
##### Interface Class
##### Base and Super Class
- super Keyword
- extends Keyword

-

#### Objects

-

#### Class Members
##### Class Variables
##### Class Methods
	dot operator
- Method Overriding and Overloading
- Driving method main()
- Abstract Methods
- Constructor
	- Constructor (Overriding and Overloading)
- Return Type
- Call By Value

##### Inner Class
- Nested Classes
	- Non Static Inner Classes
		- Inner Classes
		- Method Local Inner Classes
		- Anonymous Inner Classes

##### Outer Class
##### Wrapper Class
	Autoboxing and Unboxing

-

#### Blockc(Instance Intializer Block)

-

#### Exception Handling

-

#### Exception Handling Components
##### try Block
##### catch Block
	Multiple Catch Blocks
##### finally Vs final Vs finalize
##### throw
##### throws

-

#### Exception Propogation

-

#### Exception Handling with Method Overriding

-

#### Custom Exception

---


## Advance
	In Progress