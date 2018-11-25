
# Make a Text Based Game using Python

## Basic Concepts used:
- Lists
- Multidimensional Lists
- Loops

In this tutorial, we will learn to create a text based game in Python. I originally got this idea while going through r/learnpython. 

## Setup

I like to do my python work on VS code. I have nothing against other editors, it's just I started with it first and feel comfortable with it. 

All you need is an editor for this tutorial. I assume you have Python setup.

## Structure of the program

This is more of a quiz game. You get a question with four options and you have to answer them each and your score is updated every time.

So let's start by creating  a list of questions we would like to have. I am going to be using 5 questions but you can add more if you like. 

- What is the capital of Spain?
- What's the world's tallest mountain?
- Which country is New York located in?
- Who won World Cup 2018?

Then I will be creating my options.

1) Almeria, Getafe, Madrid, Barcelona
2) Mt. Alaska, Mt. Everest, Mt. Gatsby, Mt. XYZ
3) USA, Brazil, Argentina, canada
4) India, Russia, USA, France

Now I am going to store the position the correct answer is in. Weirdly, I am going to start with 0 which you will understand later on.

The correct answer for 1st question is Madrid which is in 2nd position( REMEMBER WE ARE COUNTING FROM ZERO!).

Similarly, the second is in 1st position.

The third is in 4th position.

Fourth is in 0th position.

Fifth is in 3rd position.

Now, let's wrap this up in Python.
