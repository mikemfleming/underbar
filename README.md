# UNDERBAR

This repo contains code that will get you a little more comfortable 
with JavaScript. It teaches functional programming concepts, JavaScript 
fundamentals (like array methods), and basic Git workflow by having you 
create your own versions of functions from the popular [Underscore](https://underscorejs.org/) library
while commiting your work to version control. It assumes that you are on 
a Mac with Git installed already.

## Resources
Make sure that you are familiar with these topics before continuing. Don't
worry about getting into the weeds too much in the functional programming one,
it's just good to have the gist of it for now if you are unfamiliar. 
* [Types in JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Data_types)
* [For loops](https://www.w3schools.com/js/js_loop_for.asp)
* [Functional Programming](https://hackernoon.com/understanding-functional-programming-with-javascript-41eb3fa8c2a)

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
git add src/underbar.js
git commit -m "this commit message has a cat emoji 🐈"

# when you are ready to have your work reviewed, push your work up to Github
git push origin MIKE

# and then make a pull request with the GUI
https://help.github.com/en/articles/creating-a-pull-request#creating-the-pull-request
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
If you have a question, raise an issue using Github and @ me.

## Contributing
This is a living document that we can use to train people up on JS. Submit a pull request if you 
have an idea of how to make this better.
