Note: This readme is specific to this project. (This is a Node project.) 
Instructions to run:
- Open terminal, type "node server.js"
- Can also use "start node server.js" (that'll open a CMD prompt)
- Test@Render: https://nodequotes.onrender.com/quotes?topic=motivational&count=3

## Purpose
This repository is for creating a server in Node. Front end will use Fetch. This is an educational project aimed at student learning. 

## Language and Technology Constraints

- **Languages**: JavaScript, HTML, and CSS
- **NOT** allowed:
  - React
  - Vue.js
  - Angular

## Code Style Guidelines
When writing or suggesting code for this repository:

- **Always** use `if/else` logic.  
  - **Avoid** ternary (`condition ? true : false`) expressions.
- **Always** declare variables with `let` unless `const` is clearly required.  
  - **Avoid** using `var`.
- **Use old-style string concatenation** with `+` operator.  
  - **Avoid** using template literals (backticks `` ` ``).
    - Example: `"Hello, " + name + "!"` instead of `` `Hello, ${name}!` ``

## Additional Notes
- Code should prioritize **clarity** and **readability** over efficiency or conciseness.
- Comments are encouraged, especially to explain steps in JavaScript files.
- Every named function and loose code block should have at least a **short comment** explaining its purpose.
- **When writing callbacks**, use **arrow functions** instead of anonymous `function()` syntax unless **this** syntax is used within the callback function.
- **Avoid** using `switch` statements. Use `if/else` logic consistently.
