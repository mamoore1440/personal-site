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

A prime example of this irrelevancy for the information taught is Solow's Growth Model. The Model was ground breaking in 1987 but explains just about nothing in regards to the real world. Solow recieved the nobel prize in 1987 for his work but I doubt much changed with the invention of his model. The model, which takes in three variables: TFP, Capital, and Labor, doesn't even include things like debt. Incase you didn't know: TFP is just the progress of technology (A higher TFP means more advanced technology). The model is essentially a basic line you would have learned in grade school. Yet Solow won the Nobel Prize in Economics for this. Why he won I'm not sure; just about nothing can be gleaned from his model. The only information that can be gleaned would be useful to a nation that existed well before the industrial revolution. The model is genuinely so worthless that I actually thought the model was invented 200 years ago. I only found out it was made in 1987 when I wrote this paragraph. However, this model is the furthest academic economics has to understanding economics. This is extremely bleak.

My background is not from economics; I have a degree in computer science with minors in data science and economics. I have dipped my toes in academic economics but by no means have I swam in the pool. To be honest I'm not sure I respect academic economics enough to even sit on the side of the pool with my feet in. I don't even respect academics in regards to computer science which I firmly believe is way too focus on the minute and not on relevant information. Of course this is a critique of all of academics and a critique I believe that this is especially true for economics. 

The first economics course 90% of college kids take in college is microeconomics. We can very clearly see how distraught academics is just from how microeconomics is usually taught. Microeconomics mainly focuses on a single part of economics: markets. The majority of the semester is spent dissecting the market. Especially memorizing equations about markets: how to find the equilibrium, the surplus or shortage, the elasticity of demand, etc etc. This is essentially useless information in the real world and even worse is absolutely useless information in broader economics. The only part of this information that is useful is understanding what elasticity of demand means. It is important to understand some Demand is elastic while other Demand isn't, but to memorize how to find elasticity is a waste of just about everyones time. The same can be said of shortages and surpluses; luckily finding the values for those is realatively easy. 

But to say that this 101 course is the best introduction to economics would like saying dissecting a frog is the best introduction to biology. We don't even know where the frog lives, what it eats, or even how it eats. But academics asserts that dissecting markets is the correct way to start learning economics. Obviously this is not the case. The correct way to learn biology is to start broadly and then work your way in. This is true for all fields. When you were taught physics did you first learn about quarks? Or did you first learn about the atom? Obviously you started broad then worked your way in. Unfortunately, economics is taught backwards. You are told to memorize the market dissection, and are forced to find values that won't matter. Rarely are you taught how concepts apply to the real world. You dissected the frog immediately but didn't understand what the frog even was or did.

This problem permeates throughout the world. There is a fundamental lack of understanding in what economics actually is. This causes people, companies, and nations to misjudge reality and allocate resources inefficiently. You would be hardpressed to find true economic information in the world. Luckily for you I have created a model we can view reality through. This model will be a computer science state diagram not a function! There will not be any east conclusion. We will not be able to plug in values for variables and have a number as the output. Instead this will be an abstract view of the world. The model will have four components: Reality, Time, Humans, and the S&D Field. These components will be abstract representations of the real world. Reality in the model will mimic reality in real life, Time in the model will mimic time in real life, Humans in the model will mimic humans in real life. This mimicing will be done by having the model be more abstract than the world is. In other words Reality, Time, and Humans in the model will incorporate all complexing of the real world into matrix variables. These matrix variables will store all information about Reality and Humans. Time will not need any information stored and the S&D Field is just a way of viewing interactions between Reality and Humans. When I refer to the component moving forward I will capitalize the first letter. If I talking about the real world or using the word in a phrase it will lower case. So for example if I am talking about the component Reality, Reality will be uppercased. If I am saying a phrase like "in all reality" reality will be lowercase. The same is true for Human and Time.

In this part (part one) I will not draw any major conclusions about the model. We will simply set up the model and I will walk you through it. In part two we will add more complexity to the model, and I will draw some major conclusions. It is very important you understand what is happening in regards to the model. In part three when I do draw conclusions about real life based on the model you will need to understand how the model works otherwise you will call me insane. Please Understand what is happening with the model in first two parts. If you gloss over the first two parts without really understanding you will have wasted your time. I'd rather you stop reading if you are not going to put the work in.

