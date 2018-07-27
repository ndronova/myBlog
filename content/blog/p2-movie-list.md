+++
title= "Project 2. Movie List"
author= "Natalia Dronova"
date= 2018-07-11
description= ""
tags= ["JavaScript"]
categories= ["Front-End"]
+++



## **Movie List**
I had to go through 5th (theory) and 6th (practice – Book List project) sections of [“Modern JavaScript From The Beginning” with Brad Traversy course on Udemy] (https://www.udemy.com/modern-javascript-from-the-beginning/learn/v4/overview) twice and then look for another course on JavaScript OOP. I just couldn’t seem to grasp the idea of prototypes and constructors and couldn’t understand why we need to create objects. Previous project, [BMI Calculator from Day 1](#) worked just fine without all that stuff. I was scratching my head for at least 8 hours learning the basics and doing 2 identical code-along Book List projects before I felt like it all made sense. Once it did, it took me 3 hours to create a Movie List, of which I’m very proud.

## *[Link to CodePen](https://codepen.io/ndronova/pen/qKGJyG)*

## *Requirements*
1. It should take movie, year and star rating as input
2. It should validate all inputs and display error or success message on submit
3. It should have an option of deleting the book
4. It should number all books added

## *Lessons learned*
* I need to stop relying so heavily on Bootstrap to save time and write my own CSS. After all, it is another area I want to improve on.
* I don’t know what I don’t know and I need someone who knows what it is that I don’t know, so finding a study group and a mentor is a priority.

## *Small wins*
* I created Movie List without looking much at the Book List (from Brad Traversy’s course mentioned above). It felt great to do what I once thought I couldn’t!
* I took the first step of thinking in JavaScript instead of just remembering the methods used in online courses! At first I wanted to sort all books added based on their star rating. After frying my brain for a little bit with this challenge, I settled for just numbering every movie submitted (small steps, eh). So my elegant (or not, I don’t know yet) solution was to count all table rows and display the number along with a submitted movie:

        {{//count table rows}}
        {{const sortOrder=document.getElementById('movieList').getElementsByTagName}}