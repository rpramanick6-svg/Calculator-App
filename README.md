# Calculator-App

I built this project as a simple browser-based calculator using HTML, CSS, and JavaScript. The application performs basic arithmetic operations and provides an interactive user interface where users can enter numbers, choose operators, clear input, delete the last digit, and calculate results.

## Overview

In this project, I mainly focused on building the JavaScript logic that powers the calculator. I worked on handling number inputs, mathematical operators, calculation flow, backspace functionality, clearing the screen, and updating the display dynamically based on user actions.

The user interface is built with HTML and styled using CSS to give the calculator a clean and modern glassmorphism-inspired look.

## Features

- I created a functional calculator interface with number and operator buttons.
- I implemented addition, subtraction, multiplication, and division operations.
- I added support for clearing the calculator state using the `C` button.
- I implemented backspace functionality using the `←` button.
- I updated the display dynamically as the user clicks buttons.
- I used event delegation to handle button clicks efficiently.

## My Contribution

My primary focus in this project was on writing the JavaScript functionality. I worked on the calculator logic by managing values such as the current buffer, running total, and previously selected operator. I also implemented functions to handle numbers, operators, and the final calculation flow.

For the CSS styling and visual design, I used references from tutorials and AI assistance where needed. My main learning objective in this project was to understand how JavaScript functions can control user interaction and application state in a real working UI.

## Technologies Used

- HTML
- CSS
- JavaScript

## JavaScript Logic

In this project, I used JavaScript to manage the calculator state through variables like `runningTotal`, `buffer`, and `previousOperator`. I created functions to handle different types of button inputs:

- `handleNumber()` updates the current value shown on the screen. [file:195]
- `handleSymbol()` processes special buttons like clear, equals, backspace, and operators. [file:195]
- `handleMath()` prepares and stores the selected mathematical operation. [file:195]
- `flushOperation()` performs the actual arithmetic calculation based on the previously selected operator. [file:195]
- `buttonClick()` decides whether the clicked value is a number or a symbol and sends it to the correct handler. [file:195]

I also used event delegation on the button panel so that all calculator button clicks could be managed through a single event listener. [file:195]

Through this project, I improved my understanding of:

- DOM selection
- Event delegation
- Conditional logic in JavaScript
- Managing application state with variables
- Handling arithmetic operations programmatically
- Connecting JavaScript functionality with a styled frontend interface