I am first going to show you the components of the model. These are the four components I was talking about earlier (Reality, Time, Humans, and the S&D Field). Then I will make assumptions about the components but I will base them on real life. Then I will walk through logical deductions about the assumptions. From these deductions we will prove more facts about the model and in turn real life. The Components and Logic sections are the math behind the model. If you don't 100% understand the math it doesn't really matter. I need you to understand the high level of this model not the low level. To be honest the low level is only being fleshed out so that I can logically prove the assertions I will make later in this series so that I am not called insane.

There is an explanation sections at the end of this part which explains what happened in the Components and Logic sections. My end goal is to have everyone who wants to understand to be able to understand. Because of this I will be walking everyone through the model in the explanation section. Consider this as a college level class but being taught on a high school level. I will not ask you to do homework, quizes, or exams: I only ask you put in enough effort to understand what is happening.


# Components Of The Model:
## Reality
This is Reality.
* R(T) will return the state of Reality at Time T.
* Δ(R(T)) will return the next succession of the Reality matrix at Time T.
* R(T) = Δ(R(T-1)). This equation connects Reality in the present to Reality in the future.

## Time 
This is Time; Time always ticks forward.

## Humans
This is Humans
* Humans have Internal Utility
* H(T) will return the state of Humans at Time T.
* Δ(H(T)) will return the next succession of the Humans matrix at Time T.
* H(T) = Δ(H(T-1)). This equation connects Humans in the present to Humans in the future.


## Supply and Demand Field (S&D Field)
This is the field on which Humans and Reality interact. This is not physical like Humans and Reality: you can not point to Demand, Supply, or a Connection.
There are two parts to the field. One is Demands which originate from Humans and the second is Supply which originates from Reality.
Connections between Demand and Supply take place within a moment.

* F_D(T) will return the Demands on the field (*)
* F_S(T) will return the Supply on the field (*)

When a Supply and a Demand Connect on the Supply & Demand Field:
  * Internal Utility changes for all Humans.
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
  * Humans have Subjections of Reality
  * Humans are inventive
  * Humans are imperfect at viewing Reality
  * Humans have free-will
  * Humans interact with Reality based on their Subjections
* Reality
  * Reality does not have free-will
  * Reality changes over Time
* Time
  * Time always moves forward
* S&D Field
  * Humans and Reality interact with each other over the S&D Field
* The Model In General
  * The base measurements for Humans, Reality, and Time are the smallest possible measurements

## Proofs
### Humans
Humans have Subjections of Reality && Reality changes over Time
  => Human Subjections change over Time (1)

Humans have free-will 
  => Changes in Humans are nondeterministic
    => The future state of Humans is essentially impossible to determine (2)

Humans are imperfect at viewing Reality && Humans have Subjections of Reality
  => Subjections of Reality will essentially never be perfect (3)

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

The base measurements for Humans, Reality, and Time are the smallest possible measurements && Changes in Humans and Reality occur one at a time over these smallest measurements
  => These smallest changes can be combined together to form an aggregate change without losing information (This is integration in calculus)
    => Humans, Reality, and Time can be viewed at any scale with losing information (7)

Subjections of Reality will essentially never be perfect (3) && Humans interact with Reality based on their Subjections
  => The perfectly efficient S&D Connections will essentially never take place
    => Pareto efficiency is essentially impossible (8)

## What we have proven:
* Humans
  1. Human Subjections change over Time
  2. The future state of Humans is essentially impossible to determine
  3. Subjections of Reality will essentially never be perfect
* Reality
  4. The future of Reality can be calculated if there are no Humans
  5. The future of Reality can not be calculated if there are Humans
* The Model In General
  6. TFP will exist and improve over Time
  7. Humans, Reality, and Time can be viewed at any scale with losing information
  8. Pareto efficiency is essentially impossible


# Explanation:
What we have just created is an incredibly abstract view of the world. We have two parts to the Model. One side is the components which are mathematically defined as functions. The second part is the logic which is the assumptions, proofs, and proven facts. There are only four components, each of which are incredibly simple but contain the complexities of real life. The first part is Reality and we will start here.

## Components Of The Model
### Reality
This is Reality. (The matrix from _the matrix_)
* R(T) will return the state of Reality at Time T.
* Δ(R(T)) will return the next succession of the Reality matrix at Time T.
* R(T) = Δ(R(T-1)). This equation connects Reality in the present to Reality in the future.

