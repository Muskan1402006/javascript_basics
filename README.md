

📘 Day 1 – JavaScript Fundamentals: var, let, const and Hoisting

Today I started learning the basic and most important JavaScript keywords and a core concept called hoisting. These concepts are very important to understand how JavaScript handles variables internally.

🔑 Keywords Learned
var
Function scoped
Can be re-declared and updated
Hoisted and initialized with undefined
let
Block scoped
Cannot be re-declared in the same scope
Hoisted but not initialized
const
Block scoped
Cannot be re-declared or updated
Must be initialized at the time of declaration
🧠 Hoisting

Hoisting means JavaScript moves variable declarations to the top of their scope before execution.

Variables declared with var are hoisted and set to undefined
Variables declared with let and const are hoisted but remain in a Temporal Dead Zone (TDZ) until initialization
📝 What I Understood
The difference between function scope and block scope
Why let and const are safer than var
How JavaScript handles memory before executing code
What the Temporal Dead Zone means