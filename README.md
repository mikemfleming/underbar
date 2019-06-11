# UNDERBAR

This repo contains code that will get you a little more comfortable 
with JavaScript. It teaches functional programming concepts, JavaScript 
fundamentals (like array methods), and basic Git workflow by having you 
create your own versions of functions from the popular [Underscore](https://underscorejs.org/) library
while commiting your work to version control. It assumes that you are on 
a Mac with [Git](https://www.git-scm.com/book/en/v1/Getting-Started-Installing-Git#Installing-on-Mac) installed already.

## Resources
Make sure that you are familiar with these topics before continuing. If you
don't already know all these concepts pretty well then just focus on getting
the gist of each and know that you can reference these documents when you 
need to. 

Don't worry about getting into the weeds too much in the functional programming 
ones, they're just there to expose you to the concept. 
* [Types in JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Data_types)
* [JavaScript Expressions](https://medium.com/launch-school/javascript-expressions-and-statements-4d32ac9c0e74)
* [Conditional Statements](https://www.w3schools.com/js/js_if_else.asp)
* [Arrays](https://www.w3schools.com/js/js_arrays.asp)
* [Objects](https://www.w3schools.com/js/js_object_definition.asp)
* [For Loops](https://www.w3schools.com/js/js_loop_for.asp)
* [Functions](https://www.w3schools.com/js/js_functions.asp)
* [Functional Programming](https://hackernoon.com/understanding-functional-programming-with-javascript-41eb3fa8c2a)
* [Professor Frisby's Mostly Adequate Guide to Functional Programming](https://mostly-adequate.gitbooks.io/mostly-adequate-guide/)
* [Debugging with Chrome](https://developers.google.com/web/tools/chrome-devtools/javascript/)

## Installation
In your terminal, run:
```bash
# clone the repo from github to your working directory
git clone https://github.com/mikemfleming/underbar.git

# change into the resulting directory
cd underbar

# open the spec runner in your browser
open SpecRunner.html
```

## Git Workflow
We'll use Github to save and submit your work just like we would for
any kind of professional project. 
```bash
# first, create a branch off of the master branch with your name.
# this will simulate a production branch of code that could be deployed.
git checkout -b MIKE

# save your branch to Github's remote servers
git push origin MIKE

# cut another branch off of your name branch. this one will be for our work 
#   in progress code.
git checkout -b MIKE-WIP

# save your progress as you go
git status # see what files have changes
git diff # see the individual changes
git add src/underbar.js # stage your changes to be committed
git commit -m "this commit message has a cat emoji 🐈" # commit your changes with a message

# when you are ready to have your work reviewed, push your wip branch to Github
git push origin MIKE-WIP

# and then make a pull request with the GUI
open https://help.github.com/en/articles/creating-a-pull-request#creating-the-pull-request
# in this example, 
#   the compare branch would be MIKE-WIP and 
#   the base branch would be MIKE
```


## SpecRunner.html
This file contains all the tests that will run against the functions
you write in this exercise. See all the red x's? That's the tests
running against all the functions that you haven't written yet.
Keep this open in your browser and refresh it whenever you would
like to run your code against the tests. 

## src/underbar.js
This is where you will actually write your code. The instructions are
mostly in the comments so make sure you read and follow those. 

Good luck!

## Questions
If you have a question, raise an issue using Github's issue system and @ me.

## Stuck?
If you're using Chrome as your browser then you should familiarze yourself with their [dev tools](https://developers.google.com/web/tools/chrome-devtools/javascript/).

## Contributing
This is a living document that we can use to train people up on JS. Submit a pull request if you 
have an idea of how to make it better.
