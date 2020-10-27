In the Houndify Developer Guide, the section on Writing Expressions could be improved by defining the actual grammar used for evaluating expressions that Houndify can recognize.

From the current documentation, relying on "these expressions can contain a simple string, or a sequence of words with weights and operators. If the expresion contains at least one double-quote character, it is taken as an expression. Otherwise, it is taken as an exact string to match ... can be expanded upon.

Further, the section on adding weights could be improved to first introduced the "what" and "why" of adding weights to an expression. Is it for Maximum Likelihood Estimation of a word based on an n-gram language model?

Or does it imply a Hidden markov Model, given:
- a set of n states
- a transition probability matrix where each element represents the probability of moving from one state to another
- a sequence of observations, drawn from a vocabulary
- sequence of observation likelihoods, each expressing the probability of an observation being generated from a particular state
- An initial probability distribution over states, determining the probability of a Markov chain starting in a particular state?

Perhaps, is there a way to teach this?
Is there a guide that can further explain the principles behind this? Currently the document is a little confusing


For the Writing Expressions section, we could also allow the developer to write a list of several phrases with variations, etc which can be tested against the grammar, and then provide feedback to improve it. 
It is not quite obvious how to assign weights to certain words and developers may find it beneficial if more tooling was provided around that.


2. Incorporate a Search feature, to make it easier to reference specific sections of the document without having to scroll through all sections, and sometimes, take a guess on which section the information you're looking for might be located

3. The user-experience is sometimes lacking especially when it comes to the related tutorials that are incorporated into the documentation. Often, these related tutorials are hosted on Medium with cross-references back to specific sections of the documentation. This constant back and forth between medium and the developer documentation can become frustrating sometimes

4. Because the developer documentation requires authentication, whereas the tutorials and guides are publicly available on Medium, developers need to make sure that they are always signed in to Houndify in order to access the documentation. Developers that are not signed in to Houndify will be unable to reference any specific portions of the documentation referenced on Medium


6. Debugging applications
A part of writing voice ai applications is the User Experience, and as such, the tools for Debugging should allow developers to be able to not only test the validity of their queries and the response from the Houndify server, but also other aspects such as:
- how well the user is able to accomplish their goals
- estimating the pace of interaction with the system
- how slow was the system to reply
- number of corrections needed to get the correct response
- number of user time outs
- number of speech recognition errors or rejections

Incorporating Frameworks such as the 
[PARADISE framework for evaluating Spoken Dialogue Agents](https://arxiv.org/pdf/cmp-lg/9704004.pdf)

