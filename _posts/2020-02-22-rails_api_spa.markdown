---
layout: post
title:      "Rails API SPA"
date:       2020-02-22 23:55:19 +0000
permalink:  rails_api_spa
---


I've worked on my Javascript and Rails project for the past two weeks, and it's allowed me to see the benefits of using Javascript. One of the primary reasons being not having to redirect for each new web request, as I did with my Rails application. This project was a single page application meaning everything rendered on screen was by replacing the inner content of the page. One really interesting feature I learned about during this process was the power of a Javascript navigation bar. I created a router and navbar to work together to allow me to make it appear as if the user was redirecting pages but at a much faster rate. Using Javascript event listeners, I was able to redirect based on the target of the user's clicks, making this project seem a lot like my Rails banking app I had previously built. Using these event listeners I was also able to have my frontend the user was interacting with, speak to the backend API of my project. This allowed users to create, read, update and delete pieces of data from the application giving them full control. The backend of my project still handled most of the authentication however my frontend was able to still contribute in requiring fields for forms, and handling the unique JSON web token given to the user on login. With this web token the user of my app is able to make secure requests to the backend to complete all of the necessary CRUD actions. 




![](https://images.unsplash.com/photo-1518773553398-650c184e0bb3?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=800&q=60http://)



On the backend side of my project I used Devise for authentication which allowed me to have access to helpful methods, such as 'current_user', to ensure I was rendering data for the specific user that was logged in. When the user logged out I then was able to set the JWT(JSON Web Token) value to null and blacklist it on the backend so it couldn't be reaccessed. I thought this was appealing as the bulk of the project was written in the frontend but still had full capabilities as an all Rails CRUD app would. 

After completing this project it's very apparent why Javascript is such a staple for developers to learn and why it is used in many different applications. Along with the speed in rendering it provides, it also allows the user to be much more interactive with the page they're on. Event listeners really change the game and allow a developer to customize as much of their application as they'd like. Some of those events include listening to the position of a user's mouse, a click, a submit button being pressed, a window being resized, or even the keystrokes of the user. This opens up an entirely new world of options for a developer to make their application do what they'd like. Overall this project as taught me this expansive world of Javascript and all the possibilities as I continue learning. 


