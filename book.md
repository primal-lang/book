# Audience

- Beginners in programming (First-time coder).
  - My audience is people who have **never coded before**. I want to teach them functional programming as their _first_ paradigm so they don't pick up the 'bad habits' of imperative programming. The structure should be pedagogical, starting with the absolute basics of logic and data.
  - The Goal: Literacy
- Programmers that want to learn functional programming.
  - My audience is **junior-to-mid-level developers** who know the basics of programming (variables, loops, functions) in languages like Python or JavaScript but feel overwhelmed by FP concepts like Monads or Currying. The book should act as a bridge from Imperative to Functional thinking.
  - The Goal: Paradigm shift.

# Chapters

- Search for sections of books on functional programming
- Ideas for chapters. Ask AI
- Examples
  1.  **The Shift:** Moving from "How" (Imperative) to "What" (Declarative).
  2.  **The Atoms:** Pure functions and Side Effects.
  3.  **The Molecules:** Higher-order functions (Map, Filter, Reduce).
  4.  **The Structure:** Persistent/Immutable Data Structures.
  5.  **The Glue:** Function Composition and Pipelines.
  6.  **The Safety:** Types and Algebraic Data Types (ADTs).
  7.  **The Context:** Functors, Applicatives, and Monads (usually the "mid-point" of the book).
  8.  **The Real World:** Error handling without exceptions, and Concurrency.

# Constraints

- Should be written in Markdown
- Should be exported to ePub, PDF and other formats
- Should be easy to translate to other languages

Explain the different computation models: Turing machines, lambda calculus, and how they relate to programming languages.

Turing computing vs lambda calculus

What’s a programmer? What skills do they need?

Ask Jorge DSP material

Explain keywords: if,else,try,catch

Search for what is taught in other books

Have an advance section with:
Backtracking

Create book generator:
<title1>
Use flags: “show_solution”

Learning to program (or to code) makes you see life differently

If taking information from a book, reference it

Explain why using Primal and not other famous/useful programming language

Famous books on programming and functional programming

How to generate an epub and website at the same time

Promise a short explanation. Give a long one. That was the worst short explanation ever.

Give intro with Turing/Church models of computation

What is programming? That's a big question. I could write a book about it

Make constant jokes about how the reader spent money on a free book. "And you might say, well, and I spent all this money on a free book that doesn't teach anything new?"

Explain the meaning and origin of special words like: Recursion

I will save you from the joke that to understand recursion you first need to understand recursion. Because if you are reading this, you probably won't get it. Yet. But you will. And come back to this line and line laughing about the joke. The irony

https://journal.stuffwithstuff.com/2014/11/03/bringing-my-web-book-to-print-and-ebook/

Set expectations about the book. It’s an introductory book to programming. Not an advance book

Tips
For every concept explained, give a real life analogy or metaphor
Each chapter has:
An introductory paragraph that explains what’s about to come
A closing paragraph that summaries that has been explained

A small closing chapter that:
Make a small summary of everything learned. Pointing key principles
Give ideas on how to continue with the programming journey
Try other languages

lazy (i.e., call-by-need)

Functional programming doesn’t have destructive assignments.

Rephrase this taken from a paper:
“Functional programming is based on two central ideas: (1) computation takes place by evaluating applications of functions to arguments and (2) functions are first-class values. In particular, functions are higher-order (can be passed to or be returned by other functions). It is well-known that expressions in pure functional languages are referentially transparent so variables are immutable or persistent—they cannot hold different values at different times”

Types of execution

- Run the tree itself
- Compile to machine code
- Transpile to another high level language
- Compile to bytecode

---

Functional programming (FP) is a paradigm—a style of building programs. Unlike imperative programming (which tells the computer how to do something step-by-step), functional programming is declarative: you describe what you want, and let the system figure out the how.

In FP, functions are the primary building blocks. Everything revolves around them. These aren't just the "methods" or "procedures" you're used to—they're mathematical functions that take inputs and return outputs, with no side effects.

---

Functional programming (FP) is a paradigm—a style of building programs. Unlike imperative programming (which tells the computer how to do something step-by-step), functional programming is declarative: you describe what you want, and let the system figure out the how.

In FP, functions are the primary building blocks. Everything revolves around them. These aren't just the "methods" or "procedures" you're used to—they're mathematical functions that take inputs and return outputs, with no side effects.

---

First-Class and Higher-Order Functions
In FP, functions can:

Be assigned to variables

Be passed as arguments

Be returned from other functions

Yes, functions are data too.

Example:

Haskell
applyTwice f x = f (f x)
You can pass any function to applyTwice. Even ones you create on the fly.

---

Recursion (instead of loops)
There are no for or while loops in Haskell. Instead, repetition is handled via recursion: a function calling itself.

---

Declarative over Imperative
You say what you want done, not how to do it.

Imperative (C-style):

for (int i = 0; i < 10; i++) { sum += i; }
Functional (Haskell):

Haskell
sum [0..9]
Much cleaner, right?
