vaScript Programming Language
JavaScript (JS) is a versatile, high-level, interpreted language primarily used to make web pages interactive. It’s a key technology in web development, alongside HTML and CSS, and it runs in the browser as well as on the server with environments like Node.js.

Table of Contents
About JavaScript
Features of JavaScript
Getting Started
JavaScript Basics
Variables and Data Types
Functions
Control Flow
Example Code
Resources
About JavaScript
JavaScript was originally created in 1995 to bring interactivity to the web. Today, it’s used for a wide variety of applications, including web development, mobile development, and server-side programming. It’s a dynamically-typed language that supports object-oriented, imperative, and functional programming styles.

Features of JavaScript
Lightweight and Interpreted: JavaScript code is executed line by line, directly in the browser or in environments like Node.js.
Dynamic Typing: Variables are loosely typed, allowing flexibility but requiring caution.
Prototypal Inheritance: Objects can inherit properties and methods directly from other objects.
First-Class Functions: Functions in JavaScript are treated as objects, meaning they can be passed as arguments, returned from other functions, and assigned to variables.
Event-Driven and Asynchronous: JavaScript can handle asynchronous tasks, making it ideal for responsive applications.
Getting Started
To get started with JavaScript, all you need is a web browser (like Chrome, Firefox, or Safari) or a code editor with Node.js installed for server-side JavaScript.

Requirements
For Client-Side: Any modern web browser
For Server-Side: Node.js (Optional)
Running JavaScript Code
To run JavaScript in a web page, include a script tag in your HTML file:

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>JavaScript Example</title>
      </head>
      <body>
        <script>
            console.log('Hello, World!');
              </script>
              </body>
              </html>
              For server-side JavaScript, use Node.js:

              bash
              Copy code
              node myScript.js
              JavaScript Basics
              Variables and Data Types
              JavaScript has three ways to declare variables:

              javascript
              Copy code
              let name = "Ovie";    // Block-scoped, reassignable
              const age = 30;       // Block-scoped, constant
              var city = "Lagos";   // Function-scoped, reassignable
              Functions
              Functions can be defined in several ways:

              javascript
              Copy code
              // Function Declaration
              function greet() {
                console.log("Hello!");
                }

                // Function Expression
                const greet = function() {
                  console.log("Hello!");
                  };

                  // Arrow Function (ES6+)
                  const greet = () => console.log("Hello!");
                  Control Flow
                  JavaScript supports typical control flow constructs:

                  javascript
                  Copy code
                  if (age > 18) {
                    console.log("Adult");
                    } else {
                      console.log("Minor");
                      }

                      for (let i = 0; i < 5; i++) {
                        console.log(i);
                        }
                        Example Code
                        Here’s a simple JavaScript example that demonstrates variable declaration, a function, and control flow:

                        javascript
                        Copy code
                        const calculateSum = (a, b) => a + b;

                        let number1 = 10;
                        let number2 = 20;

                        console.log("The sum is:", calculateSum(number1, number2));

                        for (let i = 1; i <= 5; i++) {
                          console.log("Loop iteration:", i);
                          }
                          Resources
                          MDN JavaScript Documentation
                          JavaScript.info
                          Node.js - for server-side JavaScript