You can think of Reality as the matrix from the movie _the matrix_. This is the physical world you exist and interact with. When you pick up a cup or flip a switch to turn on a lightbulb you are interacting with Reality. Reality does not require Humans to exist and will change over time without Humans. This would like a river cutting through the ground and creating a riving or an earthquake causing a tsunami. 

But because we have not introduced Time or Humans let's look at Reality without them. Fortunetaly there isn't much to see: In the model Reality is simply a mathematical matrix of information. We do not have to assign any variables or even look inside the matrix. We can simply say that the information matrix exists and contains all the complexities of the real world. Because Time does not exist yet Reality is static. Reality does not change or move. If the Reality matrix has a rock in the middle of the air then the rock will stay there. Only when we add Time will the rock move. Again, the information doesn't even need to exist in the math. We can simply assume Reality is represented in the matrix. We don't need to do any more work here so let's add time.

### Time 
There is not much complexity to Time. Time moves forward one unit at a time and the unit used is the smallest unit possible.

The only complexity in regards to Time comes up with Reality, so as Time moves forward now so does Reality. Before Reality was static and now it is dynamic. We can see this dynastic element with the three equations. 

* R(T) will return the state of Reality at Time T.
* Δ(R(T)) will return the next succession of the Reality matrix at Time T.
* R(T) = Δ(R(T-1)). This equation connects Reality in the present to Reality in the future.

R(T) simply returns that big mathematical information matrix about Reality we were talking about earlier. The variable T is simply the Time you want information from. So if the Time you input into R(T) is 'the first millisecond of May 7th 1502'. Then R(T) will return the state of Reality in that millisend. But it's important to understand that the units used for Time are the smallest unit possible. So the varible T would have to be defined all the way to the smallest possible unit of Time. However you can still assign T the value of 'the first millisecond of May 7th 1502' its just the smaller units of time would be 0. All in all, R(T) is simply a function we can use to find out the state of Reality based on a time we choose.

Δ(R(T)) will return R(T) but with any changes that occured at the smallest unit of time. This is the next step of Reality. R(T) is the state of Reality in the current Time and Δ(R(T)) is the state of Reality in Time + 1 (unit).

Based on the two equations above we can connect the present and the future as such: R(T) = Δ(R(T-1)). This equation simply says that the current state of Reality is the next step of the past state of Reality. In other words this moment in time is what came after last moment in time. This equations bridges all moments in time with the moment's immediate past. In this way we connect all of Reality in a temporal chain.

In sum: R(T) returns information about Reality based on a moment in time. Δ(R(T)) returns information about Reality one unit of time in the future of the given time T. And R(T) = Δ(R(T-1)) is used to connect all of Reality into a temporal chain.

Next let's talk about the Human component.

### Humans
This is Humans
* Humans have Internal Utility
* H(T) will return the state of Humans at Time T.
* Δ(H(T)) will return the next succession of the Humans matrix at Time T.
* H(T) = Δ(H(T-1)). This equation connects Humans in the present to Humans in the future.

Humans are Humans. As of right now they are the exact same as Reality except for one part: Internal Utility. 

Humans have an Internal Utility which is a term that comes from academic economics and is essentially their current happiness, joy, pleasure, etc: what ever you want to call it. Internal Utility is simply the happiness that Humans have in the moment. Internal Utility can be positive and negative and exists within a scale of -infinity to +infinity: Internal Utility can never actually be negative or positive infinity. While this is a varible that we have defined and can look at, unlike the matrixes, there really isn't a point in doing so. In regards to the model we only care about broad conclusions. To specify what Internal Utility should look like in regards to the real world is a waste of time. We only care that Internal Utility can be positive (happy) or negative (sad) and that the magnitude of happiness or sadness is the absolute value of Internal Utility. 

In regards to the equations they work the exact same way as Reality. H(T) will return the state of Humans at Time T. Δ(H(T)) will return the next succession of the Humans matrix at Time T. And H(T) = Δ(H(T-1)) connects the Humans matrixes in the present to Humans in the past. This connects all the states of Humans into a temporal chain.

### Supply and Demand Field (S&D Field)
The final component is the S&D Field. The S&D Field is a tad bit complex but not by much.

This is the field on which Humans and Reality interact. This is not physical like Humans and Reality: you can not point to Demand, Supply, or a Connection. 
There are two parts to the field. One is Demands which originate from Humans and the second is Supply which originates from Reality.
Connections between Demand and Supply take place within a moment.

