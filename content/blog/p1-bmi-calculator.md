+++
title= "Project 1. BMI Calculator"
author= "Natalia Dronova"
date= 2018-07-09
description= ""
tags= ["JavaScript"]
categories= ["Front-End"]
+++


One of the first things I heard when starting to learn web development was “Do projects, not tutorials”. I, of course, didn’t listen. I did multiple tutorials on Lynda.com, YouTube, Udemy and I thought I was doing great: I understood the concepts and did code-along websites. However, looking back at it,  “% of course completed” gave me a false sense of progress: I recognized the patterns but couldn’t replicate them on my own.

My first project completed with just HTML and CSS showed me how faulty this logic was. I knew nothing! After this revelation I did a few more static web pages and the process didn’t get any easier, I just got a bit better at googling.

Now I’m learning Vanilla JavaScript and doing my best to give equal attention to tutorials and projects.

## **BMI Calculator** 
Before starting [BMI calculator] (https://codepen.io/ndronova/pen/bKOwrr) I went through 4 first sections of [“Modern JavaScript From The Beginning” with Brad Traversy course on Udemy] (https://www.udemy.com/modern-javascript-from-the-beginning/learn/v4/overview).

I followed the course and coded-along the projects in Section 4. One of those projects, a “Loan Calculator” was a foundation for the “BMI Calculator”. I wrote out the steps I needed to follow based on what the instructor was doing in the tutorial and some hints, i.e:

1. Add event listeners (listen to submit, prevent default)
2. Assign inputs to variables (need to get the value)
3. Calculate BMI (round the number to nearest 2)
4. Show results (create new div element => create text node=> assign text node to div element => create reference node => add child to the DOM => add styling)
5. Validate BMI ( if… then error)
6. Compare BMI 

and then googled…

## *Requirements*:
* It should take name, height and weight of 2 people as an input
* It should calculate BMI for both people and compare them
* It should create a div tags with returned BMI scores and their comparison and assign Bootstrap classes to them
* It should reset form fields on button click and delete all div’s created in (3)
* It should check if BMI of each person is between 15 and 40 and if not, it should return an error

## *[Link to CodePen](https://codepen.io/ndronova/pen/bKOwrr)*


## *Lessons learned:*
* If it works, don’t touch it.
* Don’t try to make it perfect. I didn’t do this Calculator in 4 hours, like I promised: there was always a new issue or a new idea that I wanted to try out, and the more complex the code became, the more I wanted to “beautify” it. However, all those surface activities didn’t add value to the project, so… do it as best as you can, but not better.
