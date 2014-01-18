# P6 Oo Terminology 
 
##Learning Competencies 

##Summary 

 ## Overview

You've been learning a few common Object Oriented terms, now it's time to test and stretch your understanding. In this challenge you will create a gist to explore Object Oriented terms and state how they relate to a single problem space. 

Your submission will demonstrate a solid understanding of OO terminology. You should be able to use each term in a practical application.

### Topics covered

To achieve this, you will use knoweledge of the following: 

* Object Oriented Design

### Resources

* [Practical Object-Oriented Design in Ruby](http://www.poodr.info/) (POODR) - available under Dropbox / Books

## Objective 1: Model a Problem 

**Part 1: Pick a Problem** 

Choose a problem space to model. (Reminder: In software, the problem space is the set of requirements; these define the goal your software is trying to achieve, and any limits on potential solutions). Your problem space model is a description of a real world problem expressed in software objects. 

Your model should use at least three classes.

For example: I could choose my favorite object - the bicycle. In thinking about bicycles, I can start listing state (nouns) and behavior (verbs) that relate to bicycles. There are lots of ways to do this of course, but here is one:

**Nouns:**

* Bicycle
* Gears
* Brakes
* Wheels
* Pedals
* Mountain Bike
* Road Bike 

**Verbs:**

* Brake
* Accelerate
* Move
* Shift Gears
* Turn

Use these nouns to help determine some classes needed for the problem space and use the verbs to develop the methods needed in each class.

For this part, three classes are `Bicycle` `Gears` and `Wheels`. These classes (and others) are needed to model each of the terms below.

Now it's your turn. You need to choose your own problem space that will allow you to model each term discussed below. Before you do this, read through all the terms, and see how objects may be expected to interact. If you can't think of your own problem space, here are some common ones to that you can choose from: 

* ATMs and banks
* Car racing video game
* Person, boss, employee
* Grade book

**Part 2: Model the OO Basics - Tools and Terms**

* Attr_reader, writer, or accessor
* Public and Private Methods
* Instance and Class methods
* Instance and Class variables

First, define the terms above in two or three sentences. Then, create a code example in your Problem Space for each of the terms. The examples don't have to be the perfect application of the terms, but do include a brief description (in comments) of why they fit in your context. If you can't easily show code as an example, do it in pseudocode or stories or any other method that makes sense to you. 

Your definitions, code examples, and explanatory comments should be written out explicitly in your gist.

**Part 3: Inheritance or Composition?**

Is your problem better modeled by inheritance or composition?  First, define the two terms.  Then, show how your model can demonstrate the principle.  

In 2-3 sentences, describe why inheritance or composition are more suitable for your example (in a comment beneath your code.)  

**OPTIONAL Part 4: Extra credit** 

Implement both inheritance and composition!  And describe how both are exhibited in your code.

### You are done when...

Your model contains three or more classes, and models all of the terms in Part 2. 

### What to submit 

Your definitions, code examples, and explanatory comments should be written out explicitly in your gist. This may be a in the form of a program, pseudocode or just commentary, as discussed above. 

## Objective 2: Going deeper with OO

Implement **two** of the principles below in your code. First, define the term, then apply it in your code. Show a "before/after" example using comments to show the "before" version. If you can't easily show code as an example, do it in pseudocode or stories or any other method that makes sense to you. 

* Separation of Concerns
* Single Responsibility
* Tell Don't Ask
* What Vs. How (See POODR)
* Reducing Dependencies
* Decoupling Objects
* The Law of Demeter

For example, to explain Inheritance for the example of Bicycles:  **Inheritance** can be modeled as `MountainBike < Bicycle` and `RoadBike < Bicycle` since both Mountain Bike and Road Bike are Bicycles. A Bicycle has methods (or state) for gears, brakes, wheels.  Each of these is implemented differently in Mountain Bike and Road Bike. A Road Bike has caliper brakes where a Mountain Bike can have either V-brakes or disc brakes. Some methods are common to all Bicycles such as `accelerate` or `brake`. But other methods, like `absorb_bumps` would only be in the Mountain Bike class. 

(You would include your actual code here as the example.)

Note: This is a very brief example, but still illustrates the concept of inheritance. 

### You are done when...

You model two of the principles above. As you build your examples, find a way to briefly and succinctly illustrate the concept. Also make sure your examples contain the definition!

### What to submit 

Your definitions, code examples, and explanatory comments should be written out explicitly in your gist. This may be a in the form of a program, pseudocode or just commentary, as discussed above.  

##Releases
###Release 0 

##Optimize Your Learning 

##Resources