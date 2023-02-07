---
id: 120
title: "RTH Part One: Basics Of The Model"
slug: rth-part-1
date: Jan 1, 2023
img: hello-world.png
tags: []
---

# Introduction:
In academic economics there seems to be a fundamental misunderstanding of what is actually happening in economics. Academics spends way too much time memorizing equations, models, and variables that are of no use to real world. The models looked at are hundreds of years old and have no actual bearing. Most of the time the models looked at and tested over in academics, whether that testing be testing through exams or homework, are paradoxically both hyper specific and not useful at all. In my time in academic economics I have learned, memorized and have succefully passed tests about information that I have never actually even seen or used before. 

A prime example of this irrelevancy for the information taught is Solow's Growth Model. The Model was ground breaking in 1987 but explains just about nothing in regards to the real world. Solow recieved the nobel prize in 1987 for his work but I doubt much changed with the invention of his model. The model, which takes in three variables: TFP, Capital, and Labor, doesn't even include things like debt. The model is essentially a basic line you would have learned in grade school. Yet Solow won the Nobel Prize in Economics for this. Why he won I'm not sure; just about nothing can be gleaned from his model. The only information that can be gleaned would be useful to a nation that existed well before the industrial revolution. The model is genuinely so worthless that I actually thought the model was invented 200 years ago. I only found out it was made in 1987 when I wrote this paragraph. However, this model is the furthest academic economics has to understanding economics. This is extremely bleak.

My background is not from economics; I have a degree in computer science with minors in data science and economics. I have dipped my toes in academic economics but by no means have I swam in the pool. To be honest I'm not sure I respect academic economics enough to even sit on the side of the pool with my feet in. I don't even respect academics in regards to computer science which I firmly believe is way too focus on the minute and not on relevant information. Of course this is a critique of all of academics and a critique I believe that this is especially true for economics. 

The first economics course 90% of college kids take in college is microeconomics. We can very clearly see how distraught academics is just from how microeconomics is usually taught. Microeconomics mainly focuses on a single part of economics: markets. The majority of the semester is spent dissecting the market. Especially memorizing equations about markets: how to find the equilibrium, the surplus or shortage, the elasticity of demand, etc etc. This is essentially useless information in the real world and even worse is absolutely useless information in broader economics. The only part of this information that is useful is understanding what elasticity of demand means. It is important to understand some Demand is elastic while other Demand isn't, but to memorize how to find elasticity is a waste of just about everyones time. The same can be said of shortages and surpluses; luckily finding the values for those is realatively easy. 

But to say that this 101 course is the best introduction to economics would like saying dissecting a frog is the best introduction to biology. We don't even know where the frog lives, what it eats, or even how it eats. But academics asserts that dissecting markets is the correct way to start learning economics. Obviously this is not the case. The correct way to learn biology is to start broadly and then work your way in. This is true for all fields. When you were taught physics did you first learn about quarks? Or did you first learn about the atom? Obviously you started broad then worked your way in. Unfortunately, economics is taught backwards. You are told to memorize the market dissection, and are forced to find values that won't matter. Rarely are you taught how concepts apply to the real world. You dissected the frog immediately but didn't understand what the frog even was or did.

This problem permeates throughout the world. There is a fundamental lack of understanding in what economics actually is. This causes people, companies, and nations to misjudge reality and allocate resources inefficiently. You would be hardpressed to find true economic information in the world. Luckily for you I have created a model we can view reality through. This model will be a computer science state diagram not a function! There will not be any east conclusion. We will not be able to plug in values for variables and have a number as the output. Instead this will be an abstract view of the world. The model will have four components: Reality, Time, Humans, and the S&D Field. These components will be abstract representations of the real world. Reality in the model will mimic reality in real life, Time in the model will mimic time in real life, Humans in the model will mimic humans in real life. This mimicing will be done by having the model be more abstract than the world is. In other words Reality, Time, and Humans in the model will incorporate all complexing of the real world into matrix variables. These matrix variables will store all information about Reality and Humans. Time will not need any information stored and the S&D Field is just a way of viewing interactions between Reality and Humans.

In this part (part one) I will not draw any major conclusions about the model. We will simply set up the model and I will walk you through it. In part two we will add more complexity to the model, and I will draw some major conclusions. It is very important you understand what is happening in regards to the model. In part three when I do draw conclusions about real life based on the model you will need to understand how the model works otherwise you will call me insane. Please Understand what is happening with the model in first two parts. If you gloss over the first two parts without really understanding you will have wasted your time. I'd rather you stop reading if you are not going to put the work in.

