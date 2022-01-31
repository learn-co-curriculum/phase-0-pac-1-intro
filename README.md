# Introduction to Programming as Conversation

## Introduction

Welcome! In this module, we’re going to start learning how to program in
JavaScript.

It will be a long process and you will have moments of elation, excitement and,
sometimes, frustration. But we _promise_ you, learning to think in the
disciplined way that programming teaches will change your life for the better.

## Programming as Conversation

Our method for teaching programming starts from a different place than you might
expect. If you've ever looked at a programming tutorial or book you might be
expecting lectures on how to convert decimal numbers to binary numbers, data
types, variables, or something like that. We've designed our curriculum to _not_
do that.

![Confused by code being front-loaded](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/Image_50_SadHead.png)

We think there's a different, and better, way: we start instead by thinking
deeply about having _conversations_.

![Conversations are a natural model for thinking about programming](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/Image_51_HappyHead.png)

Many of the ideas we’ll share in this module ask you to reflect on "when you
learned to talk" or "when you’re talking with a friend." We call this
"programming as conversation" and it gets you to think about _communicating_
instead of "memorizing strange programmer words, facts, and symbols." You'll
learn those strange words and symbols eventually, of course, but you'll see them
as part of the act of communication, something you find natural right now.

## Programming is About Communication

![Turning Gears in Communication](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/Image_53_TwoHeads_Evaluation.png)

At its heart, programming is about communicating strategies for solving
problems. You:

* Document these strategies for yourself
* Communicate these documented strategies to others
* And then, lastly, ask a computer to run these strategies _very fast_

A "program" then is actually a strategy for solving a problem that people use to
communicate with one another _as well as_ give to a machine.

A recipe for a fancy dish is a good comparison: you **document** the ingredients
and preparation for yourself using human language. You can then **communicate**
that plan for food preparation by sharing the recipe with a friend.

## Programs are Written in Notation

![Notation Systems](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/Image_82_GraphicNotationSystems.png)

Even in recipes, we commonly use special _notation_ like `3g` for "3 grams" or
`½C.` for "½ Imperial Cup." In recipes, we usually use _notation_ to save time
so our wrists don't get tired. But with computers, we have to communicate using
notation. Human language is often vague and imprecise and computers are
_terrible_ about handling unclear directions. To help prevent communication
breakdowns, we converse with them using a special notation. The "special
notation" is the programming language's rules or "syntax."

> **DEFINITION** Notation: A specialized vocabulary or system of symbols for
> communication. **Examples** Musical notation, arithmetic symbols, chemistry
> symbols, traffic signs, or knitting patterns.

## Programming Defined

Let's propose a definition of programming:

> **DEFINITION** Programming: The act of creating programs, documents written in
> a notation system that can be understood by other humans _as well as_
> computers.

## Programming Language Defined

> **DEFINITION** Programming Language: A programming language defines the rules
> of notation ("syntax") that are required for it to ask the computer to do work
> on your behalf.

When programmers say "I prefer Ruby to JavaScript" they're saying "I like the
notation system that Ruby uses for expressing problems and their solutions."
It's a lot like why some people like to play one instrument over another. In
your heart you might _feel_ like a bassoonist, tuba player, or pianist —
but all those instruments play a Middle-C note at the same frequency.
Programming languages are similar: while their notation varies, they all ask the
chips inside the computer to do the same work at the end of the day.

As such, a lot of the "fashion parade" of "what's hot" in the technical scene is
just fashion. The really important thing to learn is: "What kind of problems or
solutions does this language make easier to express?"

## We Converse With Computers

One of the most essential ways of communicating, that we've all practiced
thousands of times, is a _conversation_.  "Conversation" comes from the Latin
words meaning "by taking turns." In conversation, we "take turns" _expressing_
ourselves.

A unit of "ideas" is an _expression_. When a listener hears an _expression_ they
interpret the words and symbols and sounds in the _expression_ into a _meaning_.
We call the work they're doing _evaluation_. The result of _evaluation_
for a human is "understanding." Computers show their understanding by returning
the result of that evaluation. That value is called a _return_ value.

Consider this diagram:

![Conversational Summary Graphic](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/Image_52_TwoHeadsConversingSummary.png)

In the next lessons, we're going to see how JavaScript acts as a "listener" in a
conversation. When given an _expression_, JavaScript will _evaluate_ it and,
like a good friend, give you a reaction about _how_ it evaluated your
expression. In the programming world, we call responses from the programming
language a _return value_.

***When expressions are evaluated, they return something***

Sometimes our expressions might not make sense to JavaScript, just like
sometimes our conversations with friends don't _quite_ make sense to them.

`Work, you stupid machine` is not part of the valid notation of JavaScript.
Below, we've embedded a tool that can read JavaScript. To see what happens when
JavaScript tries to interpret `Work, you stupid machine`, you can simply type it
into the console window below and press enter. Give it a try.

<iframe height="400px" width="100%" src="https://replit.com/@lizbur10/Sandbox?lite=1&outputonly=1" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

Here we've broken the rules of the notation system. This is known as a _syntax
error_. Computers require us to honor _their_ ***limited*** vocabulary. Syntax
errors are prompts from the programming language to help steer _our_
communication to be more precise.

When we follow the rules and adhere to the syntax, however, JavaScript will
return something to us. This time, try typing `1 + 1` into the console window.
(Don't forget to hit enter.) You should see the following:

![return value](https://curriculum-content.s3.amazonaws.com/phase-0/pac-1-intro/return-value.png)

JavaScript has _evaluated_ the _expression_ `1 + 1` and the result — the
expression's _return value_ — is returned on the next line.

Sometimes, we might get something unexpected. Type in `1 + "Cookie Monster"`
(including the quotes) and see what happens.

You'll learn more about _why_ this happened later. The important thing to know
now is that, as long as we follow JavaScript's syntax rules, we'll get
_something_ in return.

**Top Tip**: when you see an instruction to type something into the repl, we
suggest you do exactly that rather than copy/pasting. Actually typing in the
code helps your brain learn!

## Conclusion

Congratulations! You've finished your first lesson in thinking about programming
as a conversation. As you might guess, _expressions_ are important because
they're how we "push" ideas to computers and other programmers. We're going to
spend the remainder of this module learning to build expressions and
understanding how JavaScript will _evaluate_ them. Make sure you've integrated
the vocabulary words of "expression," "evaluation," and "return value" before
moving on.