This is not an actual field; nor is it physical. It's simply a way for us to visualize how Humans and Reality interact. Humans make Demand for the Supply that is Reality, and if the Demand Connects with Supply then there is a change in Reality along with a change in the Utility of all Humans. The change in Utility may be big or it may be small. The majority of changes that take place will be minute and will be essentially 0. If someone kicks a rock in China will someone in America care? The answer is no, BUT they will be affected and thus there will be a utility change.

The Supply and Demand Connections are not complex either. Again, this is simply a way of viewing how Humans interact with Reality. For instance if you raise you right arm you are making an S&D Connection. You are demanding your arm be raised and this connects if you raise your arm. If type on a keyboard you are Demanding your fingers move which will connect. When you pull a lever you are Demanding that the lever move. If you succeed in pulling the lever then the Demand (You) and the Supply (the lever) will have Connected. Supply and Demand Connections change the Internal Utility of all Humans and change Reality. There isn't much to understand here: Humans interact with Reality and these interactions are visualized with Supply and Demand on the S&D Field.

I will refer to 'Supply and Demand' as 'S&D' and I will refer to 'Supply and Demand Connections' as 'S&DC' moving forward.

There are two equations that exist for the S&D Field. The first is F_D(T) which returns the state of Demands in the given moment in Time. The second is F_S(T) which gives the state of Supply in the given moment in Time. It's important to understand that F_D(T) and H(T) are the same function but with different prioritizations. It's like if you asked for a list of student and classes they take vs. asking for a list of classes and the student who take them. All information that is returned in one function is returned in the other. This aspect of universalness is holds true for F_S(T) and R(T) also.

With that we now have our four components and so we should move onto the Logic.

## Logic

### Assumptions: 
Here are the assumptions we are making for the model. We will go through them one at a time and see if they are founded in reality.

* Humans
  * Humans have Subjections of Reality
  * Humans are inventive
  * Humans are imperfect at viewing Reality
  * Humans have free-will
  * Humans interact with Reality based on their Subjections
* Reality
  * Reality does not have free-will
  * Reality changes over Time
* Time
  * Time always moves forward
* S&D Field
  * Humans and Reality interact with each other over the S&D Field
* The Model In General
  * The base measurements for Humans, Reality, and Time are the smallest possible measurements

1. Humans have Subjections of Reality
This is a rather simple assumption and I don't think there will be much conflict here. For one I think it's obvious to think any one person's view of reality is their subjective view of reality. No one idividual has the "objective" view of reality. I've genuinely never seen the opposite of this be asserted so I think this one is clear to assume.

2. Humans are inventive
This is also a rather simple assumption. Humans solve problems and invent all the time. We went from cavemen to the moon so obviously we had to invent along the way.

3. Humans are imperfect at viewing Reality.
This sort of goes hand in hand with 1. Essentially no Human has a perfect view of reality. If that did happen it would be insane, they would never answer a question wrongly even as a baby. Another assertion I don't think many will disagree with.

4. Humans have free-will
This one will have a bit of flak. There is always a debate about whether or not Humans have free-will or not. Maybe all of existance is deterministic. Where ever you stand on this issue it doesn't really matter that much. It will affect small parts of conclusions but that will be in the later parts. To be honest this is only a minor assertion. Again, the model is really only being made to prove a couple of things about economics.

5. Humans interact with Reality based on their Subjections
This isn't an assertion about reality so much as a fact about the model. But it is important to understand and work with so I will put it in the assumptions.

6. Reality does not have free-will
I've never seen this not be the accepted position. I've never seen someone have the opposite take, so I'm just going to move on.

7. Reality changes over Time
Also another take that I've never seen the opposite be taken. No one has even been a Devil's advocate on this one.

8. Time always moves forward.
Again, another cold take. I'm just going to move on.

9. Humans and Reality interact with each other over the S&D Field.
Same as 5. Not really an assumption so much as a fact.

10. The base measurements for Humans, Reality, and Time are the smallest possible measurements
Same as 5 and 9. This is more of a fact.

This concludes the assumptions and so we can move on to proofs.

### Proofs
#### Logic & Proofs Explained
Because proofs and logic is taught rather awfully in middle, high and college I'm going to briefly explain it.

