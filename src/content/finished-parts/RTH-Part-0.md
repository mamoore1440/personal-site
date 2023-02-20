---
id: 119
title: "RTH Part Zero: Introduction"
slug: rth-part-2
date: Jan 1, 2023
img: hello-world.png
tags: []
---

# Logic & Proofs Explained
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