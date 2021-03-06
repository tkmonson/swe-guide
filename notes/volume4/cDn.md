# Notes for Chapter 13: Programming Language Theory

Programming is the act of scheduling something (e.g. cable television programming is the strategic scheduling of different kinds of TV shows). Computer programming is the act of scheduling machine operations, either one by one or in blocks of operations, which are abstracted away and represented by statements written in high-level languages.
Programming is also the act of optimizing (i.e. maximizing or minimizing) a function in order to predict the best course of action. In computer programming, this involves developing input (source code) that will perform a task with minimal complexity (in space or time).

Primitives (derived from primitive notions in philosophy)
Virtual machine
REPL
Entry point
Interactive programming
Programming in the large and programming in the small
Pipeline
Transcompilation
Command line interpreter
Modular programming
Template processor
Software framework
Portability

Clocking, asynchronous events

Iteration and recursion are about repeating an operation. How they do that differs.
Iteration: fast, usually easy to implement
Recursion: easy to debug, sometimes more natural, uses stack memory
They can be converted into each other

Polyglot programming

## Elements of Programming Languages

Development: specifications should be separate from implementations

What does a Turing-complete language need? Conditional branching (not just jumping), others?

Structured program theorem - any computable function can be represented using three types of control structures (sequence, selection, repetition)

Statement types: assertion, assignment, goto, return, call

Field, property, method, object, class, ...

## History of Programming Languages

What does it mean to print? It means to render a piece of information content in some physical medium. Printers print information into books. Back in the day, when computers didn't have fancy graphical displays, the print command converted digital content (information stored in bits) into a print file or device file, a file that an external device (like a printer) can read and operate on. The operating system of the computer would then output the file to the device, which would render the information content in physical form. Nowadays, the print command converts digital content into various standard file formats and those files output graphically by means of a monitor (and technically, light is physical). Printing hasn't fundamentally changed.
Turing is imperative and lambda is declarative?
What is a paradigm? How does having a strict paradigm affect the experience of coding? More restrictive, more streamlined?
More recent is not necessarily better
Why are we still using old languages like C?

## Programming Paradigms

How can we categorize programming languages?
Imperative vs. Declarative (Functional and Logic)
        Declaration-style and expression-style
Procedural vs. Object-Oriented
Compiled vs. Interpreted
Static vs. dynamic
Weakly typed vs. strongly typed
Statically typed vs. dynamically typed
Syntax (sparse, dense, graphical)
Release date
Structured vs. Non-structured (Control flow)
Popular use cases
Cultural perceptions?
Company preferences (Microsoft, Apple, general use)
General-purpose vs domain-specific (MANY domains)
High-level vs. low-level
System programming vs. application programming
Scripting languages (glue, shell, macro, embedded)
Concurent/Parallel/Distributed/Multithreaded
Heterogenous programming (OpenCL)
Natural languages
Memory management vs. garbage collection (C++ scope-based resource management)
Performance vs. readability/manageability
Expressive power
Whitespace-sensitive or not
Data languages
Query languages
Pointers or not
Exceptions or not
Library size
Numerical computing (e.g. MATLAB, Maple, Mathematica)
Automated theorem proving
Hyperlink to esoteric languages lol
Literate programming (e.g. TeX)
Ontology language

## Programming Techniques

### Higher-Order Programming

Map, filter, fold, zip

