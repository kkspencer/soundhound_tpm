# Proposals for Improving the Developer Experience through Documentation

## Houndify Developer Guide

### Custom Commands
In the Houndify Developer Guide, the section on Writing Expressions teaches how to incorporate custom commands by writing expressions that specify phrases which they want the Houndify Server to recognize.

From the perspective of a developer new to voice user interfaces, phrases such as:
> ... these expressions can contain a simple string, or a sequence of words with weights and operators. If the expresion contains at least one double-quote character, it is taken as an expression. Otherwise, it is taken as an exact string to match ...

does not reveal much in terms of the actual grammar that the Houndify server uses to validate an expression. This can be improved by formally defining the grammar that the Houndify server uses to validate an expression, as well as providing several examples of expressions. To improve on this, an expression validation tool can be built to help developers and product managers quickly develop and validate custom commands.

Further, the section on adding weights is unclear about the "what" and "why" of adding weights to an expression. It raises some ambiguities in the form of:
- do these weights imply a maximum likelihood estimation based on an n-gram language model? and are developers expected to know about statistical or neural language models?
- do these weights imply a Hidden Markov Model with a given set of states, a transition probability, a sequence of observation likelihoods, etc?

I believe documentation clarifying the use of weights in expressions, as well as the principles behind them will be beneficial to developers using the Houndify platform.

### Search Engine
Currently, the developer documentation does not have a search tool, making it difficult to find or reference important information. Without a search tool, developers have to scroll through all sections of the documentation and sometimes guess the section in which the information they are looking for might be located. Having to repeat this several times a day over the span of a project which may take weeks or months can quickly become tedious and inefficient. Thus, adding a search tool will have a strong positive impact for developers using the Houndify platform.

### User Experience Improvement
Currently, the developer documentation is split between an embedded documentation on the Houndify platform (which requires authentication) and tutorials hosted on Medium. This introduces additional friction to the developer experience since a piece of information in the developer guide may be cross-referenced on Medium and vice-versa, forcing the developer to switch back and forth between the two platforms.

Further, developers that are not signed in to the Houndify platform are unable to reference any specific parts of the developer documentation referenced in the developer tutorials on Medium.

A solution may be to unify the developer documentation on a single platform so that developers spend less time switching from one platform to the other. This has the added benefit of providing a more coherent base to build on.

## Debugging applications built with Houndify
A key part of writing Voice AI applications is the user experience. For developers, this is usually weighted towards Debugging tools which allows them to quickly test the validity of queries and their associated responses from the Houndify server, but also verify other aspects such as:
- how well an end-user of the application is able to accomplish her goals
- estimating the pace of interaction between the AI agent and the end-user
- the speed with which the AI agent replies to the end-users queries
- the number of corrections needed to get the correct response from the AI agent
- the number of end-user time outs
- the number of speech recognition errors or rejections

By incorporating an evaluation framework such as the [PARADISE framework for evaluating Spoken Dialogue Agents](https://arxiv.org/pdf/cmp-lg/9704004.pdf), the Houndify platform can provide a superior developer experience when compared with its competitors.

