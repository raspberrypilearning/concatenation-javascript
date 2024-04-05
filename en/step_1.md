You can combine text (string) and variables in JavaScript to create user friendly messages.

A "string" is a data type in JavaScript and other programming languages. Data types are groups of data tell the program how we want to use data.

You can format strings using template literals or concatenation. 

Here are examples of how they work:
+ Use backticks ``` ` ``` to embed variables within `${}` inside the string. This is called a template literal.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---
    
   const name = "Spider-Man";
   const age = 25;
   // Example using template literals
   const message = `Hello, ${name}! You are ${age} years old.`;
   console.log(message);
    
--- /code ---

+ Concatenation: you can combine strings together using the `+` operator.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---
    
   const superhero = "Iron Man";
   const power = "suit of armor";
   // Example using concatenation
   const description = "The superhero " + superhero + " possesses a " + power + ".";
   console.log(description);
    
--- /code ---