Logic is just math. The greeks believed there was a logical force that permeated reality and they called it the logos. Now a days people simply view this as math and mathematical proofs. You may have seen or done some proofs in high school, and if you were in an engineering, mathemcatical, or computer science field in college you may have done some proofs there. Nevertheless let's quickly go over it.

You can think of logic as the universal language. Just like how in English you can say "A dog is running after a ball" so too can you say this in Logic. In Logic you have define a bit more. Because it is the universal language everyone needs to be on the same page, and everyone can only be on the same page if everything in the statement is defined. So for our example we would need to define a couple of things. First we need to define 'running after', then a dog, then a ball. Luckily, we don't have to fully mathematically define each of these three. We don't have to get into exactly what 'running after' means or what exactly a dog is. Even if defining a ball would relatively easy compared to defining a dog we don't have to do it. We simply have to create variables and function that interact in a logical way. 

Again, for our example we need three things defined. A dog, a ball, and the process of 'running after'. For defining a dog and a ball we can simply create variables and say they are these things. So we can say the following:

For the two nouns:
* Variable D = "a dog"
* Variable B = "a ball"

For the one process:
* RunningAfter(X, Y) = "X is running after Y".

Then we combine the three together as:
* RunningAfter(D, B)

RunningAfter(D, B) simply means that "D is running after B". But we know that D = "a dog" and B = "a ball". So we substitute these definitions in and say that RunningAfter(D, B) simply means that "A dog is running after a ball".

Our original sentence in english was "A dog is running after a ball". And after defining the two nouns and the one process we can say that RunningAfter(D, B) also means "A dog is running after a ball". We have taken the english sentence and turned it into the unversal language that is logic. It's important to understand that we still had Enlish in the definitions but that doesn't matter. Logic simply combines the variables and processes in a concrete framework: It's a framework that will always work the same way and thus will always be understood by anyone in the same way.

Now onto proofs. 

Proofs are simply deductive reasoning. When are playing clue and are finding information and forming a conclusion about how the murder happened you making a proof. Proofs don't have to be expressed in the way either. Proofs can be written in any language. What matters with proofs is that the flow of reasoning stays true. This is why they are commonly used in mathematics. Math is very easy to remain 100% logical, and this is why most people's first encounter with proofs is in math. More specifically in geometry with triangles. Triangles have relatively simple proofs that are easy to work with. You don't have to understand higher math you just have to be able to do deductive reasoning given some facts.

A lot of people may have been given some facts about a shape and been to prove if the shape was a triangle. 

So for example if you were given the following facts:
* This shape has three edges
* All the edges are perfectly straight
and were to prove the shape was a triangle you coule do so in the following manner.

You would say that by a triangle by definiton has three perfectly straight sides. And because in the given information that the shape has three perfectly straight side that the shape must be a traingle.

This is a proof. Notice that symbols were never used and that whole sentence was in English. Proofs don't have to be in the logical language. We could define the given facts as logical variables but thats a lot of work when we could just give a couple English sentences.

Another example of a proof is this. Imagine there are three people in a house with one apple on a table. The first person, let's call him Bob, has to leave the house all day and do some work. The second person, let's call her Alice, is allergic to the apple and she knows this. If she eats the apple she will die in 24 hours. The third and final person, let's call him Brad, has nothing to do for the day and is currently hungry. There is no agreement between the three about the apple and all are free to eat it. The apple is eaten at some point in the day; the question is who ate it. We must use logical deduction to prove who ate the apple.

Bob leaves the house and two facts are confirmed. One, Bob did not eat the apple before he left as the apple is still on the table after he leaves. And two, Bob did not eat the apple after he left because he confirmed a mile away all day. From this we know that Bob did not eat the apple. He didn't eat it before he left and he didn't eat it while he was away.

Alice most likely didn't eat the apple because if she did she would die.

Brad most likely did eat the apple because Bob was confirmed not to and Alice would die if she did.

What we just did was a proof. We had three possible conclusions initially; one for each person.
* Bob ate the apple
* Alice ate the apple
* Brad ate the apple

We proved that Bob didn't eat the apple and we deduced that Alice didn't eat the apple. And because the apple was ate and Brad was only person left who could have eaten it then brad had to have eaten it. Again, we could write this out in the logical language if we wanted, but English works just fine and is easier to work with. At every step we simply took information that was given and logically deduced that other facts were true. So for example we were never told that Bob didn't eat the apple but we did deduce it. We were told three facts: one that after Bob left the apple was still not eaten; two, that Bob was away the whole day; and three, that apple was eaten sometime during the day. We can combine these facts and deduce that Bob did not eat the apple.