I am first going to show you the components of the model. These are the four components I was talking about earlier (Reality, Time, Humans, and the S&D Field). Then I will make assumptions about the components but I will base them on real life. Then I will walk through logical deductions about the assumptions. From these deductions we will prove more facts about the model and in turn real life. The Components and Logic sections are the math behind the model. If you don't 100% understand the math it doesn't really matter. I need you to understand the high level of this model not the low level. To be honest the low level is only being fleshed out so that I can logically prove the assertions I will make later in this series so that I am not called insane.

There is an explanation sections at the end of this part which explains what happened in the Components and Logic sections. My end goal is to have everyone who wants to understand to be able to understand. Because of this I will be walking everyone through the model in the explanation section. Consider this as a college level class but being taught on a high school level. I will not ask you to do homework, quizes, or exams: I only ask you put in enough effort to understand what is happening.


# Components Of The Model:
## Reality
This is Reality. (The matrix from _the matrix_)
* R(T) will return the state of Reality at Time T.
* Δ(R(T)) will return the next succession of the Reality matrix at Time T.
* R(T) = Δ(R(T-1)). This equation connects Reality in the present to Reality in the future.

## Time 
This is Time; Time always ticks forward.

## Humans
This is Humans
* H(T) will return the state of Humans at Time T.
* Δ(H(T)) will return the next succession of the Humans matrix at Time T.
* H(T) = Δ(H(T-1)). This equation connects Humans in the present to Humans in the future.


## S&D Field
This is the field on which Humans and Reality interact. This is not physical like Humans and Reality: you can not point to Demand, Supply, or a Connection.
There are two parts to the field. One is Demands which originate from Humans and the second is Supply which originates from Reality.
Connections between Demand and Supply take place within a moment.

* F_D(T) will return the Demands on the field (*)
* F_S(T) will return the Supply on the field (*)

When a Supply and a Demand Connect on the Supply & Demand Field:
  * Internal Utility changes for all relevant Humans.
  * Reality changes in a deterministic way based on the single Supply and Demand Connection


(*) Note: 
* F_D(T) and H(T) are the same function but with different prioritizations.
  * Like if you asked for a list of student and classes they take vs. list of classes and the student who take them.
    * All information returned from one function exists in the other.
  * F_D(T) prioritizes Demands
  * H(T) prioritizes Humans
* This is the same for F_S(T) and R(T).


# Logic:
## Assumptions: 
* Humans
  * Humans have Subjections of reality
  * Humans are inventive
  * Humans are imperfect at viewing reality
  * Humans have free-will
* Reality
  * Reality does not have free-will
  * Reality changes over Time
* Time
  * Time always moves forward
* S&D Field
  * Humans and Reality interact with each other over the S&D Field
* The Model In General
  * The base measurements for Humans, Reality, and Time are the smallest measurements possible

## Proofs
### Humans
Humans have Subjections of reality && Reality changes over Time
  => Human Subjections change over Time (1)

Humans have free-will 
  => Changes in Humans are nondeterministic
    => The future state of Humans is essentially impossible to determine (2)

Humans are imperfect at viewing reality
  => Subjections of reality will essentially never be perfect (3)
    => The perfectly efficient S&D Connections will essentially never take place
      => Pareto efficiency is essentially impossible (8)

### Reality
Reality does not have free-will && Reality changes over Time
  => Any changes in Reality that originate from Reality are deterministic
    => The future of Reality can be calculated if there are no Humans (4)

Humans have free-will && Reality changes over Time && Humans and Reality interact with each other over the S&D Field
  => Any changes in Reality that originate from Humans are nondeterministic
    => The future of Reality can not be calculated if there are Humans (5)

### The Model In General
Humans are inventive 
  => Humans will discover and invent over Time 
    => TFP will exist and improve over Time (6)

The base measurements for Humans, Reality, and Time are the smallest measurements possible && Changes in Humans and Reality occur one at a time over these smallest measurements
  => These smallest changes can be combined together to form an aggregate change without losing information (This is integration in calculus)
    => Humans, Reality, and Time can be viewed at any scale with losing information (7)

## What we have proven:
* Humans
  1. Human Subjections change over Time
  2. The future state of Humans is essentially impossible to determine
  3. Subjections of reality will essentially never be perfect
* Reality
  4. The future of Reality can be calculated if there are no Humans
  5. The future of Reality can not be calculated if there are Humans
* The Model In General
  6. TFP will exist and improve over Time
  7. Humans, Reality, and Time can be viewed at any scale with losing information
  8. Pareto efficiency is essentially impossible


# Explanation:
What we have just created is an incredibly abstract view of the model. The Model only has four parts, each of which are incredibly simple. The first part is 