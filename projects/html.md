---
layout: project
type: project
image: img/cotton/htmlkeys.jpg
title: "Teaching VS Code"
date: 2024-11-20
published: true
labels:
  - Teaching Assistant
  - VS Code
  - HTML
  - CSS
summary: "In order to become a fully-fledged lab assistant, I had to teach an introductory lesson about HTML and Visual Studio Code."
---

<img width="450px"
     class="float-start pe-4" 
     src="../img/cotton/htmlcode.jpg" >

### Assistant Teaching Assistant?
In my Fall 2024 semester, I had the opportunity to be an ATA for the introductory ICS 101 class at UH Manoa. Although this class was not a requirement to graduate with a degree in computer science, I had taken it due to my previous background as a business major. As a result, I knew a bit more going in how the labs operated and what they'd teach.

In addition, all of the other TAs were very friendly and supportive, always giving me advice and talking to me before and after lab. Their warm personalities really sold me on the idea of becoming a real LA; however, I had to pass one test.

### Teaching a Class
I was able to become an ATA because of a computer ethics class I was taking, ICS 390. So a part of my grade, in addition to going to office hours and helping out in labs, was teaching one lesson in the class. My previous plan was to teach a somewhat easy lesson earlier in the semester, but by some unlucky happenstance the wifi went out in the building, so I was unable to teach that day. As I wasn't very fluent in the other lesson plans, I decided to teach HTML instead.

Despite the change and the fact that I'd never taught a class before, the TAs grading me all said I did really well. They claimed that my lesson was easy to follow and I went slow enough so people could keep pace together. Here is the code for the home page I created:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Coffee Shop</title>


    <link href="style.css" rel="stylesheet" type="text/css" />
</head>


<body>
    <div id="container">
        <header>
            <h1>My Coffee Shop</h1>
            <nav>
                <ul>
                    <li><a href="index.html"><div id="home"></div></a></li>
                    <li><a href="menu.html"><div id="menu"></div></a></li>
                    <li><a href="more.html"><div id="more"></div></a></li>
                </ul>
            </nav>
        </header>


        <figure>
            <img src="pics/coffeeshop.jpg" alt="Coffee Shop"/>
            <i><figcaption>You can add captions to your pictures like this!</figcaption></i>
        </figure>
    </div>


    <div id="content">
        <h2>About Us</h2>
        <p>Everyone here at My Coffee Shop wants to give you the best experience possible, whether it be to sit down and study, socialize, or just to pop in and grab a cup of coffee every morning before work. No matter what, you're always welcome here at My Coffee Shop. Thank you for stopping by!</p>
        <p>The discount items of the week are:
            <ol>
                <li>Strawberry Smoothie</li>
                <li>Cappuccino</li>
                <li>Avocado Toast</li>
            </ol>
        </p>
    </div>
</body>
<footer>
    <p>This is the website I found my images on: <a href="https://www.pexels.com/search/coffee%20shop/" target="_blank">Pexels</a></p>
</footer>
</html>
```

### Base Knowledge
Because I had to teach HTML and Visual Studio Code to introductory students, who I have to assume do not know anything about the two subjects, it really pushed me to return to the basics and understand every single line of code I wrote. I wanted to feel confident enough that I could explain everything in a simple, easy to comprehend manner. Often times, people who are really skilled in their craft do not know how to teach beginners, because they forget what it was like to learn the subject for the first time. So teaching the lesson really helped me to step out of that mindset and try to explain things as simply as possible (and I got better at HTML as a bonus).

At the time of creating this project, I've had the opportunity to return as a newly hired lab assistant. Now, with my HTML teaching day deemed an A+ success, I'm extremely prepared for when the lesson comes up again at the end of the semester.