This is what that deduction looks like in english:
"After Bob left the apple was still uneaten, Bob was away the whole day, and the apple was eaten sometime during the day implies Bob did not eat the apple."

But we can also show this in the logical language. It would look like this
Facts:
* A = After Bob left the apple was still uneaten
* B = Bob was away the whole day
* C = The apple was eaten sometime during the day

Want to prove
* D = Bob did not eat the apple

Then we say A and B and C => D. This is exact same as the english sentence we had above. The symbol '=>' simply means implies.

There is another point to take into account. We never actually proved that Alice didn't eat the apple. Alice could have eaten the apple even if she knew she would die. But the vast majority of cases such as this Alice would not eat the apple. We can say there is a 99% chance that Alice did not eat the apple and a 1% chance that she did. However, even if there is a 1% chance, it still makes sense to conlude that Alice did not eat the apple. In academics this would be rejected but in the real world this is accepted. When Wall Street is creating profitable trading strategies they don't care if any one assertion is 100% true or not. Wall Street generally settles around 70%. This is important because when do proofs on the asumptions above they won't be 100% true. There will obviously be cases where the facts that asserted or concluded arn't 100% true. However, this does not mean that we should throw out the model or any conclusion from the model. We simply have to understand that the conclusion could possibly be wrong just like how there was a 1% chance Alice ate the apple. Another way to think about this is that next time you eat there is a non-zero chance that the food will enough cyanide in it to kill you. Is it logical then to never eat? Obviously not, the chance is so small it essentially never matter. The same principle applies everything in real life. 100% proofs, while nice, are niche. Life is not lived at that 100%.

Now that we understand logic let's work with both the assumptions and the model to prove a couple of things about the model. Let's start the Human based Proofs.

#### Humans
Humans have Subjections of Reality && Reality changes over Time
  => Human Subjections change over Time (1)

Our first proof is a rather simple one so it's a great place to start. We have two original assumptions:
1. Humans have Subjections of Reality
2. Reality changes over Time.

Because Humans have Subjections about Reality and because Reality changes then the Subjections have to change. This is more of a fact about the model rather than a point I need to argue.
We can conclude that Human Subjections change over Time is a true statement about the model based on the assumptions.


Humans have free-will 
  => Changes in Humans are nondeterministic
    => The future state of Humans is essentially impossible to determine (2)

The second proof is a bit more interesting. We need to conluded two facts from the original assumption. The second conclusion being based on the first.
Initially we are assuming that Humans have free-will. This implies Humans can do what they want and are not required to do any one thing. This means that Humans will not act like a robot or in other words are free. The conclusion we can easily draw from this is that the Changes in Humans are nondeterministic. From this conslusion we can easily conclude another fact. That the future state of Humans is impossible to know. In other words given H(T) it is impossible to know what H(T+1) looks like. You could guess and could be really accurate at times but in general you arn't going to know and even if you were correct in your guess you wouldn't be 100% accurate.

Humans are imperfect at viewing Reality && Humans have Subjections of Reality
  => Subjections of Reality will essentially never be perfect (3)

Our original assumption is that Humans are imperfect at viewing reality and that Humans have Subjections of reality. This implies that the Subjections Human's have are imperfect Subjections. Technically at times they could be perfect, but the vast majority of the time they won't be.

That concludes the proofs for Humans lets move onto proofs for Reality.

#### Reality
Reality does not have free-will && Reality changes over Time
  => Any changes in Reality that originate from Reality are deterministic
    => The future of Reality can be calculated if there are no Humans (4)

This first proof is rather simple. Reality changes and it does not have free-will and so the changes must be deterministic. Because the changes are deterministic the future must be deterministic. If the future of Reality is deterministic then it can be calculated.

Humans have free-will && Reality changes over Time && Humans and Reality interact with each other over the S&D Field
  => Any changes in Reality that originate from Humans are nondeterministic
    => The future of Reality can not be calculated if there are Humans (5)

The second proof is essentially the first but with Humans. Because Humans have free-will, Reality changes over Time, and Because Humans and Reality interact then any changes in reality that originate from Humans must be nondeterministic. Thus the future of Reality can not be calculated if there are Humans.

Finally proofs about the model in general.

