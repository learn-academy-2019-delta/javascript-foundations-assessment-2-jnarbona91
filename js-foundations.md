# ASSESSMENT 2: FOUNDATIONS OF JAVASCRIPT
## Interview Practice Questions

### From memory, answer the following:

1. What's the difference between =, ==, and === in JavaScript?
= is used to set a value, == is used if you want something to loosely equal something in a function and === is used for exact values.


2. What is the difference between an array's index and length?
the index is where the element is located relative to other elements, index starts at 0. While length is how long the array is starting from 1.


3. What is a function's declaration, argument, and call?
the declaration is the function it self that gets executed, argument is the values youre passing through and call is what youre trying to declare.


4. What are the three main steps in saving work to github?
git add . git commit -m and git push


5. What is an object?
an object is the combination of state and behavior


### Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

Consider the function:

var text = 'outside'
function logIt(){
  console.log(text)
  var text = 'inside'
}
logIt()


1a. Look at this Javascript function and try to predict what the console show.
undefined

1b. Test the function. Explain why the function returned what it did.

  Your answer: theres nothing being passed through

  Researched answer: the variable wasnt assigned in the function's scope or passed through as an argument


2. What is JSON? How does it relate to javascript objects?

  Your answer: Javascript Object Notation. it relates to objects by allowing us to give an object multiple values to call on later

  Researched answer: JSON is a lightweight format for storing and transportating data.


3. What does CRUD stand for?

  Your answer: Create Read Update Delete

  Researched answer: Create Read Update Delete


4. What is a higher-order function?

  Your answer: a higher order function is a function that uses a function for another function

  Researched answer: a function that takes a function as an argument, or returns a function 


5. Stretch: What is a closure, what is it good for and how do you recognize one?

  Your answer: 

  Researched answer: Is an inner function inside an outer function. They have their own local scope and have access to outer scopes.


6. Stretch: What is an API?

  Your answer: 

  Researched answer: a set of functions and procedures allowing the creation of applications that access the features or data of an operating system, application, or other service.


### Additional Feedback Questions.

1. Do you have a suggestion for a Check In question?
Whats your favorite meal of the day?

2. What was your favorite topic this week?
React State


3. What was your "A-ha!" moment this week?
My a-ha moment was during the pig latin challenge, when we finally got the code to work