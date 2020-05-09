# Why Johnny Can't Encrypt: A Usability Evaluation of PGP 5.0

- "effective security requires a different usability standard, and that it will
  not be achieved through the user interface design techniques appropriate to
other types of consumer software" (1)
- "PGP 5.0 is not usable enough to provide effective security for most computer
  users, despite its attractive graphical user interface" (1)


"configuration errors are the probable cause of more than 90% of all computer
security failures ... inescapably a user interface design problem" (1)

### Defining usability for security
**usability** - security that can be used effectively
- users are reliably made aware of the security tasks they need to perform
- users are able to figure out how to successfully perform those tasks
- users don't make dangerous errors THAT'S A BIG WHAT IF
- users are comfortable with the interface


### Problematic properties of security
1. unmotivated user: security is not a primary goal
- "should not assume that users will be motivated to read manuals or to go
  looking for security controls that are designed to be unobtrusive" REMINDS ME
OF THE LAST ARTICLE WE READ

2. abstraction: security policies == abstract rules for deciding whether to
grant accesses or resources; is not understood by general public

3. lack of feedback: "attempts to summarize [the state of security
configuration] are not adequate" (3)
- dependent on what user wants to do

4. barn door: "user interface design for security needs to place a very high
priority on making sure users understand their security well enough to keep from
making potentially high-cost mistakes" (3)

5. weakest link: "users need to be guided to attend to all aspects of their
security, not left to proceed through random exploration as they might with a
word processor or a spreadsheet"

### Cognitive walkthrough
- more helpful: "an extension of the metaphor to distinguish between public keys
  for encryption and decryption if it is not visually clarified in some way" 
- "the lack of forward compatibility ... can be a problem: if a file is
  encrypted for several recipients ... the recipients who have RSA keys will not
be able to decrypt unless they have upgraded to PGP 5.0" (5)
- "information about the meaning of the blue and brass key icons is difficult to
  find, requiring users either to go looking through the ... manual, or to
figure it out based on the presence of other key type data" (5)
- "There is nothing to prevent users from innocently assigning their own
  interpretations to those [validity] ratings and setting them accordingly
(especially since 'validity' and 'trust' have different colloquial meanings)"
(7)
- "attempts to delete a private key should be met with a warning about the
  possible consequences" (8)

#### Too much information
- "PGPKeys ... presents the user with far too much information to make sense of,
  and that it needs to do a better job of distinguishing between basic,
intermediate, and advanced levels of key management activity so as not to
overwhelm the users" (9)
- THE DESIGNERS NEED TO CONSIDER THAT EACH USER WILL BE AT A DIFFERENT LEVEL OF
  UNDERSTANDING WITH DIFFERENT PRIMARY GOALS

### User test
- Hillary Clinton -  convenience, lack of understanding
- "thinking it referred to some area specifically demarcated for the purpose
  that she was unable to find" (12)
- "gave up on using the key server after one failed attempt" (12)
- not a lot of motivation behind this clumsy procedure


### Conclusions
- would have been neat to see them attempt the same thing with the suggestions
  they had made above to see if they would actually help
- or is the problem more ingrained? 
- is encryption to geared towards cyber security specialists?
- difference between knowing what you need to know and know how to do it

### Usability evaluation for security
- "Standard usability evaluation methods, simplistically applied, may treat
  security functions as if they were primary rather than secondary goals for the
user" (14)
- "likely to need similar adaptation to the priorities appropriate for security"
  WHY ARE "PERSONAL COMPUTER USERS" AND "CORPORATE OR MILITARY USERS" USING THE
SAME TOOL? 

### Towards better design strategies
- "a need to communicate an accurate conceptual model of the security to the
  user as quickly as possible ... pragmatic ways of pairing down security
functionality to that which is truly necessary and appropriate to the needs of a
given demographic" (14)
