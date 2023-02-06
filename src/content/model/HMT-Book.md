---
id: 111
title: HMT Book
slug: hmt-book
date: Jan 1, 2023
img: hello-world.png
tags: []
---

HUMANS, MATTER AND TIME.

THE GOAL IS TO TURN ECONOMICS INTO A COMPUTER SCIENCE STATE PROBLEM.
To start we are going to create THE MOST abstract view of reality possible. It is going to be so abstract that you are going to believe it was a waste of your time to read it. That will not be the case. Any logical conclusion we can come to about the state diagram we can now conclude about real life.

# Basics Of The Model

## Just Matter
  Let's start with just Matter.

  Matter is made up of Things. There are Base Things and Compound Things. BT is Base Thing(s) and CT is Compound Thing(s).  
  BT are the most basic Things in Matter. For instance if the Matter was based on the knowledge of reality in the 1930s the BT would be the electron, proton, and nuetron. As time went on Humanity discovered that the standard model made up electrons, protons, and nuetrons and so with this knowledge Matter would have the standard model as BT. 

  CT are bit more complex but not by much. A CT is built by BT with a specific "Pattern". So if the CT was a single hydrogen atom then the CT would built by these BT {proton, electon} with a specific Pattern. 
  
  Let's create a function that will give us a CT based on input BT and a pattern. This function will be CT(BT, P) and is 1-1.

  We also need to add a little caviat about indentification. How do we know if a CT is different from another CT if they share the same BT and Pattern? Hypothetically there could be two hydrogen atoms with the same BT, and Pattern. Now we need to add Space to the model. Let's assume each Thing now has a location and no two things can share a location. If two things share a location they are no longer to things; they are one (this would be a case of fusion). 

  So far we have just Matter defined. Matter consists of BT and CT. CT are made up of BT with a Pattern. All Things have a location in Space. So let's finally define Matter. Matter is now just information about the model's "reality". You can easily think of Matter as the "Matrix" from the Matrix movie. Matter (in total) consists of all BT and CT along with locations on both. There are also Patterns for each CT. 

  For a less formal but simplier breakdown we have this.
  Matter:
    - Things
      - BT
        - Electron, Proton, or Nuetron
        - Doesn't matter what this is defined as
      - CT
        - Made up of BT
        - Has a pattern
        - CT(BT, P) will input BT and a P to get CT. 1-1 function.
      - Location in Space
      
  Matter is the same as Things and will be used interchangably. Matter can not make any actions. This is not to say that Matter does not change without interactions, but that Matter does not change itself. Matter never changes anything.

  A tiny bit complex so far. Please make sure you understand this. Matter is everything and all information regarding matter; essentially just a matrix of information about reality.

## Add Time
  Lets add Time into the mix. Time always ticks forward.
  
  Let's quickly describe a function to find Matter given Time. M(T) is Matter of Time. Given any positive Time: M(T) will return the matrix that is Matter. 

  For now-because we have only Matter defined-there is only one change to the model. Matter will now change over time just like how they do in real life. Erosion will create a rivine. Trees will grow over Time. Rivers will move rocks and Volcanoes will erupt. Much will happen as Time ticks forward. 
  
  "That's great and all but what does that mean?". 

  For one we now need to describe a function in which Matter changes over Time. So far we just have Matter and thus changes in Matter is determinate. The function we need to create is Δ(M(T)), change of Matter. Δ(M(T)) takes in a Matter matrix and outputs a new Matter matrix that is the succession of the old.
  
  At any given moment in Time we can now find what Matter looks like based on the last moment in Time. M(T) = Δ(M(T-1)). At each moment in time the matter matrix is static. Matter only changes when Time changes.

  Again this is deterministic. I am assuming only Humans have agency. Dogs, Cats, etc would thus all just be algorithms which would be deterministic and therefore taken into account in Δ(M(T)).

  This is a very simple way of viewing reality. Matter deterministically changes with Time. 

  Let's add to the less formal but simplier breakdown.
  Matter:
    - Things
      - BT
        - Electron, Proton, or Nuetron
        - Doesn't matter what this is defined as
      - CT
        - Made up of BT
        - Has a pattern
        - CT(BT, P) will input BT and a P to get CT. 1-1 function.
      - Location in Space
    - Equations
      - M(T) will give the state of Matter at Time T.
      - Δ(M(T)) will return the next succession of the Matter matrix.

  Again, not too complicated but please read until you understand what is happening.

  If we just "let the model lose" it would just be a Matter matrix deterministically changing over Time.

