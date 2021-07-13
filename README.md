# Cookies and ovens: bakery model

## Introduction
*I ❤️ Cookies*: a bakery that specializes in various types of delicious cookies. The bakery is rapidly growing, and it's becoming difficult to meet the demand. Your task is to create a program that will help you manage your bakery.

Here's some user feedback to help you get started:
- As a baker, I want to make different types of cookies (peanut butter, chocolate chips, etc.).
- As a baker, I want to put batches of cookies in the oven.
- As a baker, I want to know when a batch is ready so that I can take it out of the oven.

### Object-oriented approach. Design.
This assignment's goal is to transfer objects, classes of the real world to objects, classes of your program. You should follow these guidelines. 

##Цель этой задачи - переложить объекты, классы реального мира на объекты, классы вашей программы.

* Create well-defined classes, each responsible for one thing.
* Implement clean and flexible logic for communicating between objects.

## Releases
### Pre-release: Understanding the problem
Before you start coding,  thoroughly think through the issue. Then, in plain English, describe how you'll create this program. 
Consider the following questions:
- What are the main classes?
- What attributes will each class have?
- What functionality will each class provide?
- How will the classes interact with each other?
- Do you need to use inheritance? Composition? Do you know what composition is?

### Release 0: Minimum Viable Product (MVP) Implementation

After understanding your program's components, start coding. Build a *Minimum Viable Product* (MVP) - no fancy features, just the essentials.

Using the *Introduction* for reference, make a program that can put cookies in the oven, bake them, and take them out. If the cookies are in the oven, you must bake them, checking for a change in readiness status.
Now, let's take this opportunity to practice writing tests! Your tests should describe your class' functions.

### Release 1: Additional Features
Excellent! You've written an MVP. Now, it's time to expand the program: add and test some new features. 

Please do the following:
- Create several types of cookies, each with a different baking time.
- The cookies should have four possible statuses: `doughy`, `almostReady`, `ready`, and `burned`, depending on their baking time.

### Release 2: Refactoring
[Refactoring](https://en.wikipedia.org/wiki/Code_refactoring) is an essential part of development. Take a step back, look at your code, and optimize optimizable code. 
Pay attention to the following aspects:
- Are you giving objects more properties/functions than necessary?
- Are you unnecessarily repeating logic throughout your code?
- Are your classes orthogonal? [Orthogonal](http://stackoverflow.com/a/1527430)

### Release 3: Be Creative!

Put yourself in a baker's shoes. What other features would be helpful? Choose and add the most useful/feasible functions to your program.
