# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

    .map - automatically returns a new array of converted data, you would use this if you needed to see an array of specific keys taken from a large array of objects

    .reduce - returns a single value by taking in 2 parameters: the running total (accumulator) and the current element being processed in the array, it also needs an initial value so it knows where to start the equations: for adding usually 0 is used, and if multiplying usually 1 is used. This could be used for pretty much anything but is most commonly used for sums and products.

    .filter - returns a new array after filtering through an array of data and deciding if that data is true or false, if it's considered true it is included in the new array, you could use this if you wanted to see an array of specific dates from a larger array of objects

2. Explain the difference between a callback and a higher order function.

    A higher order function is a function that takes in another function as an argument.

    A callback function is the function that gets passed as an argument into a higher order function

3. Explain what a closure is.

    A closure happens when an nested function reaches into its outer function to grab a variable that is defined in the outer function

4. Describe the four principles of the 'this' keyword.

    Window Binding: an error that occurs when 'this' isn't given context so the browser returns the window or undefined if in strict mode

    Implicit Binding: this occurs in 80% of use cases and applies to objects with methods, when we invoke the function it looks to the left of the dot and that is what 'this' refers to

    Explicit Binding: when we explicitly state what 'this' refers to by using .call/.bind/.apply

    New Binding: applies when a function is invoked as a constructor function by using the 'new' keyword to create a new object and 'this' refers to the new object that was created

5. Why do we need super() in an extended class?

    super(), when used together with extends, allows the child to inherit all the attributes of the parent class by doing what .call and Object.create do

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