## Add Humans
  Finally we need to add Humans.

  Humans have Internal Utility and a Spirit. No Matter has Utility or a Spirit, only Humans have them. Humans create Demand which originates from the Spirit. 

  We are going to define Humans the same way we defined Matter except this time there is no split in Humans and there is nothing resembling a Pattern. H(T) is the state of Humans at a moment in Time. We are also going to need a change function. Δ(H(T)) is change of Humans. We can see Humans move from one point in time to another with H(T) = Δ(H(T-1)).

  In the real world Humans act indeterministically and thus are hard to model. Assume Δ(H(T)) incorporates both the deterministic and the free will based changes to the Human matrix.

  Humans create Demand (that originate from the Human's Spirit) with the intent the Demand Connects with Supply (Matter) on the Supply & Demand Field. These Demands can be complex or simple. They may be simply breathing or launching a rocketship. We will describe the Supply & Demand Field soon.

  When Demand Connects with Supply on the Supply & Demand Field every relevant Human's Internal Utility will change. The Human's Internal Utility may change a lot or it may change a little. Internal Utility is essentially just happiness of the Human. Each moment, when S&D Connect, there is a Utility change for all Human's Internal Utility. The intermoment changes to Internal Utility matter as well as the overall long running Internal Utility for a Human just like how your day to day happiness matter just as much as your yearly and lifetime happiness.

  Not every Human's Internal Utility will change with every Supply & Demand Connection. In the real world this could theoretically happen, but it would be would be extremely rare. I could really only see this happening if there was a small amount of people who are all entangled in one Supply.

  If we let this model loose currently it would just be Humans and Matter updating each other over Time. There wouldn't be much insight and it would be very boring.

  Let's add Humans to the breakdown.
  Matter:
    - Things
      - BT
        - Electron, Proton, or Nuetron
        - Doesn't matter what this is defined as
      - CT
        - Made up of BT
        - Has a pattern
        - CT(BT, P) will input BT and a P to get CT. 1-1 function.
      - Location in Space
    - Equations
      - M(T) will give the state of Matter at Time T.
      - Δ(M(T)) will return the next succession of the Matter matrix.
      - M(T) = Δ(M(T-1)).

  Humans:
    - Have
      - Spirit
        - The Spirit creates Demand
      - Internal Utility
    - Equations
      - H(T) will give the state of Matter at Time T.
      - Δ(H(T)) will return the next succession of the Matter matrix.
      - H(T) = Δ(H(T-1)).

  Because we have briefly touched upon both Supply and Demand I will start using "S&D" instead of saying "Supply & Demand"

## What Is The S&D Field?
  You've probably noticed we have two sets of terms. "Matter and Humans" and "S&D". These are essentially interchangable but let's formally describe the interaction just to remove any confusion. To do this we are going to split the sets of terms and say they are related to each other based on the S&D Field. "S&DF" is "Supply & Demand Field" or "S&D Field".

  Matter and Humans are the most basic units in this Model. Matter is essentially just the Matrix from the Movie _The Matrix_ and Humans are just Humans.

  Matter does not need Humans and Humans do not need Matter. 
    _In the real world Humans obviously need Matter, but I want the model as abstract as possible so just ignore that._

  Humans create Demand that originates from the Spirit.
  Matter is Supply.

  Because we know the following
    - Humans and Matter both change over Time
    - Demand originates from a Human's Spirit
    - Supply is Matter
  we now also know that Demand and Supply change over Time.

  So how do Humans and Matter interact?
    Through Supply and Demand.

  Not helpful. How do Supply and Demand interact?
    They interact on the S&DF

  What is the S&DF?

  Great question. A Human's Demand will always want to Connect with Supply from Matter. In a very simple case of a Human wanting to breathe the interaction is easy to see. The Human who wants to breathe is creating Demand for oxygen. This oxygen is part of Matter which means the wanted oxygen is Supply. So, in sum, the Human is creating Demand for Supply and the Supply-who the Demand wants to Connect with-is oxygen. If the Human does successfully breathe this means that the Demand Connected with Supply. If the Human fails to breathe that means the Demand failed to Connect with Supply. In this case the Human would be in a bit of a panic. Not all potential S&D Connections will be this serious. Maybe a Human wants to eat a sandwhich in which case failure wouldn't really matter.

  The created Demand and inherient Supply do not actually exist. Don't get me wrong the Humans and Matter do exist; it's just S&D does not. You can never point to a Demand or point to a Supply. You could point to a Thing but not a Supply. And you could point to a Human but not a demand. The S&D both exist on a Field. A sort of battleground. On this battleground it is decided which S&D will Connect and which won't.

  It's important to understand S&D do not exist in Space. Again, you can not point to Supply or Demand. Because of this it's hard to visualize the processes involved. Because of this difficulty we are going to view S&D on a "Field". This Field will be visualized like a simple euclidean plane. There will be Supply and there will be Demand on the Field. The location of the Supply or the Demand on the Field is irrelevant. This is simply to visualize what is happening. A Demand could Connect with a Supply even if they are very far apart. 

  The Supply will look a shape because it is the easiest way to visualize Matter (Things) as being different from each other but similiar in the fact that Supply is not Demand.

  Demand will be visualized as an arrow with a number at the tip and a shape in the middle. The number at the tip will be the number of who's Spirit the Demand originated from. And the shape will be the Supply the Demand wants to connect with. If the arrow has a 3 at the tip then you will know the Demand originated from Spirit #3. If the arrow has a circle in the middle then you will know the Demand wants to Connect with a circle (whatever the circle may be).
  
  The origin of the arrow on the plane is irrelevant, but the origin of the arrow in respect to who's Spirit it came from is relevant. This is why the number is at the tip. Later the origin will have greater importance on it.

  On top of this it's important to understand that in the real world there is essentially an infinite number of Things thus there would need to be an infinite number of shapes. Obviously this is not possible so there will always be not enough shapes shown to be 1-1 with the real world. 

  Let's do a quick breakdown again:
  S&DF:
    - Supply
      - Visualized as shapes
    - Demand
      - Visualized as arrows
      - Number at the tip is to associate the Demand with a Spirit
      - Shape in the middle is to visualize what Supply the Demand wants. 

  In sum, the S&DF is not a physical field. You can not point any of the three: Supply, Demand, or the Field itself. The S&DF is simply a way of visualizing how Supply and Demand interact or connect. From this visualization we can see how Humans and Matter affect each other over time.

## Intricacies Of The Model

### TFP
  Humans are curious creatures. We like to solve problems and engineer solutions. We are not happy with being complacent and to explore and learn. This drive that exists in all Humans is the drive that pushes us forward. Specifically forward through knowledge and by the definiton of knowledge it pushes us through technology. Technology is ever expanding, ever encompassing, and undestroyable. Once the cat is out of the bag in regards to a specific technology it is really hard to put the cat back it. 

  In academic economics this technological progress is widely considered as the variable TFP. At times in academics when working with a specific equation, wether it be labor output, capital output, national output, etc, you may see TFP being assigned the letter 'A'. This variable 'A' simply represents technological progress. 

  TFP is not a variable in the model, but it is inheirent in the model. As time increases so to will technological understanding. As technological understanding increases so to will a Human's ability to manipulate Matter increase. This is TFP; Human's ability to manipulate Matter the way we want to. They will be able to create things that earlier they didn't know were possible. 
  
  For example when Humans started understanding the steam engine for the first time we were now able to create factories. This was a main precursor for the industrial revolution and thus allowed people to live better lives. 
  
  TFP advancement let us have phones in our pocket. It let us have laptops and computer, rockets and battleships, tanks and satellites, and even steel or silicon chips. TFP affects everyone. The only reason we live so well in the 21st century compared to the 4th century is TFP advancement.

  In sum TFP is simply technology. As time moves forward TFP so to will TFP and thus a Human's ability to manipulate Matter the way the want.


  //Add Later: Capitalism did not improve your life standard; it simply allocates resources efficiently. This means what you earn is highly correlated to how much you work. Life standard is improved by TFP not income. Capitalism influences the rate of TFP but capitalism does not affect whether TFP grows or not. Remember TFP is technology and really hard to put back in the bag.

### The Frame of Reference Is Ambiguous 
  Because the model is so abstract we can now ignore the intricacies of scale. If you want to say a factory is a Supply you can do so even if you are ignoring the fact that factories are made of smaller components like machinery. Humans will interact with the factory the same way they interact with a phone: through S&D Connections. It doesn't matter that the interaction actually took place in a small way or that the interaction didn't fundamentally change the Supply. The scale or frame of reference is whatever you say it should be. If you want to look the the molecular level then so be it. If you want to look at the building level then so be it. What ever you want the frame of reference to be you can make it that. 

  This is also applicable to Time and Demand (Humans). All three components of the model do not have an inheirent scale. Thus the frame of reference can be what ever you want!


## A Quick Overview Of The Model
  There are two main parts to the model so far. There is Matter and Humans, and there is the S&DF. The physical and the non physical.
    
  Matter is M(T) and changes over one moment in Time with Δ(M(T)). The present and the one moment forward future is related with M(T) = Δ(M(T-1)).
  Humans is H(T) and changes over one moment in Time with Δ(H(T)). The present and the one moment forward future is related with H(T) = Δ(H(T-1)).

  Physical
    Matter:
      - Things
        - BT
          - Electron, Proton, or Nuetron
          - Doesn't matter what this is defined as
        - CT
          - Made up of BT
          - Has a pattern
          - CT(BT, P) will input BT and a P to get CT. 1-1 function.
        - Location in Space
      - Equations
        - M(T) will give the state of Matter at Time T.
        - Δ(M(T)) will return the next succession of the Matter matrix.
        - M(T) = Δ(M(T-1)).
    Humans:
      - Have
        - Spirit
          - The Spirit creates Demand
        - Internal Utility
      - Equations
        - H(T) will give the state of Matter at Time T.
        - Δ(H(T)) will return the next succession of the Matter matrix.
        - H(T) = Δ(H(T-1)).

  Non Physical
    S&DF:
    - Supply
      - Visualized as shapes
    - Demand
      - Visualized as arrows
      - Number at the tip is to associate the Demand with a Spirit
      - Shape in the middle is to visualize what Supply the Demand wants.

  As we've discussed earlier, every S&D Connection changes both Matter and Humans. With regards to Matter it changes Things in some way which changes Supply on the S&DF. With regards to Humans it changes Internal Utility and all relevant Humans will update what Demands they have. It's important to notice that with every S&D Connection both Demand and Supply will change on the S&DF.

  As Time ticks forward one moment at a time we will see H(T) and M(T) change. Any change that occurs for Humans in a moment will originate from a single or multiple Demand and Supply Connecting in the moment. We can not say the same about Matter. Matter changes may originate from a S&D Connection or from Matter deterministically changing over Time.

# Start Using The Model (Pre-Sin)

## Let's See How The Model Works With One Person
  For now let's start off with just one Human in Humans. 

  This Human will want to change the enviornment, they will want to eat, drink, etc. They may want to make a house or feed chickens. Maybe help a calf be born. No matter what the Human wants to do they will always create Demand. This Demand will show up in the S&DF. If any of the Demands Connect with Supply Matter will change and the single Human's Internal Utility will change. Because there is only one Human the Human's Utility will essentially only go up. Just about Human _in real life_ will act in a Utility Maximizing behavior. Obviously there are occurances where this doesn't happen. On top of this, the Human will never have Demand Rejected. They are the only Demand. No one else is there to Demand Supply that the one Human wants to Connect with. 

  The Human creates and destroys Demand in the moment. And as moments progress the Human will have Demand Connect with Supply which will occur on the S&DF.

  In any given moment the Human can only have certain Demands connect with Supply. In other words the Human can not do two things at the same time. If the Human wants to jetski they can not create demand for reading a book. In the moment: either the Human jetskis or reads. Which ever action they do determines which Demand Connects with Supply. If the Human decides to read then the Demand for reading will Connect with Supply but the Demand to jetski will not. Because of this we have Opportunity Cost.

  _In the real world_ everyone faces Opportunity Cost. You can not get drunk and stay sober at any given moment in time. You can not eat just eggs and eat just bacon in the morning. That isn't to say you can't eat both in the morning. If you want to eat eggs and bacon in the morning then be my guest. But if you eat both you did not eat just bacon or just eggs. The common saying is "You can't eat your cake and have it too". All Humans experience Opportunity Cost because of this. When more Humans are brought into the model to further our understanding then we will see more complexity to Opportunity Cost.

  There is also another aspect to talk about. How does the Human know what it wants to do? All Humans have a Subjective perspective on both Matter and Humans. They will have a subjective perspective on all Demand and all Supply. In this way Humans do not know the true outcome of every possible S&D Connection, but they do have a Subjective perspective on all of them. The perspective may be close to the truth or it may be far.

  So what do I mean? 

  When this Human creates a Demand for some Supply there is an objective change to the Human's Internal Utility and Matter if the Demand Connects with the Supply. However, the Human does not know what that true change is for either Humans or Matter. What the Human think is going to happen is the Human's Subjective Perspective. Human's have a Subjective Perspective on all Supply and all Demand. Even if the Demand did not come from them. Ownership of Supply is irrelevant here as there is only one person. Who would dispute the one Human's claim to the world?

  In this way Humans will choose to Demand for Subjective Utility Maximizing decisions in hopes it maximizes actual Internal Utility. 

  I'm going to add a couple of terms here and in the example we will see what I mean for each.
  OUS is Objective Utility for a Subject
  SUS is Subjective Utility for a Subject

  ### A Quick Example To Understand Decision Making
    In a moment there are two possible S&D Connections with different OUS and SUS. The Human can only facilitate one of the possible Connections.
    
    Possible Connection A has OUS = 20 & SUS = 30
    Possible Connection B has OUS = 50 & SUS = 5

    Because there is one Human there only one Subject. This means that the Subject (the final 'S') in OUS and SUS has to be for this one Human. There is an Objective/Subjective split (the first letter; 'O' and 'S') because there is a true change and an expected change. The true change is Objective while the expected change is Subjective. 

    For all Possible Connections between any S&D there is a single OUS for every Human. This is because there is an Objectively true change all Human's will have for their Internal Utility when a S&D Connection happens. The 'S' in "OUS" is the Subject in context. For now, because we only have one Human, the Subject will always be this one Human. When we have two people there will be two OUSs per possible S&D Connection. The two OUSs will have different Subjects (the two different Humans).
    
    In regards to SUS it is not that simple. Every Human has a different perspective and thus every Human has a different percieved outcome. This is where SUS, which is different than OUS, comes into play. The first 'S' in "SUS" refers to the Human doing to Subjecting. The 'U' is Utility. And the last 'S' is about the Human who is affected. It is important to understand that every Human will have a SUS for every other Human as the subject in regard to every possible S&D Connection. There were three "every"s in that sentence so it's very easy to see that there gets to be a lot of information to handle very quickly. 
    
    For now because we only have one Human there is only one OUS and only one SUS per possible S&D Connection. When we have two Humans there will be one OUS per Human for each possible S&D Connection. There will also be 4 SUS per possible S&D Connection. Each Human will do the Subjecting and be the Subject.

    Quick Table:
    Number of Humans  | Number of OUS / possible Connection | Number of SUS / possible Connection  
    1                 | 1                                   | 1
    2                 | 2                                   | 4
    3                 | 3                                   | 9
    n                 | n                                   | n*n

    Here the Human will choose to facilitate Connection A because the SUS is higher. But objectively this was an awful decision; Connecion B offer over twice the OUS!

  Based on the example it is very easy to see that Humans are dumb! They will choose to facilitate S&D Connections that do not maximize OUS. They will choose to facilitate S&D Connections that maximize SUS in an attempt to maximize OUS. Not every time will the Human be wrong. More often than not Humans will make the OUS maximizing decions. In this case the single Human will have made a "bad" decision, but it won't matter: OUS was positive and ignorance is bliss. As far as the Human is concerned he made the OUS maximizing decision. 
  
  It is also very easy to see Opportunity Cost here. If the Human chooses to facilitate Connection A then they also choose not to facilitate Connection B. And the opposite is also true. If the Human chooses to facilitate B then they did not facilitate A. The Opportunity Cost of A is B and the Opportunity Cost of B is A. 

  With just one individual the model is rather boring. There is no complex interactions outside of Opportunity Cost and Subjectivity. The world is this one Human's Oyster! If the Human could live forever they would end up with infinite Internal Utility.

## Let's Add A Second Human
  As we saw with one Human there were two aspects to look at. We saw Opportunity Cost and Subjectivity. We also saw a brief glimpse into Value. These concepts were not hard to grasp or even work with. They were easy to work with only because there was only one Human. When we add a second, third, fourth, Nth Human it becomes a bit more complicated. How does Subectivity and Opportunity Cost work when two Humans are Demanding the same Supply? How does ownership work? Does the first Human own everything? Is the second Human then a slave? How do possible S&DC get prioritized? 

  Well to start let's seperate the two Humans simply to make the model easier. In this way they will never Demand the same Supply. Let's also name them to make it easier to work with. The first Human will be named "Adam" and the second "Eve".

  Opportunity Cost and Subjectivity work the same. Both Humans will choose to make S&DC that maximize Internal Utility based on what they view (subjectively) as Utility maximizing. Each Human can "own" whatever is around them and because they are completely seperated there will be no conflicts. 

  Both Humans would live hapy prosperous lives. Their section of the world is their oyseter.

  Rather boring; let's throw them together. 

  Say they did live in the same part of the world and they did interact together. How would it look?

  Well this is a rather tough question. In academics there is behavioral economics to try and explain this, but because I want the model to be completely abstract I will be making one assumption to explain how the Humans will behave. The assumption is that these Humans do no sin. I will call this part of the model pre-sin. Later, when we fully understand the economics of pre-sin, we will move to post-sin. Post-sin is much more complicated. Post-sin is also, quite obviously, where the real world is and where insight can be gleaned. But to understand post-sin we need to understand pre-sin. 

  In pre-sin there is only one assumption. That given any choice the Human will make the Utility Maximizing decision for the biggest group of Humans. What do I mean by this? Humans will always prioritize each other over themselves in this way. In this way there will never be hoarding, no one will be to lazy to work, etc. 

  ### Example 1:
    We have two possible Connections where Adam decides which Connection is to be facilitated. Only one Connection can take place.
    Here the Subjecting force is Adam. The first 'S' in SUS here is Adam. The second 'S' in SUS for this example is for Adam, Eve, and both in that order.

    Possible Connection A
      - OUS = 20 & SUS = 30 for Adam
      - OUS = 15 & SUS = 10 for Eve
    Possible Connection B
      - OUS = 30 & SUS = 25 for both Adam and Eve

    To briefly talk about SUS and OUS for the example: here we know that Adam views Connection A as offering 30 Utility for Adam and 10 Utility for Eve. We also know that the objective change in internal Utility for Adam and Eve will be 20 and 15 respectively. Adam's estimations are decent. He in correct in his estimation that he will enjoy Connection A more than Eve and that Connection B offers better Utility overall.

    Here Adam will choose to facilitate Connection B simply because in B there is greater SUS for everyone. 25 + 25 > 30 + 10. Adam will have facilitated the Connection that creates the most OUS for everyone. While this is the goal for all Humans pre-sin it is not always the case. In the example provided if Connection B had offered 10 SUS for both Adam and Eve then Adam would have chosen to facilitate Connection A. This would not have been the OUS optimizing decision, however, Humans are generally pretty good at making rational choices so Adam and Eve would live rather happy lives together simply because they are both choosing to make Connections that optimize OUS for everyone. Even if they aren't perfectly optimal they are still very happy in both the short and long run. 

  This will be the case for the majority of S&D Connections. Most of the time Adam and Eve will do their own thing. They will take each other into account but most of the time they will focus on maximizing their own Internal Utility simply because they are in the position to do so to the greatest extent. While Eve could Adam happy, Adam can certainly make Adam happy.

  This was an example of pre-sin decision making for one Human between two connections. Let's switch it around and have two Humans with one possible Connection. This will be done by having one Supply that both Adam and Eve Demand. Only one Demand can Connection with the Supply, so only one Human can have a successful Demand for the Supply. In the real world this might be one crab to eat, one chair to sit in, etc.

  ### Example 2:
    We have one Supply with Demands coming from both Adam and Eve. Adam and Eve both have their OUS and SUS in regards to both S&D Connections. 

    Possible Connection A (Adam's Demand Connects with the single Supply)
      - Objective:
        - OUS = 30 for Adam
        - OUS = -3 for Eve
      - Adam's perspective:
        - SUS = 40 for Adam
        - SUS = -1 for Eve
      - Eve's perspective:
        - SUS = 10 for Adam
        - SUS = -5 for Eve

    Possible Connection B (Eve's Demand Connects with the single Supply)
      - Objective:
        - OUS = -1 for Adam
        - OUS = 20 for Eve
      - Adam's perspective:
        - SUS = 0 for Adam
        - SUS = 10 for Eve
      - Eve's perspective:
        - SUS = 1 for Adam
        - SUS = 30 for Eve

    Here there is a conflict. Only one Human's Demand can Connect with the single Supply. Adam and Eve will have to decide between each other who's Demand gets to Connect. Objectively Adam's Connection creates more Utility. Will they decide to facilitate Adam's Connection? 

    Both Humans want to maximize OUS but they believe different Connections maximize OUS. Eve believes Eve's Connections maximizes overall OUS and Adam believes Adam's Connection maximizes OUS. 

    Now in the real world this would talk multiple moments to decide; sometimes minutes, hours, days, even months. But there will be a decision and someone will connect with the single supply. How is this done in a pre-sin world? Adam doesn't know Eve's perspective and Eve doesn't know Adam's perspective. How are they going to decide who gets to Connect?

    They communicate with each other! Adam expresses his opinion on the matter and Eve does the same. Based on the communication each Human will have a better understanding of SUS. Let's speed forward some time and say 5 moments have passed. Now they know each other's perspective better and both have a better understanding of the overall situation.

    Possible Connection A (Adam's Demand Connects with the single Supply)
      - Objective:
        - OUS = 30 for Adam
        - OUS = -3 for Eve
      - Adam's perspective:
        - SUS = 35 for Adam
        - SUS = -2 for Eve
      - Eve's perspective:
        - SUS = 25 for Adam
        - SUS = -3 for Eve

    Possible Connection B (Eve's Demand Connects with the single Supply)
      - Objective:
        - OUS = -1 for Adam
        - OUS = 20 for Eve
      - Adam's perspective:
        - SUS = 0 for Adam
        - SUS = 18 for Eve
      - Eve's perspective:
        - SUS = -2 for Adam
        - SUS = 21 for Eve

    Because of the communication that took place between the two there is now a better understanding of the situation. Adam and Eve both have better subjective estimations of Utility. Of course there is still a problem. Who gets to Connect? Adam and Eve both have their own estimations of Utility but they both know that the true Utility is unknown by both. They will have to come up with a way of deciding.

    Now, with a better understanding, they are both on the same page. Adam's Connections maximizes OUS for everyone and so Adam will Connect. Eve loses some Utility and Adam gains, but the overall Utility change is higher in Connection A than B.

    Of course when Adam's Demand Connects then Eve's will die. There will be no Supply for Eve's Demand to Connect with. 

    This example only have two Humans, but there could be a situation where n amount of Humans are Demanding k Supply given n>k. The fundamentals of the situtaion would still hold. Humans will communicate preferences and unserstanding. SUS will change as moments progress. Demand will filter Demand to see which k amount of the n Humans get to Connect with Supply. 

  ### Take A Step Back
  
  As we can see even in a pre-sin world Demand filters Demand for what Demand Connects with Supply. In the above example there was two Demands and one Supply. Demand decided between itself which Demand should Connect. This was the filtering of Demand!

  Demand filtering Demand is the best way to maximize OUS in S&D Connections. However, Demand filtering Demand will largely only take place in a pre-sin world. 

  Pre-sin, 100% of S&D Connection conflicts, like the one above, will be resolved with Demand filtering Demand. Excluding human error, this leads to maximum overall OUS for all S&D Connections. 
  
  Post-sin, Supply will filter Demand. This will lead to maximum OUS for a sinlge Human at expense of the maximum overall OUS for each S&D Connection. That isn't post-sin a overall OUS maximizing Connection can't take place it just isn't the norm. But for now we do not have to think or worry about post-sin.

## Let's Give An Overview Of The Model So Far
  So far we Humans, Matter and Time. Humans do not sin and thus overall OUS is maximized. 

  In regards to the S&D Field: Humans will interact with Matter. Humans do this by Demanding Supply and will facilitate S&D Connections as a way of interacting with Matter. Important to note the S&D Field does not physically exist. This is simply a way of viewing how decision making happens along with interaction between man and matter. 
  
  In regards to Humans: Humans will not operate at 100% efficiency simply because of human error. In academics there is a term thrown around called "pareto efficiency". Pareto efficiency just means 100% efficient. This will never happen, not in the model or in the real world. Human error does exist. However, the Humans won't mind. Pre-sin they will make what they believe to be the best decisions for everyone. If there is a non OUS optimizing S&D Connection made it's no big deal. Every Human will facilitate Connections they view to be optimal. Ignorance is bliss eliviates any sadness about Humanity not acting at 100% efficiency. 

  In regards to Subjectivity: Every Human will view every S&D through their own subejctions. On top of this they will also have subjections about every possible S&D Connection. Communicating estimations is how S&D conflicts are resolved. When the S&D conflicts are resolved no one is sad, mad, or otherwise unhappy because of the decision made. This is simply because Humans are pre-sin and thus have a guiding ideology (maximize OUS for everyone).

  In regards to Objectivity: There is an objective change in Internal Utility for every Human for every S&D Connection. The change could be so small that it is irrelevant. If a rock is kicked in New York then all Internal Utility of all Humans living changes. However, what does a chinesse citizen care? Their Internal Utility change will be essentially 0. 

  In regards to S&D Conflicts: In a pre-sin world Demand will filter Demand for access to Supply. This leads to OUS maximizing S&D Connections. All Humans are happy with the process because they know that overall OUS will be maximized. 

## Let's Add A 3rd, 4th, ..., Nth Human
  When adding Humans in a pre-sin world there is only one consideration to take into place. The only cosideration is: Are there enough resources for everyone after one more Human is added? 

  Because all Humans have the guiding ideology of everyone over themselves there is no conflict and life is a utopia. Thus the only problems that can occur are the extremes of time. Maybe there is a case where the world does not enough food and by adding one Humand another of starves. This would obviously suck for the Humans and should probably be avoided. 

  Other than this only consideration there is nothing wrong with adding another Human. Humanity will prioritize the whole and live in a utopia. 

  Just to work through some facets of the model that exist only when multiple Human exist: let's go through some examples of how the Humans would interact with each other and Matter. 

  There are three facets to explore. The First being SUS when there are n amount of Humans; the second is ownership; and the third facet is organizations of Humans.

  The First facet is easy so let's start there. Humanity will always prioritize the whole over the part while pre-sin. This means that every Human will take every Human into account when facilitating S&D Connections. This means that Human 1 takes Human 1-n into account. Again, most of the time other Humans will not matter. Humans will make decisions mostly between themselves and thus other Humans will not matter. Think of the rock kicking analogy. If Human 1 kicks a rock on one side of the world would any Human on the other side care? Would any Huamn over 50ft away even care? Any Human that many be next to them? Most S&D Connections will only affect a small subset of Humans to a sizable degree. 

  The second facet is also just as simple. How does ownership work in a pre-sin world? Who owns what? Well the answer to the question is that no one owns anything. Ownership of Matter (Supply) would simply not make sense. Humans already act with each other's best interests in mind. Why would you even need to have ownership? Humanity as whole in regards to matter would act as a communist system. I don't mean the USSR communism, Chinesse communism, or any other real world application of communism. I mean strictly theoretical communism where it's a utopian economic system. As I've said before this is obviously not how the real world operates. But because we are pre-sin we can say that this model is a working communist model. There is no need for any Human or Organization to own any Matter (Supply).

  The final facet is a tad bit more interesting. Humans will eventually start creating groups and those groups will Demand certain Supply. The groups of Humans are simply organizations. When just Adam and Eve existed this could still take place. Maybe both Adam and Eve worked together to move a rock in which case an organization, consisting solely of Adam and Eve, would have moved the rock. In this example the organization would have also been all of Humanity. When you there are a lot of Humans organizations stop being all of Humanity. As with all Humans pre-sin organizations will also Demand Supply with all Humans in mind. Post-sin this changes but for now we are in the theoretical communist utopia. Organizations, just like Humans, do not own anything. If the organization believes Demanding a certain Supply is in everyone best interests then they will do so. Finally S&D conflicts would be resolved the same way as they were before. Demand would filter Demand by Humans communicating with each other. In this case the organization-or who ever in the organization is making the Demand-would be a Human communicating with any other human in the S&D Conflict. 

## Value In A Pre-Sin World
  Value is a rather hard concept to understand, explain, or even just design. To be perfectly frank I'd rather not touch on Value, just because it is so complex, but I do not have that luxury and for this model to mean anything we need to understand Value. So the question must be asked "What is Value?". A rather TOUGH question.

  In regards to the real world people view Value as a means to an end. They buy stocks, real estate, gold, silver, watches, collectable, even old games or Pokemon cards because they are "valueable". But what does that even mean? Most people who buy gold don't touch it; they don't look at it; they don't eat it; they certainly don't make and drink gold smoothies; and they don't plant it to a make gold tree that rains gold in the summer. So what "Value" does gold have? Gold is means to an end for people who collect, hoard, or invest in it. Feel free to use whatever term you deem appropriate. When people hold gold they are only holding it so that they can sell it later at a higher price than what they bought it at. They know gold has no use. They are simply hoping or know or whatever that in the future they will get more for their gold than what they put in. Again, a means to an end. 

  But in the model, so far, we are pre-sin. No Human "owns" anything because there is no need to. There is no need to invest in or hoard gold. No reason for silver or any other metal. Assets like real estate and equity certainly don't exist. Which raises the question then "What is Value?". Ugh, a rather TOUGH question.

  Based on the above reasoning it's rather hard to define Value here, but it's not impossible. You can always declare a way to Value something or some action. In this way you will be creating a value function. In the real world, and we will talk about this a lot later, markets are primarily used as _thee_ value function.
  
  We can say that every possible S&D Connection have a Value to them. What would that Value be? Well the Value of a possible S&D Connection would be its ability to facilitate another S&D Connection in the future. This would be the Value Function we are currently using. For instance if there was an S&D Connection about one Human planting an apple tree we could say that this Connection is rather valuable. Why? Because this allows Humanity in the future to eat more apples. I.E. the S&D Connection (of planting the tree) leads to more S&D Connections being possible in the future (eating apples). 

  Decent definition but there are some obvious flaws. Every S&D Connection allows for more S&D Connections in the future. For instance if you made a hole in the sand while at the beach there is an obvious new possible S&D Connection of just filling in the hole. If you kicked a rock there is a new possible S&D Connection of kicking it back to it's original spot. The majority of S&D Connections will lead to new possible S&D Connections that are rather dumb. For these "dumb" S&D Connections we can Value them by how much OUS or SUS they offer the one Human. I'm going to use both OUS and SUS just because we can. The model is not physical and meant to be used as a way of understanding the real world. Because of this we can take into as much information as we want into the Value Function. 

  Another obvious flaw is how far into the future are the new S&D Connections possible? Does it take 20 years for the new S&D Connection to come into fruition? When kicking the rock the new S&D Connection was instant, but planting the apple tree took a bit. 

  Both of these flaws would have to be taken into account. Fow now, the Value of each S&D Connection would be the ability to facilitate more S&D Connections in the future with time, OUS, and SUS taken into account.

## Final overview
  This is a utopian society. Every Human acts with every Humans interests in Mind. There are no S&D Connections that are made with the intent of putting on Human's preferences or Internal Utility above the whole of Humanity. This could happen on accident but no Human will actively do it. There is human error and thus nothing runs at pareto efficiency. 

# Add Sin To The World
  //TODO Important to talk about why these changes need to be made?
    Demand needs to be filtered.

  Unfortunately the model we have created has little to no use in the real world. Humans do not prioritize Humanity over themselves. In this way all real world communism applications will fail. The USSR became a bastion of totalitarianship and oppresion, and China created the bird-in-a-cage model where they would allow capitalism until it interfered with the CCP's power. There are various differences between the model pre-sin and the real world. One quick diffrence that matters is that money, debt, and finance don't exist pre-sin. And that's for good reason. There is no need for money, debt, or any sort of finance in a pre-sin world. But, of course, all three and much more exist in the real world. So what's the main difference? The difference, quite obviously, is Sin. Humans in the real world act with their own interests in mind. They do not act with Humanities, societies, or even organizations that they are apart of in mind. Humans can at times work towards a greater existance (Humanity, Society, etc) but this rarely happens. Generally this only happens when a society is in a sort of golden age and is particularily unified. 

  So let's add sin to make the model more applicable to the real world. The only change we are going to make is that now Humans will prioritize themselves over any other Human, organization of Humans, or Humanity as a whole.

  What changes first?

## Humans Have Cohesion
  Well before-when we were pre-sin-there was no need for private property. No Human owned anything Humans simply coexisted. Now that is not possible. Humans will be lazy, loathful, and all around greedy. Given the choice of a "free" lunch a Human will take it. Now of course, this isn't completely compatible with the real world. Humans do nice, caring, and loving actions at times. Does this mean they are without sin? No, just in the moment they prioritized the whole of Humanity over the part of Humanity. Which means we need to add a level of cohesion between Humans.  

  Cohesion between Humans will simply measure the want or desire to prioritize the greater good OUS maximizing decision over the self OUS maximizing decision. In this way, for every Human there is a cohesion level between the Human and themselves, every other Human, every organizaion, and the whole of Humanity. Cohesion is going to exist on a scale of 0-100, where 100 means they will prioritize the greater good decision always and 0 means they will prioritize themselves no matter the outcomes of an S&D Connection. Because Humans now have a cohesion level between themselves and every Human (including themselves), every organization, and even all of Humanity this becomes a lot to deal with. I'm not going to give examples or go into specifics. I'm just going to say the logical conclusions to part we are pondering. 

  I think it's important to understand that even though Humans can hypothetically have cohesion at 0-100 it is rarely ever the case. Most of the time, in the real world, Humans don't 100% hate or 100% love anyone or any organization. Usually Humans exist in a range where they are indifferent. But the same principle applies that applied in the rock kicking analogy. There is always an idea of "out of sight, out of mind" that exists for everyone. Someone in Malaysia is going to care very little about an organization in Iceland. The only organization that everyone is truly apart of and everyone at some level or another cares about is Humanity as a whole. This driving care for Humanity probably stopped the world from being nuked in the 60s-80s. That or it was MAD that saved everyone...

  To take it back to the model: What is the first change that occurs when Humanity can sin? Well Humanity can now prioritize a part over the whole-which was unthinkable before-and because of this there is now cohesion. What comes next? Well we now need private property, and let's now see why.

## Private Property
  //TODO split this up into sections.

  Because Humans are now able to simply be lazy they are now able to Demand Supply that they otherwise would not want to. For example in a pre-sin world having your food stored all in a central location would be the best option for a community (assuming food safty is fine). This would lead to the most efficient way of allocating the resource (the food). But post-sin now someone can just walk up and eat; then go home and sleep; then go and eat; then sleep; eat; sleep. And repeat that process without adding anything to the community. Obviously the community isn't going to be too happy about this one Human's actions. So what do they do?

  They take one of two actions. The first action is to "dispose" of the Human in a certain way. This could just be flat out killing them. Maybe it's kicking them out into the wild. Or maybe their hands are cut off. Some way or another the community will find a way to deal with the troublesome Human. The second and more commonly used action is to create private property. 
  
  As we've seen before there was no need for private property: Humanity was a utopian species who was only ever happy. Now Humanity has troubles and these troubles need dealt with. But what exaclty is the trouble? Humans now Demand Supply (in effect creating an S&D Connection) that is not benifitial to everyone. In the case above a Human is eating without working. The Human is Demanding Supply but not creating useful Supply himself. He simply wakes up, eats, and goes back to sleep. There is Demand that no one has the power to prevent from being created except the very Human who is making the bad Demand! 

  The solution is to come up with a way of filtering demand. How is this done? Part of Matter is now sectioned off into the possesion of a Human. This sectioning takes a part of Matter out of the community chest and into private property. Before, in pre-sin, the community's food existed in the community chest. It would have been so free in that community chest that if another Human from a different community wanted to eat everyone would have been okay with it. Now, post-sin, even Humans in the community need to be checked. The need to filter Demand has been birthed. The only question now is who owns the food?

  The question of ownership is quite simple. Someone has to own the food. If everyone held their own food in their own house the owners are quite obviously individual Humans. If the food is still kept in the central location but everyone in the community decides that the community owns the food then who ever owns the community owns the food. If the community had a totalitarian leader who murdered any opposition then the one lone totalitarian dictator owns all the food. If the community was a democracy then the food would be owned by everyone in a split. If the community was run by an oligarchy then the oligarchy would own the food. At the end of the day only Humans can own something. No organization (in this case a community) or the whole of Humanity can own anything. Ownership always goes down to an individual. 

  For this example there was only a need for private property in regards to food. But generally, in the real world, there is a need for ownership on quite a bit. In today's world people even buy plots on the moon. The moon no longer exists in the community chest but now is private property to be bought and sold. However, this isn't to say everything exists in private property. Quite a bit exists in the community chest still. What exists in the community chest still? Air does, and so does water in the ocean. You can take as much water from the ocean as you want. No one is going to stop you. 

  So now Matter can exist in the community chest or as private property. If the Matter is in private property then someone owns it; no organization can own anything. 

  But this has dramatic affects for how Demand Connects with Supply. Before, in pre-sin, Demand always filtered Demand for which Demand was allowed to connect with Supply. But now that Humans sin Demand no longer has the authority to filter Demand. Because of this now Supply must filter Demand. So when Supply enters private property now who ever own that Supply has the authority to reject Demand. In the case of food who ever owns the food gets to say who eats. It's extremely important you understand that there was a change in the Supply and Demand dynamics. In pre-sin Demand filtered Demand. In post-sin Supply filters Demand. The Supply filtering is done through private property and who ever owns the supply has the right to filter Demand for that Supply. 

  ### Income
  Proof: The existance of private property causes the existance of income. 
    Ownership of Supply changes over time => Individually held wealth changes.
  
  Proof: Individually held wealth changes => Subjections change. Proof by definition. 

## Debt
  ### Why Debt Exists
  There is an inheirant problem with private property however. Private property did a great job at filtering Demand. When Demand filtering Demand stopped working it allowed Supply to filter Demand. However, now there the economy is rife with inefficiency. The beloved and mythical pareto efficiency is impossble for a second reason now. Before in pre-sin if it was believied to be OUS optimizing for a S&D Connection to take place it did. Now in post-sin the possible S&D Connection has to be approved by who owns the Supply. However, this leads to quite a lot of cases where OUS optimizing S&D Connections are denied by Supply owners. A quite obvious example of this would Steve Job's Mac. A revelutionairy computer which didn't get enough funding or resources for a long time. In this example Steve was denied S&D Connections that maximized OUS. This denial delayed the creation of the mac and in turn any resources not spent on the mac was an inefficient allocation. If Humanity wanted the economy to run at peak efficiency then Steve's S&D Connections should not have been denied.

  There are many other instances of this scenario occuring. Projects, organizations, or even just Humans have their Demand's rejected because of private property. We can't remove private property because now there is too much Demand. People can be lazy and just eat and sleep. We need private property but a way of allowing some Demands to Connect. 

  The solution Humanity has come up with is debt. Say a Human, let's call him Adam, who owns just enough to survive has an idea for the steam engine in a world without any industrialization. To invent and sell his idea of the steam engine he needs his Demands for Supply to not be rejected. So what does he do? He goes to a different Human, let's call her Eve, who does own the Supply Adam needs and asks for his Demands to not be rejected in the present. In effect, he would like his Demands to Connect with Eve's Supply. Eve's obviously isn't going to be too happy about this. Unless Adam and Eve have perfect cohesion and both truly believe in the idea then this a bad idea for Eve to do. Even in a pre-sin world Eve may not even think this to be a good idea. It's important to understand the world in this example has no industrialization. So for Adam to go upto Eve and say "hey, I have a crazy idea but I need your resources for it be fulfilled" Eve's gonna think Adam's lost his damn mind. So in a post-sin world it makes even less sense. As far as Eve is concerned Adam's gonna take the resouces and run off. 

  Now Adam is pretty intelligent. He knows that Eve is never going to just let his Demand Connect with her Supply. So what does he do? He promises her an equal amount of Supply in the future. But that's not enough. Eve would be losing in this situation. How? Eve loses the ability to Connect with her own Supply during the time between Adam's Connecting in the present and Adam's repaying in the future. Eve doesn't like losing but she sees an opportunity. She offers the Supply in return for the same amount of Supply in the future and bit more. That "bit more" is the interest. Adam agrees, makes the engine, changes the world, gets rich, repays Eve, and Eve get's a tad bit richer. 

  Adam and Eve in the scenario above have just created debt. In this case the interest was a fixed amount of supply. However, in the real world, interest can come in different forms. You could have fixed or adjustable.
  
  It's important to note that debt was created BEFORE money was created. In the real world the first debts were about agricultural product. Seeds were loaned and then repaid after a harvest. 

  ### Debt Bringing Demand Forward In Time
  Again, why does debt even exist? Because people may need the ability to faciliate an S&D Connection when they don't own the neccesary Supply. In pre-sin, no Demand was rejected it was simply filtered. Now Demand has to be rejected as a way of filtering. But this leads to a reduced amount of demand. We no longer are making S&D Connections that facilitate growth in the economy or growth for society. The level of aggregate S&D Connections is below what it was pre-sin. 
  
  Now to explain how debt affects demand I need to assert a fact that most of academic economics doesn't have (as far as I know). It is widely believed that that demand can not be manipulated. That on a certain level demand is static. I do not believe this to be the case, and to understand why we need to understand Demand, Supply, and S&D Connections pre and post sin.

  Let's start with Demand. Pre-sin we see Demand filters itself. Post-sin Supply has to filter Demand. On top of this, we see that, at times, Demand can be created by Humans that do not maximize OUS for everyone. But a lot of this Demand can't be rejected bcause only the owner of the Supply can reject Demand. So if a Demand is created from a Human with the intention of Connecting with a Supply owned by the same Human than the Demand will not be rejected even if the possible S&D Connection is detrimental to either Humanity or even the Human. For example if someone owns herion and wants to do it it would be both detrimental to Humanity and themselves. They would immediately have a high which would give them quite a lot of Utility but would also immediately become addicted leaving both them and Humanity worse off. But the S&D Connection can't be stopped because the owner of the Supply is the same Human who made the Demand.

  Next is Supply. Before Supply was owned by no one and everything was in the community chest. Now Supply is owned by someone. This means the owner of the supply can reject Demand while before no Demand was rejected.

  Finally we have S&D Connections. Because now Demands can be made that are not OUS maximizing, Demands can connect with Supply based not on an objective OUS for any subject simply because of ownership of Supply, and the owners of Supply can now reject Demand we now a minimized amount of total S&D Connections that take place in any time frame. Whether you consider the "correct" time frame to be moments, days, months or years is irrelevant. On any time scale the total number of OUS maximizing S&D Connections will be lower. But this causes many issues mainly inefficiency. To deal with this problem we created debt. Debt allows for two parties-one who has Supply and one who has Demands for the Supply-to create an S&D Connection that benifits both. The Demanding party gets to Connect with Supply in the present and the Supplying party gets the same amount of Supply and more in the future. Again, the "more" is interest of the debt. Any Supply that the Demanding party creates past the initital Supply and the interest Supply is profit that the Demanding party gets to keep. The only caviet is that the Supplying party is taking on lots of risk. What happens if the demanding party can't pay back the loan? If this does happen the Supplying part has LOST Supply. And if the Supplying party loses Supply they will have lost a certain amount of the ability to create Utility for themselves. No one wants to lose Supply.

  So we have a tool Humanity can use to facilitate S&D Connections in the present and a cost of risk. The Supplying party takes on the risk and because of this the Supplying party decides when the tool should be used. If the Supplying party believes that the debt will benifit the Supplying party alone then the debt will be created. The Supplying party does not care about the Demanding party. If the Demanding party creates no profit then the Supplying party does not care. If the Demanding party creates a lot of profit then the Supplying party does not care. The only possible outcome that the Supplying party does care about is if the Demaning party can not pay off the loan. In other words if the Demanding party uses the Supply but does not create enough Supply to pay back the loan.

  Now I just gave an overview of debt again. Did you notice the temporal part?

  Before the loan is created there is no S&D Connection. The Demanding party wants to create Demand that Connect with Supply they do not own. And Supplying party wants to hold their Supply simply because it allows for themselves to Connect whenever they want. But after the loan takes place there are S&D Connections. The Demanding party gets the Connection they want and the Supplying party loses their Supply with the promise of more supply in the future. 

  Did you notice the temporal part?

  When the loan is created there are S&D Connections with the hope of more S&D Connections being available in the future. In this way, we are bringing S&D Connections forward in time. Before the Supplying party would have kept their Supply to themselves simply because this means the Supplying party would be allowed to Connect with the Supply when ever they deemed it correct to do so. Now the Demaning Party does connect and there is a promise of more Supply in the future.

  Very important to understand. We are bringing S&D Connections forward in time with debt with the assumption that these S&D Connections will allow for more S&D Connections in the future.

  ### Types Of Debt
  It's important to understand the types of Debt and the terms involved. I generally see a classification system for debt which has four types. There is productive and unproductive; and there is toxic and non toxic. I think this classification system is a pretty good way to classify debt and so I am going to explain the four types. I will also talk about how the four types show up in the model.

  But first the classification system. And to start we are going to talk about productive and unproductive debt. Productive debt is debt that produced something. So for example if you took out a loan to build a steel beam factory that would be productive debt. Unproductive debt, or sometimes called consumer debt, is debt that doesn't product anything. So for example if you took out a loan to buy a hotdog that would be unproductive debt (or consumer debt). 

  The other bifurcation in debt is toxic vs non-toxic. Toxic debt is debt that is not paid off fully. On the flip side any debt that is paid off fully is considered non-toxic debt.

  We can combine the two bifurcations together and create a (sort of) punnet square to classify debt.

  Debt exists in one of these four categories:
  
                |Toxic | Non-Toxic
  --------------------------------
  Productive    |PxT   | PxNT
  Unproductive  |UPxT  | UPxNT

  Let's look at each category. 
  
  Right off the bat we can make an assertion about UPxT. UPxT is the worst kind of debt. This is debt that was inheriently consumption and it was consuption that had no chance of being paid off. 
  
  UPxNT is a little bit better. This debt is debt that did get paid off but it was still just consumption. There was no gain to Humanity as a whole, but both parties are better off. The Demanding party got to Connect with Supply and the Supplying party got their interest. Here the Demaning party wanted Utility more than they wanted Supply. 

  PxNT is the best kind of debt. This is debt that benefited everyone involved. Not only did the debt help the Demanding party and the Supplying party but because this debt was productive it produced something! Humanity as a whole now has a factory, mine, farm, etc. 

  PxT is tricky however: no clear assertion can be made about this kind of debt. This is debt that went to producing something but couldn't be paid back. However, just because the debt is toxic doesn't mean the debt is bad. This debt can be great for Humanity but just fail to be paid back. For example if a loan is created to allow a company to research and develop a next generation computer but fails to be paid back it isn't neccesarily bad. The company could have discovered or invented processes, functions, or analytical viewpoints that are incredibly valuable to Humanity but just arn't profitable. Again, Steve Jobs and his mac are perfect example here. Even if the first mac wasn't profitable it was still a good idea for it to be funded. It revolutionized the world with how accessable the computer was for everyone. PxT debt is actually the second best debt Humanity can create!

  If I was going to rank the debt types in order of best to worst in regards to Humanity I would rank them as such. PxNT, PxT, UPxT, and UPxNT. There is a tie for the fourth and third which depends on how much of the initially loaned Supply was Connected with. The less Supply Connected with the better. Because the debt is UP any Supply Connected with is "wasted" Supply in the eyes of Humanity. This Supply was Connected with simply for Utility (for pleasure).

  Now let's connect this to the model.

  We already have the toxic and non-toxic split as that is about whether the loan was paid off or not. So if the loan is defaulted on then the loan is toxic otherwise the loan is non-toxic.

  The productive-unproductive split is not inheirently in the model but can be easily incorporated. In regards to the Model there exists Demand and Supply which Connect in the from of an S&D Connection. And the concept that can be worked with to create the productive-unproductive split is Value. The dread Value has shown up again.

  When any S&D Connection takes place there are changes to all Humans and all Supplies that are affected. Again this changes Value but who knows what the before or after looked in like or even what the change was. Value is unknowable; a blackhole. Don't try to peer into it or you'll get lost forever. But the productive-unproductive split is defined though so that leaves us in the dark. But we can incorporate it! If the S&D Connection added to Value (in what ever way you defined) then the S&D Connection is a "productive" S&D Connection. If the S&D Connection lost Value (again in what ever way you define) then the S&D Connection is a "unproductive Connection". 
  
  So for example: if you ate a hotdog which allowed you to live long enough to invent a perpetual motion machine then the S&D Connection of eating the hotdog was a "productive" S&D Connection as it added Value. But if you ate the hotdog, threw it 5 minutes later, and didn't invent the machine, then the S&D Connection of eating the hotdog was "unproductive". But if you ate, threw up, and invented the machine then it was "productive". But even in this example it matters what you define as Valuable. Maybe value is defined by how much puke an S&D Connection creates in which case only the first example of eating and simply inventing would be viewed as "productive".

  In any case we can not definitively define an S&D Connection as "productive" or "unproductive" but we can say that given a definition for Value that all S&D Connections can be defined "productive" or "unproductive" based on the value definition. This may seem useless but given a widely accepted value function we can glean information about the real world.

  ### Debt Overview
  As of right now debt is between two parties with an agreement on a specific supply (usually seeds). But the important part is that the Demanding party can not get a loan of a Supply that the Supply party does not own. So for instance if the Demanding party wants a nuclear reactor but the Supply party doesn't have a nuclear reactor then the loan can not be created. The Demanding party can only demand what the Supply party has. After Money is introduced we will look at debt again as this facit no longer exists with debt.

## Money
  ### Barter
  Now so far we private property and debt, but in the real world we also have money. So where does money come in to play? As we saw in the last section there wasn't even a need for money for debt to be created. So what facilitates money then? Why does money exist? Well at the start it didn't. What did exist was barter. People would trade ownership of Supply for ownership of Supply with each other. If someone had 1 cow but wanted 2 pigs they would go to the market and try to find someone who wanted a cow for 2 pigs. If the person did exist and they found each other then the trade could take place. But this become unsustainable fast as there are a couple of problems that arise. 
  
  The first problem is that both parties need to exist and have to want to partake in the same trade of Supplies but on oppostite end. In the case above about a cow and 2 pigs someone had to want 2 pigs for 1 cow and another person had to want 1 cow for 2 pigs. This problem is called the double coincidence of wants. 
  
  The other problem that arises is a question of Value. Unfortunately the dreaded Value has shown up. Each person has their own subjections what the value of each Supply is. This is Subjective Value or SV. Each person's SV of a Supply is unique to that individual. The first Human (who wants 2 pigs for a cow) subjectively values the two pigs higher than the cow. On the other hand the second Human (who wants a cow for 2 pigs) subjectively values the cow higher than the two pigs they currently own. Because of this difference in subjective value the trade can take place. After the trade happens both parties believe they are better off. Total SV owned by both parties goes up. Please, please, please don't ask about actual Value. Only God knows how Value changed even in the hypothetical I created. Both, one or none of the parties might be better off in terms of Value. But most importantly both parties believe they are better off.

  In this current example both parties believed they would better off post trade and thus the trade toke place. If both or one of the parties believe that they will be worse off after the trade then the trade won't take place. Maybe the cow looks sickly or the two pigs look small. There are essentially an infinite number of reasons that the SV of wanted Supply is percieved lower. This percieved low SV causes the trade not to happen.

  ### Commodity Money
  So what's the solution? Barter was doing so well at facilitating change in ownership of Supply. But the problems, double coicidence of wants and double coicidence of antithesis subjective value, become exponentially worse as both more Humans and dinstinct Supply exist. The main problem being that there is no standard of Value. Humans are not good at Valuing things. Humans start gravitating to owning more widely subjectively valuable supply that stays valuable longer. In this way people moved from bartering their Supply with other to bartering to hold more of the universally valuable Supply. The Supply to fill this role was grain. If kept properly grain could last quite a bit. So people would trade or work their way to grain and just hold it.

  In this way grain was the first commodity money. Grain was universally accepted as a "valuable item". In this case grain actually did have value. You could make bread with it and eat. This first commodity money has a lot more instrinsic value than the next widely accepted ones will. Nevertheless the grain served a new role other than its initital role. The grain became Abstract Subjective Value (ASV). Everyone viewed grain as having value and thus could be traded for other Supply. It became the first money or ASV. 
  
  ### ASV
  Let's talk a bit more about ASV before we get back into the origin and evolution of money. 
  
  Note that it's abstract subjective value not abstract value. Abstract value is not something that could ever exist. Each Supply has it's own value based on what ever you deem to be the defition or funtion of value. There is no Supply that is abstract value. If there was a Supply that could be abstract value then there would be a Thing that could serve EVERY role in reality. You would be able to eat or drink that Supply. You would be able to use it as rocket fuel or as concrete. You would be able to drive it to work. This Supply obviously doesn't exist. There is no abstract value. BUT we as a society can assign a Supply the role of abstract subjective value. We can create or designate a Supply to be a respresentative of abstract value. This creation or designation process is what we as a society do to create money. Important note: A Supply fills the role of ASV. There is no ASV you can point to. It was made up to greese the wheels of economics post-sin.

  But back to the first ASV. For a certain Supply to act as an ASV the vast majority of a society has to believe that the Supply does logically fit the role of ASV. If the majority of people stop believing the Supply fills the role then the group ideology collapses like a ponzi scheme and the role of ASV goes unfilled. The society would revert back to a barter economy. Very rarely in the modern day is this the case. The majority of the time when there is a crisis of failing faith in the ASV people simply assign a different Supply to serve the role of ASV. Humans love the existance of money. Greece during the European debt crisis is the only example I can think of where society did revert back to a strict barter system. However, this may also simply be the case because the other Supplies that are commonly used as ASV were out of the hands of the 99%. In the case of crisised Greeks it's safe to assume that the 99% did not have gold or silver to trade with and so the vast majority went to barter.

  When a Supply is given the role of ASV and is widely accepted the SV of the Supply goes up. Think of the fiat you hold. What actual value does it have other than you being able to trade with it. When you buy or sell for ASV you are trading a Supply with actual Value for a Supply with only subjective value. Poeple only make this trade because they are confident that later down the line the ASV can be traded back to Supply which has actual Value. Think about a $10,000,000 ranch that is self sustaining versus $10,000,001 in cash. Which has higher Value? Which has higher SV?

  For a supply to become an ASV it has to serve a couple of purposes. Sometime you'll see money being assinged 3-5 function in academics. Here money (ASV) serves three roles. 
  
  Firstly ASV is used to facilitate changing in ownership of Supply. This again is a ponzi scheme for confidence though: if the majority of society simply believe that the selected Supply can't or doesn't fulfill the role of ASV anymore then it will no longer be used to facilitate the changing of ownership of Supply. If this is the case then the selected Supply no longer serves the role of ASV and the role is either filled by a different Supply or it goes unfilled in which case the economy reverts back to a barter economy. 

  Secondly ASV is used as a way of measuring the value of supply. Humans will start measuring every other Supply in relation to the ASV. They may say one apple is worth 1/20 of a pound of grain or a cow is worth 30 pounds of grain. When you see money being assigned 5 roles one of them will be that money is a unit of account and another is that money is a way to measure value. Here the two roles are combined; ASV becomes both a way to measure Supply and the unit.

  Lastly ASV becomes a way of storing wealth. As stated earlier ASV now becomes a universally subjectively valuable Supply. In this way if you store ASV you are storing subjective wealth. The ASV can be traded for Supply and thus storing ASV is akin to storing Wealth. The only problem with this is that if the confidence does collapse then does your wealth. Your wealth is tied to the group ASV ideology. 

  ### Commodity Money Again
  To get back to commodity money, as we've already glimpsed a bit into the modern day we can see that the economy doesn't use grain as the ASV. So what happened? Well grain has a couple flaws. Firsly, It doesn't last forever and secondly it's really annoying to use as ASV. Even under perfect conditions it will deteriorate over time. And if you as a Human are hoarding grain as a way of hoarding your wealth then as time progresses your wealth will erode. On top of this grain also is annoying to use as ASV. No one wants to carry around hundreds of pounds of grain to pay for things. Do you really want to pay for college in grain. I know nothing about grain but I know that would quite a lot of grain. Another issue is that not all grain is the same. One could always pay with bad grain and keep the good grain for themselves. People then trading Supply for the ASV wouldn't be too happy. We need to come up with a solution to these problems. We need an Supply that doesn't deteriorate over time, or at least doesn't deteriorate as much, and we need a Supply that is uniform and easy to handle.

  In academics money is sometimes assigned a couple of "requirements" relating to these problems. Usually it is said that Money must be easily divisable and easy to handle. But as we saw with grain that wasn't the case. But grain was actually used as money, so that mean that money has these "requirements" or that grain wasn't money? Well grain was obviously money, so obviously money doesn't actually require these "requirements". But when a Supply selected for the ASV role does fulfill these "requirements" it is a better Supply to assign the role of ASV than other Supplies who do not fulfill these "requirements". Theoretically a society could use dirt as ASV it's just the confidence in that Supply as ASV would be hard to maintain and would deteriorate and collapse fast. The confidence in grain as ASV did deteriorate and collapse and people went to the next ASV. But what was that?
  
  Over time with advent of technology Humanity could mine, melt, smith, and coin metals. Metals don't deteriorate over time as bad as grain does and can be easily carried around. On top of this no one has ability to pull metals out of thin air. It requires time, effort and resources to create metal coins. Thus the coins were scarce. Grain is also a scarce resouce which leads to another "requirement" that isn't truly a requirement. The "requirement" being that the selected Supply must be somewhat scarce. Again, dirt could be used as ASV but it wouldn't last very long for a lot reasons but the main one being that dirt is everywhere. It's not scarce. But metals are scarce, easy to carry around and don't deteriorate over time. The main metals used were gold and silver which are still widely believe to be the "correct" ASV today. Note I put quatations around correct because there isn't a correct ASV. ASV isn't real. It was made up by society to fulfill a role because we can no longer trust each post-sin.

  This lead to metal money. While grain was the first commodity money, metal money was the most widely used at it's peak and was used for the longest period of time. Metals as commodity money had the longest run of any Supply as a widely accepted ASV. The most widely used metals were gold and silver. Gold has an edge over silver for two reasons. Firsly gold is rarer and secondly gold does not react with air. Over time silver changes but gold does not. The acceptance for commodity money spanned empires, nations, land and sea. For a couple thousand years you could take gold and silver anywhere and it would accepted as an ASV. But the acceptance in ideology was not universal which lead to some interesting moments in history.

  The first major example of gold not being accepted as an actual ASV was Mansa Musa's story. As the king of Mali he was extremely rich and had lots of gold. When he went to Cairo he brought the large amounts of gold with him. He spent and gave away so much gold that the SV of gold in cairo eroded to an extreme degree. To Mansa gold had no value; the SV of gold was nill for Mansa. However, in Cairo, the belief was the opposite; they loved gold. And so Mansa traded gold for lots of various Supply. This caused inflation in cairo and helped cement Mansa in history. Did Mansa have the correct view on gold? Was the actual of gold nill like his SV on it? Or was Cairo correct and gold was extremely valuable?

  The second major example is about native americans and the colonizers in the new world. In the genisis of this colonial expansion people who migrated from Europe to America were in search of silver and gold. Now the native americans had silver and gold but didn't have certain Supply that Europe had simply because Europe was more technologically advanced. Native americans had silver and gold which they didn't care about and Europe had Supply like beads which they didn't care about. So what did they do with each other? Well mainly they killed each other. But there was some trading that took place. Europeans traded beads and other Supply to native americans in exchange for silver and gold. Native americans did not hold the belief that silver and gold was an ASV but the europeans did. Because of this a trade took place and both viewed themselves as better off. SV held by both parties rose in thier own minds. 

  But overall silver and gold are two most commonly used and believed in ASVs. This believe is still very strong. So strong in fact that JFK wanted to eliminate the banking system at the time he was president and implement bimetallism in America. He wanted both gold and silver to be used not just gold. Later he was assissinated and the plan for bimetallism fell through. The rallying cry of bimetal commodity money however did not die. Some poeple today still want gold and silver to be the most widely used ASV. 

  Well great, we have a Supply that can almost perfectly fulfill the role of ASV and somewhat has a cult following. These two facts go hand in hand and lead silver and gold to be the most successful Supply ever used for ASV ever. They did so well that the reign of the two Supplies will probably never be topped. But there are still some problems. What are they?

  Well for one what is the unit here? On the most basic silver and gold standard everyone carries around lumps of the metals for their ASV. Is one lump the actual unit of measurement while another isn't? And even if we did choose a lump shape to determine as the correct lump how do we get everyone on board? The second problem is an issue of standardization. Before with grain you could always just pay with the bad grain. With gold and silver it's impossible to tell just by looking at it what the purity of it is. The final problem is a problem without a solution. Gold and Silver weighs quite a bit and is pretty bulky. It's incredibly annoying to carry around. 

  But we as Humans are always engineering solution and so we engineered a solution for these problems. Firstly we deal with the unit problem. Instead of trading lumps we now trade weights of lumps. A cow will traded for .5lbs of silver or a house for .25lbs of gold. This is why when you see trades in the _ye olden days_ take place they are weighing the gold and silver against something. Usually that something was a small effigy like figure made to so that the value of the Supply was represented in the weight. You want a Supply with a certain weight? Great! Give me the equivalent in gold and silver in weight. This is a great solution but one that is somewhat annoying.

  The second problem can't be solved in a decentralized way however. The problem of standardization in the ASV in regards to purity needs a central authority. The central authority has to make a rule about the purity and has to enforce it. So what do they do? They take all the lumps of gold and silver and melt them into coins. The coins will then have a standardized purity and on top of this offers a better solution to the unit problem. We now have coined commodity money. You're no longer required to weigh the gold and silver while trading. Here another problem pops up. Post-sin economics is always problem, half-solution, problem, half-solution on and on forever. Post-sin Humanity is rather annoying to deal with.  
  
  The problem that arises is called Gresham's Law and it states that good money drives out bad. When you do have coined money it becomes profitable to take notches off the coin. If you do this enough you can create a new coin. Have you just created money out of thin air? No, you simply devalued all other coins in favor of creating a new one. If you chip off 2% of every coin you have you can create a new coin out of 50 coins. You now have 50 coins at 98% SV and a new coin at 100% SV. This undermines the solution created for the last two problems of commodity money. It's like the last two solutions didn't even work and we still have the issue of weight and bulkiness to worry about. We are now back to the drawing board. 

  The solution to solve the Gresham's Law problem and the problem of weight and buliness. Is to store the metals in a vault somewhere and to carry around something that represents gold and silver. Humanity has just created representative commodity money.

  ### Representative Commodity Money
  So no longer are we carrying around gold and silver instead we carry around some Supply that says we own that gold or silver. When we trade we now trade that representative which the counter party can take the vault and exchange for gold or silver. We are starting to have a rather complex solution for a problem that didn't even exist pre-sin. Before we didn't even have ASV and now we have both ASV and some Supply that represents ownership of the ASV. We knew that the ASV itself never even had value it simply had a widely held belief of the Supply used as ASV having SV. Does the Supply used as a representative have value then? Not even close. We are even further from the truth of that elusive value, but the system created is easier to use and harder to abuse. And so it flurishes.

  At this point in history we are about at the 1700-1800s. The barter system lasted for quite a long time up until technology and the culture changed allowing for grain to take the role of ASV. Then metals came and gold and siler ruled the world for mellenia as _thee_ ASV. Representative money takes on a brief blip as a the next stage of money and lasts for about 100-200 years. 

  There isn't much to talk about in regards to representative commodity money. It was simply the next step to commodity money and offered a solution to the two problems. The only question to be talked about is what is the Supply used to represent the ASV? Well it's paper. People carried around paper which represented ownership of gold and silver. If you clipped the paper you wouldn't be able to make new gold or even new paper, and carrying around the paper wasn't annoying.

  So this is the perfect way for ASV to take form? No. No ASV will ever be perfect. ASV was created to greese the wheels post-sin. No matter how greased the wheels are the system will never be as good as it was pre-sin.

  ...And we have another problem. problem, half-solution, problem, half-solution. What's the problem? People can counterfeit the paper and then take ownership of gold that wasn't their's. This problem has no solution other than the central authority making the paper hard to counterfeit and being ever vigilient. On the individual Human side there is a partial solution. The partial solution comes with it's own problem which is quite evident. The solution is to just ignore this next step in money and to keep your gold and silver in your own hands. But in general there arn't too many problems. So why do we not currently use representative commodity money anymore?

  Well, widely in the world, we did use representative commodity money up until the 1970s. Specifically starting in 1971 with the Nixon Shock. The problem is that central authorities do not have control. Central banks, federal government, and multi-nation alliances crave power. They hate not being in control. In a perfect democracy, republic, or democratic-republic this would not be the case, but obviously we do not exist in that reality. Power is everything to these institutions and must be kept close which is why the next evolution of money is based solely around the central authority. Gold and silver did not make decisions and thus was "decentralized". For lack of a better word I am saying "decentralized" but essentially gold and silver are not apart of the central authority. Given a command from the central authority the gold and silver won't comply. It's inanimate and thus can't. Central authorities don't like that. They want money that can be controlled. So fiat money was made.

  ### Fiat Money
  Fiat money is the money the majority of use. The U.S. Dollar, Euro, Yuan, Ruble, etc are all Fiat Currencies. It is the money the modern world runs on. But what is fiat money?

  Fiat money is just what ever the state decides is money. Fiat literally means "Let it be done" in latin. The state is just assigning a Supply the role of ASV. Nothing more. If the state decided that sticks are the ASV then then the sticks would be fiat money. There isn't much more to it. In America the money is paper in the shape of a rectangle with metal circles for coins. In Canada the money is plastic in the shape of a rectange with metal coins too. The metal coins are usually not gold or silver but instead zinc or some other metal. Certainly not gold or silver as there are people who subjectively value gold and silver rather highly still and at this point in history TFP has advanced enough for gold and silver to have industrial uses. Gold and silver are both used in electronics to varying degrees.

  Why does this ideology for the ASV hold then? For well over two millenium the ideology of gold and silver being _thee_ ASV held. Why all of the sudden is the majority of the world using a Supply as ASV which quite obviously has no value? Well there are some benefits to fiat that don't exist with commodity money. Mainly the money supply is now flexible. Before when we were on the gold standard the money supply would only increase if more gold and silver were found. Now with Fiat Money the money supply can be increased or decreased depending on the wants of everyone in the economy*. 
  
  * Now in the real world no is asked the people's thoughts on changing the money supply. Central banks which are lead by unelected officials change the money supply usually without regard to everyone's standing. They will say they are doing the right thing but usually they are lying. 

  This allows the central authority (who ever that may be) to pull the levers of economics in favor of everyone in the nation. If the money supply needs to be increased then they can increase it. If the money supply needs to be decreased they can decrease it. 

  This does however change the ideological aspect of ASV. Before ASV was whatever people decided it was. Now there is a central authority which is saying a Supply is now ASV. This causes one more change. Now a Human's belief that a certain Supply can fill the role of ASV is now also tied to the belief, hope, or cohesion in the government. But it is important to note that just because someone loses faith in their government that doesn't mean they will lose faith in the Supply's ability to fulfill the role of ASV. On the other hand however, if people in a nation now believe that the government can no longer maintain the central authority role successfully then faith in the ASV will deteriorate also. Faith in the ASV is now tied directly to faith in government's ability to maintain the role of central authority. This is a small change but it has drastic affects in crucial moments of history.

  There is also a matter of scarcity to talk about. With commodity money the scarcity element caused the money supply to be relatively static. This add it's positives and negatives. With fiat money the state now control money supply. Scarcity can be usurped and the money supply can now be engineered. However this has a draw back. The money supply can be engineered to expand and to contract at extremes. The state can create the designates Supply to an extreme level to cause hyperinflation. With commodity money hyperinflation was never possible. Now, with fiat, the state can create a near infinite amount of the designated Supply making the Supply worthless when compared to other supplies, but still be used as the ASV because the central authority designates the Supply as so. Before in commodity money, for hyperinflation to occur the commodity had to be either easily created or easily found. Gold and Silver was not easily created. Even in today's world it is extremely expensive. Gold and Silver were also not easily found. It requires finding, mining, and refining the metal which requires time, effort, luck, and other resources (other Supplies). Sometimes finding, mining, and refining wasn't even profitable; TFP had to advance for it be profitable. Fiat doesn't have this problem. We print it. It's cost essentially nothing to print the piece of paper designated as ASV.

  ### EMoney
  The next evolution of money takes fiat and puts it online. Going from Fiat to EMoney will be the same change as going from Commodity to Representative Commodity but in this case we go online using electricity as our way of representing ownership. Instead of holding fiat we want to deal with a debit card, credit card, online certificate, etc. This runs into a problem of ownership the same way representative commodity money ran into its ownership problem. Here the solution is to store money at an institution and have them assign your online presence as having money. This way when you pay online using whatever online based payment method you want there is still confirmation of funds. In an attempt to improve ASV to be more easily usable we run into a couple of problems.

  The first problem is that confirmation of funds which was already briefly talked about. The solution for this problem is inherient in the problem itself. For the first time we didn't even add a half-solution. We added a half-solution that is built upon a problem framework. Nevertheless Humanity pushes forward. Confirmation of funds in the modern world is the resposibility of the institution providing proof of ownership. These institutions are regularly checked by the government in the form of audits. However this again is only a half solution. What happens if the government sweeps a problem under the rug? What happens if they change ownership of ASV online?

  The second problem is about whether or not both the ASV itself and ownership of ASV is truly represented in the online framework. What happens if the government, who runs the framework, decides to give someone $100 but solely online. In this case the $100 was not part of the real world in the first place but is now represented online. On top of this the accredited individual has the ability to take out the $100 and get fiat from a bank or ATM. The problem being this was never his Supply to begin with. He gains ownership of a real world Supply based on an electronic ownership that was simply created. Another questions is what happens if no one has faith in the online existance but believes in the real world? In these ways we can see ASV in the real world and ASV online are two seperate existances with seperate ideologies of ability to fulfill the role of ASV. This is very important and we will touch on this later. 

  There is also a problem of money supply creation. In commodity money gold and silver (or whatever commodity is ASV) had to be found, mined, and refined to for the money supply to increase. In fiat for the money supply to increase the physical Supply had to be created. Again in fiat this was extremely cheap and could lead to hyperinflation. But in EMoney money creation takes literally no physical Supply or time. EMoney creation is as easy as updating a variable in a computer. To see how easy this is you could create a simple js script like the one below.

  MoneySupply = 1000;
  Console.log(MoneySupply);   // Will print the money supply which is 1000
  MoneySupply = MoneySupply + 100000000000;
  Console.log(MoneySupply);   // Will print the money supply which is 100000001000

  It is literaly this easy to change the money supply in EMoney. Anyone who doubts this should watch interviews of the fed chairs during the Covid-19 times. They will very clearly state that money supply creation is brain dead simple and there is no limit to their ability to do so.

  Nevertheless Humanity persists and now we have fiat in the form of EMoney.

  ### Crypto
  Crypto seems to be the final solution for ASV. This is a form of ASV where every attribute of money is now decided by code. And with code there is never a case of code going angainst what it was programmed to do. Before in Fiat and EMoney there were issues with the government not doing both what they said they would do or even what they should do. Code does not have free will and thus will be deterministic. Governments and institutions were not beholdant to what they say or what they should do. Code is. If code says it will create a Supply in a certain way then it will. This is a REALLY big calling card for crypto. Code is deterministic and can be programmed. Attributes like money supply and ownership certification are programed. No longer are you required to be beholdant to the government.

  As with all other forms of ASV Humanity still has a problem of ideology. If no one believes the specific supply can fulfill the role of ASV then the supply will lose the role of ASV. Fiat was able to usurp this by tying ideology to the state. Crypo is decentralized (usually) and thus can not tie the ideological role of ASV to the ideological role of government. Again, this is usually a calling card for crypto and is seen as a positive. Objectively this is a positive and a negative, but because the government leans to abusing power at any opportunity it is mostly a positive.

  Bitcoins was perfectly designed to fill the role of ASV.

  ### Money In General
  With the creation of crypto money seems to have evolved to its final state. The evolution went barter (no money) -> commodity -> representative commodity -> fiat -> EMoney -> Crypto. 

  Money exists in the model as ASV and there are three actions you can take with ASV.

  1. TODO
  2. TODO
  3. TODO

  The creation of ASV and assigning of a Supply to fill that role allows for more S&D Connections in any momemnt in time along with a more efficient ownership of Supply change. The creation of ASV also does one more thing. Debt in the model is now slightly changed.

## Debt With Money
  Earlier, when money did not exist, debt was a contract between a demanding and supplying party about a specific Supply the Supplying party had.
  
  Now we have to split between Supply specific debt and Money based debt. Literally all debt created today is Money based debt. The only time you will encounter Supply specific debt is on minute and irrelavent instances. Like for example you borrow a pen from you friend and give it back two seconds later (no interest debt). Or you borrow a ladder from you neighbor and hand them a dozen eggs as thanks (12 eggs as interest). All financial debt today is Money based debt. This is great and awful.

  Supply specific debt pulls Supply specific S&D Connections forward in time.
  Money based debt pulls abstract demand forward in time.

  * Before when debt was loans on Supply there was no possibility of "forging" ASV. Now that loans are ASV, debt creates shadow ASV (credit) which is, again, a positive and a negative.

## Institutions (Systems)
  Pre-sin there was no need for institutions. Demand successfully filtering Demand at every occurance of a conflict was FANTASTIC. Post-sin three things need to happen.
  1. Demand needs filtering
  2. Temporality of Demand needs to be manipulated (technically it doesn't have to but like...)
  3. Ownership of Supply needs to be decided
  Institutions are thus created to fill these roles. All Institutions exist on a pyramid where the points are purely Economic, purely Financial, and purely Sociological.

  1. Economic and Sociological Institutions filter Demand in the current moment.
  2. Economic and Financial Institutions can manipulate Demand through its temporal property by using debt.
  3. Sociological and Financial Institutions decide Supply ownership through powers granted by the people whether begrudgingly or happily.

  All real world Institutions exist somwhere in this classification pyramid (look at the soil pyramid for example). In the real world Sociological (government) institutions are tried to be kept purely Sociological but obviously this doesn't fully happen, and even if it did. It would be a bad idea to do so. Even in the real world governmental institutions act as economic and financial institutions. Public debt is a prime example of this. 
  
  A true sociological institution would never even touch debt. Only economic and financial instutions do. So if any government touches debt well they are now automatically a certain percent economic and/or certain percent financial.

  A true economic and financial institution would never deny demand if the exchange is profitable. If a business denies service based on religous, personal, or societal reasons then the institution is now automatically a certain percent sociological. This is the same for banks denying credit or freezing accounts.

  * Financial Institutions make the Value trade. They create debt => they pull demand forward in time => they trade Value in the present for percieved Value in the future. They problem is that any Value spent on the Financial Institutions is wasted Value. 
  * It doesn't matter that a loan to create a HFT algorithm was successfully paid off by the HFT's profit. Any Value spent creating the HFT is wasted Value.
  * Systems make up Systems which make up Systems which make up Systems...


//Markets are a type of institution. Before they were purely economic/financial. Now they are under the control of government.


### Financial Institutions
  The evolution of financial institutions needs to be talked about. Financial institutions are instutions that deal solely with Money and Debt. They don't care about other's Supply or their own. They solely want to manage Money and Debt in an attempt to gain SV whether that be ASV or Supply. These are institutions that don't care about Value. They play the Money game and only care about SV.



  The very first financial institution is an individual Human. When two Humans create debt they are acting as financial institutions. 

  Evolution of financial institutions went Human -> 





  