#### The Model In General
Humans are inventive 
  => Humans will discover and invent over Time 
    => TFP will exist and improve over Time (6)

Here we start with an assumption about Humans. Humans are inventive and this obviously implies that Humans will discover and invent over Time. Because Humans are inventive and this inventiveness will only improve over time then technology has to exit. This technology is TFP. We can also conclude that TFP will advance over Time.

The base measurements for Humans, Reality, and Time are the smallest possible measurements && Changes in Humans and Reality occur one at a time over these smallest measurements
  => These smallest changes can be combined together to form an aggregate change without losing information (This is integration in calculus)
    => Humans, Reality, and Time can be viewed at any scale with losing information (7)

This proof is a really important proof and will mimic the fundamentals of calculus. The two assertions is that: One, the base measurements for the model are the smallest measurements possible. And two, that the changes in the changes in the model occur in these smallest measurements. From this we can conclude that we can combine these small changes together and form one big change without losing information. Just like how in mathematics you can combine small changes in a function to form conclusions about the function (integration). So too can you combine small changes in Humans, Reality, and the S&D Field together to form one big change.

From here we can conclude that we can view Humans, Reality, or the S&D Field with any sized scope without losing information about the components. If we want to consider a whole factory as a Supply we can do so. Even if the factory actually has multiple components inside of it. We don't have to condider the machinery, the air, or even the ground it is on. The scope can be whatever we want. This is extremely important and to be honest is a foundational fact about the model.

Subjections of Reality will essentially never be perfect (3) && Humans interact with Reality based on their Subjections
  => The perfectly efficient S&D Connections will essentially never take place
    => Pareto efficiency is essentially impossible (8)

The final proof is also important. One of assumptions in this proof is something proved earlier. This will happen multiple times in the next parts. We want to assume very little so that model can stay flexible and applicable to real life. 

Our two assumptions, one being proven from earlier assumptions, is that Subjections or Reality are essentially never perfect and that Humans interact with Reality based on the subjections. From this it's easy to conclude that the interactions (or S&D Connections) between Humans and Reality will never be perfect. Again, technically they could be but it would extremely rare. Because the interactions will essentially never be perfect then Pareto efficiency for an economy is essentially impossible. For those who don't know: Pareto efficiency is just peak efficiency. Every Decision made in a Pareto efficient economy is perfect. Only in very simple hypotheticals could Pareto efficiency be possible. In the real world Pareto efficiency is impossible.

This concludes our proofs.
### Final Facts About The Model
So why are we doing all this? for two reasons. Number one, we know that based on the four base components of the model-Reality, Time, Humans, and the S&D Field-combined with the ten assumptions we made that the eight proven facts have to be true in regards to the model. So for instance the first fact we proved, Human Subjections change over Time, now has to be part of the model. In the model Human Subjections have to change over time. If they didn't then the model would not be logical. And for the second reason: We know because the model is an abstract an abstract view of reality and that the assumptions are based on reality. That the proven facts have to be true in real life also. Again, the facts assumed and the facts proven are not very important so far. This first part is simply for us to understand the model. In later parts we will make assumptions and prove facts that give vital information about the real world.

Here is the overview of the facts assumed and proven.

Assumptions: 
* Humans
  * Humans have Subjections of Reality
  * Humans are inventive
  * Humans are imperfect at viewing Reality
  * Humans have free-will
  * Humans interact with Reality based on their Subjections
* Reality
  * Reality does not have free-will
  * Reality changes over Time
* Time
  * Time always moves forward
* S&D Field
  * Humans and Reality interact with each other over the S&D Field
* The Model In General
  * The base measurements for Humans, Reality, and Time are the smallest possible measurements

Proven:
* Humans
  1. Human Subjections change over Time
  2. The future state of Humans is essentially impossible to determine
  3. Subjections of Reality will essentially never be perfect
* Reality
  4. The future of Reality can be calculated if there are no Humans
  5. The future of Reality can not be calculated if there are Humans
* The Model In General
  6. TFP will exist and improve over Time
  7. Humans, Reality, and Time can be viewed at any scale with losing information
  8. Pareto efficiency is essentially impossible

Technically the inbetween facts also belong in the Proven section above. But I only included facts that actually mattered.

# Conclusion
This concludes part one. The next part is using the model in a utopian world. It will not be applicable to real life, but it will be important to look at so that we can understand how the model works.