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

   .map() allows you to loop through all elements in an array and makes a new array based on the existing array. You can make changes to the existing array and move the new values to the new array. An example would be trying to add 5 to every element in the array. This would easily be done with a .map() method.

   .reduce() will reduce the array to a single value. You can use any math operator to calculate the new single value, and an accumulator variable is returned as your single value. An example would be if you wanted to know the sum of an array of numbers. You could use the reduce() method to sum all of the values in the array and return the single sum.

   .filter() allows you to loop through the array and filter out any unwanted values, and then return a new array with on the desired values. An example would be if you wanted to filter out all of the numbers in an array that are greater than 10. You could use the filter() method to filter out values greater than 10 and return a new array with only the values less than or equal to 10.

2. Explain the difference between a callback and a higher order function.

   A higher order function takes another function as an argument while a callback function is a function passed into another function. The function being passed as an argument into a higher order function is a callback function by definition.

3. Explain what a closure is.

   Closure is when a function reaches outside of its scope to a higher function for a variable/value. The need for a lower function to reach into the higher function for a value is a closure.

4. Describe the four principles of the 'this' keyword.

   1. When the 'this' keyword is in global scope, meaning it is not scoped to a function or object, then it will return window Object
   2. Implicit Binding - whatever is before the '.' when calling the function, it is implicitly bound to the newly created object
   3. New Binding - When a constructor function is used, 'this' is referring to the specific instance of the object that was returned by the constructor function
   4. Explicit Binding - when using call or apply, 'this' is explicitly defined for the creation of the new object

5. Why do we need super() in an extended class?

   The super() function is needed because it is used to call the variables and methods of the parent class. You would otherwise need to call the parent class and pass the variables and set the child prototypes equal to the parents prototypes. With the super() function you can now recieve all of the parents methods and variables with a single function.

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
