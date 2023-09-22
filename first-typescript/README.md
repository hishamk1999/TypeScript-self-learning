# What is TypeScript?

TypeScript is a programming language developed by Microsoft that is a superset of
JavaScript. This means that all valid JavaScript code is valid TypeScript code. However,
this doesn't mean valid JS code won't cause warnings in our IDE if written in TypeScript
which is actually the main benefit of TypeScript: it can highlight unexpected behavior in
our code and warn us about it before we ever even run our program.

This is primarily accomplished with static typing in TypeScript, which is the idea that a
variable will always have the same type over its lifetime. Static Typing is a new concept
for us - it lies in opposition to JavaScript's dynamic typing: where a variable can have
data of any type assigned to it at any time. TypeScript accomplishes this by inferring
types and allowing defined types - where you explicitly declare the type a variable will be

- even as far as describing the specific keys and data types of values on an object.

  Because our browsers and Node (yes, we can write Node apps with TypeScript!) cannot
  run TypeScript code natively, the TypeScript has to be transpiled into JavaScript. If you're
  familiar with compilation, this is very similar to that process; however, instead of
  translating from an abstracted language to a lower-level language, transpilation is
  taking code written in one programming language and translating it into another
  language with a similar level of abstraction.

> [!NOTE]
> While this technical distinction is cute, no reasonable person will be mad at you for saying TypeScript is compiled into JavaScript. We'll soon be installing the `typescript` package from npm, which comes with a command line app called tsc, aka the TypeScript Compiler - even Microsoft hand waves this detail. We will be doing the same.

## Why TypeScript?

To answer this question, we need to dive into the original intent of JavaScript as it was developed. You'll recall from the beginning of the course when we talked about Brendan Eich developing JavaScript in just ten days to give a web developer the ability to add behavior to a webpage.

Since then, JavaScript has grown far beyond its original stope and purpose. As we've
learned, it's common for entire web, mobile, desktop, and server applications to be
orchestrated with JavaScript today. Many additions have been made to the language to
ease the development of large apps, but one essential component to successfully
working with a team over time has been left out a type system.

Developers also love working with TypeScript; in the 2022 Stack Overflow Developer
Survey, devs indicated that TypeScript is their fourth most loved language, beating out
JavaScript at 16th.

TypeScript is also the third fastest-growing language on GitHub from 2021 to 2022 and
the 4th most prominent language overall.
