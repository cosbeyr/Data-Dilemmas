# A Brief Introduction to Usable Security
- historical look at papers that address user authentification and email encryption
- study security systems to determine how important design is
- debate exists over the role of interface changes versus more structural solutions in providing usable security
---

### Case Studies
#### Passwords and Authentification
- usability (easily memorable, reuse) vs. security (longer, diverse)
- people have more accounts and more computer power (for cracking passwords)
- guidelines: 8+ characters, random, upper-/lower-case, digits, ...
    - improve security but reduce usability
- usability approach goal: validate that they access only resources they have permissions to use
    - passwords, passphrases, PINs, graphical authentificaion, biometrics, secure tokens


**passphrases** - Sigmund Porter (1982); use sequences of words to authenticate users; more usable == more memorable, more secure == longer, more key space

**pass-algorithms** - James Haskett (1984); password would change for each login but pass-algorithm would remain (e.g. type next letter for each in given prompt)

**password advice** - Ben and Marthalee Barton (1984); provided different ways to aid in password selection; ways to convert a sentence or expression to a strong password

**cognitive passwords** - give the user a series of questions that are easier for them to answer than for others; not for high-security == people close to the user can guess

**passfaces/graphical** - (2000); three variants; more usable but each with security problems
- *graphical password* - Ian Jermyn; pencil-style drawing password
- *passfaces* - Sacha Brostoff and Angela Sasses; user selects an image of a person's face known to them from a grid of nine faces, repeats four times with different faces
- *deja vu* - similar to passfaces but with various images rather than just faces

**passpoints** - Susan Wiedenbeck (2005); using images as passwords; users select regions (varying tolerance) within single image to create a password; smaller tolerance == better security but lesser usability


#### Email Encryption
- email == not a secure medium
- email encryption == not widely used

**privacy-enhanced mail (PEM)** - Internet Architecture Board (IAB) (1985); problem: lacked flexibility; problem: required all entities worldwide to trust a single certificate authority (CA) infrastructure == organizational usability issues

**pretty good privacy (PGP)** - Phil Zimmermann (1991); employs a decentralized trust model; "web of trust" == participant can validate the other participants' trust; usability == mimics human interaction; problem: doesn't scale well; available as a plug-in

**secure multipurpose internet mail extensions (S/MIME)** - set of protocols for securely sending messages encoded using the MIME format; security comes form Public Key Cryptography Standard (PKCS) and an RSA Data Security standard; trust model == middle ground between PEM and PGP (any CA can be used)


**Encryption usability studies**

- Alma Witten and Doug Tygar (1999) "Why Johnny Can't Encrypt"
- verified usability problems inherent in security interfaces
- results: revealed difficulties users face with PGP
    - test participants emailed secrets without encryption (irreversible, serious)
    - participants chose passphrases that were similar to standard passwords (decreased key space)
    - only a third of participants could correctly sign and encrypt a message within 90 minutes
- conclusion: *generic* usability standards aren't applicable to security applications

* Simpson Garfinkel and Robert Miller (2005) 
* repeated study on S/MIME with key continuity management (KCM)
* *KCM* - automatically creates a public-private key pair whenever a user creates a new email identity 
* results: effective at stopping impersonation attacks
     * not useful against new identity (phishing) attacks
* conclusion: improvement but not perfect; highlighted continuing problems 

---

### Usable Security Design
#### Design Guidelines
* Kai-Ping Yee (2001); addresses valid and nontrivial concerns specific to usable security design
* no set rules, principles or formalisms that are guaranteed to produce usable computer systems
* ARE THESE TOO GENERAL? IS IT EVEN POSSIBLE TO LAY OUT GUIDELINES? 

- *Path of least resistance.* Match the most comfortable way to do tasks with the least granting of authority.
- *Active authorization.* Grant authority to others in accordance with user actions indicating consent.
- *Revocability.* Offer the user ways to reduce others’ authority to access the user’s resources.
- *Visibility.* Maintain accurate awareness of others’ authority as relevant to user decisions.
- *Self-awareness.* Maintain accurate awareness of the user’s own authority to access resources.
- *Trusted path.* Protect the user’s channels to agents that manipulate authority on the user’s behalf.
- *Expressiveness.* Enable the user to express safe security policies in terms that fit the user’s task.
- *Relevant boundaries.* Draw distinctions among objects and actions along boundaries relevant to the task.
- *Identifiability.* Present objects and actions using distinguishable, truthful appearances.
- *Foresight.* Indicate clearly the consequences of decisions that the user is expected to make.


#### Successful Designs
- based on user acceptance; designs viewed favorably in user testing and showed improvement in users' ability to achieve appropriate security levels

**Salmon file permissions interface**
- new user interface
- anchor-based subgoaling (ABS) - ensures user interface provides all information user will need to complete the tasks for which the interface is intended
- relevant information is readily available; relevant access control is in a single user interface
- "Salmon is clearly a successful example of how simply changing an interface's design can result in better user security"

**Network-in-a-Box**
- new system architecture with modifications to existing protocols
- "reframes the problem away from setting keys and acquiring certificates and toward the more fundamental task of getting on a wireless network"
- gesture-based user interface 


#### Flawed Designs
- user's ability to perform tasks securely; designs that did not promote sound security decisions

**Kazaa**
- users need to refer to multiple locations to see externally visible files, not a shared interface
- automatically shares any selected folder's subfolders
- could be fixed through interface systems alone

**Eudora PGP Encryption Plug-in**
- users didn't understand the metaphors in public-key crytography
- design problems run deeper than the interface: reframing required
    - "We must step back and look at email itself as the task in question, rather than simply providing a better interface for key management"

---


- successful: made it easy for users to achieve their desired security goals
- flawed: made it difficult for users to operate securely
- conclusion: security problems can be approached in multiple ways
- conclusion: shift in thinking required
    - problem fundamentally scoped around security? improve interface 
    - others? broadening definition of the task to change the assumptions involved --> new design opportunities
    - I AGREE COMPLETELY WITH THIS NOTE ON ASSUMPTIONS, AS DESIGNERS WE ARE TYPICALLY TOO NARROWMINDED -- BROADENING LEADS TO BRINING MORE PEOPLE TO THE CONVERSATION
