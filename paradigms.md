# Programming paradigms

## Imperative

- A broad paradigm where you write code that explicitly describes **how** to perform tasks.
- It focuses on changing program state through statements like assignments, loops, and conditionals.

### Procedural programming

- A specific subset of imperative programming based on the concept of **procedure calls** (routines or subroutines).
- It organizes code into modular blocks that perform specific tasks, emphasizing a linear, step-by-step flow of execution.
- Focuses on the manipulation of variables and the sequence of commands to achieve a desired state.

### Object-oriented programming (OOP)

- A specific subset of imperative programming that organizes code around **objects**, which are instances of classes.
- Data and behavior are bundled together into objects, and the program's structure revolves around the interaction of these objects through message passing.
- It emphasizes principles like encapsulation, inheritance, and polymorphism to create modular, reusable code.

---

## Declarative

- A broad paradigm where you specify **what** the program should accomplish rather than how to do it (abstraction of control flow).
- The focus is on the desired results, with the underlying system handling the execution details.
- Avoids state changes; results are determined solely by the inputs, ensuring consistency and predictability (immutability).
- Relies on expressions and declarations rather than explicit commands or steps.

### Functional programming

- A specific subset of declarative programming.
- It emphasizes writing programs using **pure functions** (no side effects), avoiding mutable state, and relying on expressions instead of statements.
- It focuses on what transformations to apply to data, often using higher-order functions and recursion.
- Uses recursive function calls instead of traditional looping constructs to perform repetitive tasks.

### Logic programming

- A specific subset of declarative programming based on **formal logic** and mathematical relations.
- Programs consist of a collection of **facts and rules** that describe relationships between objects, rather than a sequence of instructions.
- The execution is handled by an **inference engine** or "solver" that navigates the rules to find solutions or verify truths, essentially "reasoning" through the data to reach a conclusion.
