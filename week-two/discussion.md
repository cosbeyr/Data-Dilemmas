## I) Usable Security

**GB: How should an organization determine goals?**

- Complex organizations have many goals but it boils down to data and the value placed on data
- Goals should be based on the users as well as the current or potential for data
- What communities or individuals are using their product or service?
- What are the goals of the users and are they parallel to the goals of the organization?


* e.g. Zoom: many different types of users (colleges, businesses) and even from these broad categories of users we can break them down further based on socioeconomical and cultural factors
* The data may consist of how the users are using Zoom so different users have different goals
* A goal for Zoom is the ensure that every cluster of users is successful in their individual goals


**RC: From these goals how does an organization determine potential security risks?**

- 1) They need to assign value to the data associated with their product/service
- Could a part of their greater data be taken advantage of?
- Yee's design guidelines talk a lot about "authority" and who has right to data at what times
- Assigning levels of value to this data can be step toward determining what aspects may need more security


* 2) They need to understand the procedure of each group of users 
* It's not enough for us to assume that each task associated with a product *must* be completed in the same way
* Humans do things there own way, even if they all end with the same result
* It's important that engineers and designers consider all the ways their product could be used even if it doesn't match the initial, singular goals of the organization


**SA: Whose responsibility is it that user's data is secure and that they are acting in a secure way? Organization employees? Users?**

- I don't think that we, as technologists, have any right to put blame on users
- We can't make assumptions about the data or tech literacy of the people using our products
- Instead, I think we need flexible designs that can provide additional, digestible information to those that need it 
- Email encryption is a great example of this and is brought up in the Usable Security article
    - I have one experience trying to encrypt an email from school for a government internship without much of an understanding of what it meant in the bigger scale
    - It was incredibly complicated and the email client I was using didn't supply any information
    - Which I think is not an uncommon experience and is one that we should try to remedy 


* Two big parties stand out to me as responsible: the organization, which can be broken down as well as regulatory agents
* I think the security of users should be a goal of an organization and they should set out to design flexible products that encourage users of all different types to consider the data associated with them as users of the product
* An organization should make the security risks clear to their user which will motivate them to follow security measures
* e.g. Facebook -- how much data is associated with each user? They don't make it clear in all cases
* Regulators are another big factor that have a responsibility to put pressure on organizations to care about security
* Both of these parties should have the user's best interests in mind, I'm not sure that's always the case



**RC: How can an organization support secure user action?**

- Organizations need to reconsider themselves as the ones to introduce their users to the ideas of security
- Think this is the only way to bridge the gap between usability and security -- if we can motivate our users to be aware of and to care about the security of their data then the usability improves without any changes to the system itself
- As humans we don't really think about digital information about us in the same way that we think of physical property
- It's harder to put the same level of value on something that you can't see so it's important for these organizations to encourage secure user action


## II) Sociotechnical Systems

**GB: What elements of software engineering could designers draw from?**

- I think we shouldn't draw from software development rather we should incorporate more voices, it's a challenging approach but can help us reframe the problems we find 
- What the DesignX article points out to me when it dicusses implementation and a designer's role is that we need to be reframing the problem away from traditional engineering
- They point to compromise which I think is often overlooked 


**RC: How do we introduce incrementalism when the technology is constantly changing? When business processes change so slowly?**

* I agree with the DesignX article's assertion that rebuilding a system from scratch is not the answer and will most likely introduce more problems
* The landscape of tech is changing incredibly rapidly which makes incrementalism a problem

- I think one answer is that organizations need to constantly monitor how they product is being used
- Are the ways it is being used changing? Are the types of users changing? How are people failing to use this product?
- And then when they can answer these questions making the little changes to fix the issues they discover for a single group of users
- This is instead of a one size fits all model and definitely requires a flexible product that can be changed in this way

* But at the same time this can lead to decreased usability 
* e.g. LinkedIn for a while changed their interface every few months and as a user I always got lost
* Making it a less usable product
* So for incrementalism to work it needs to be made known to users 


**SA: How do we train engineers to be thinking in terms of "satisficing"?**

* e.g. randomness in algorithm design is not the most efficient but is good enough
* More lectures on this idea, explaining to students the flaws in their design so that they can understand that there is no such thing as optimal in the real world
* We need engineers to be thinking how the product will be used and that it will be used by many different people
* You can't build a system that works perfectly for everyone but it's still important to include all of those perspectives in your design


**GB: How do we know when we've reached something that's "good enough"?**

- I think this requires an engineer to map out all the pros and cons of the solution they've come to
- From the first reading it's clear that usability and security are at opposite ends of a spectrum
- When considering these factors, the engineer needs to see the ways the product fails from a usability perspective and from a security perspective
- I think modularity, as mentioned in DesignX comes in handy -- pros and cons for one piece of the bigger picture

## III) Actor-Network

**RC: What/who are the actors in terms of usable security?**

- Social, political and economic factors are all actors


**GB: What are the "actions" that these actors take?**

- Both the users and designers are influenced (e.g. being acted on) by these social, political and economic factors


**SA: What is the purpose/intent of thinking of usable security in terms of AT?**

- The usable security article talks about the approaches to fixing a broken system
- And one is "reframing" and I think that we can utilize the ideas of AT to rethink the factors related to the usability and security of the product
- Bridge to more of a social science approach to technology because these technologies are being used by humans not other computers
- Designing software to be run by a robot is easier because they follow the rules we outline for them the bugs come from us as engineers (we tell the robot to do the wrong thing)
- Humans don't act in the way we expect them to and we might accidentally tell them to do the wrong thing on top of that which means we have more complexity
- We need to reframe these issues in terms of the humans using them and all of the complexities that come wiht them 

---

[Go Back](https://cosbeyr.github.io/Data-Dilemmas/)
