# Lambda calculus

## Binding

Binding refers to the association of a variable with a function's parameter. A variable that is defined locally within that function is called a "bound variable". Variables that are external to the function are called "free variables".

Example:
Given the function (λx.x + y), the variable x is bound and the variable y is free

## Application

Application is the process of applying a function to an argument.

Example:
Given the function (λx.x + 1) and the argument 2, the application is (λx.x + 1)2

## Substitution

Substitution is the outcome of function application, where the argument replaces the bound variable within the function's body.

Example:
Given the function (λx.x + 1) and the argument 2, substitution involves replacing the bound variable x with 2 in the body of the function, resulting in (2 + 1)

## Beta reduction

Beta Reduction is the process that includes application and substitution.

Example:
Given the function (λx.x + 1) and the argument 2, it performs the application and then the substitution, resulting in (2 + 1)

## Evaluation

Evaluation is the process of reducing an expression to its simplest or most computed form.

Example:
Given the function (λx.x + 1) and the argument 2, after performing beta reduction, it evaluates to 3
