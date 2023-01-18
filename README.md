# springboard-10.2-let-and-const-quiz

ES5 Global Constants
var PI = 3.14;
PI = 42; // stop me from doing this!


ES2015 Global Constants:
const PI = 3.14;

Quiz Questions

What is the difference between var and let? Scoping -- var is scoped at the function level whereas let is scoped only to the block in which it is declared. Therefore, let will only have values that were defined and retained in that block. Let variables declared in multiple scopes witht the same name will act like separate variables.

What is the difference between var and const? The same as above -- scoping -- plus the fact that const variables cannot have their type or value reassigned.

What is the difference between let and const? While these two have the same scope (block level), const variables cannot have their type or value reassigned.

What is hoisting? Hoisting occurs with var -- declaration occurs and is alloted memory before initialization. So the variables, by name, exist at the very beginning and will have a value of undefined until initialized. Therefore they can be referred to even before they are given a value or used in any way, without causing an error.
