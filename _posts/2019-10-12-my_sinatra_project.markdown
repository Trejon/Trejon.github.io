---
layout: post
title:      "My Sinatra Project "
date:       2019-10-13 00:59:55 +0000
permalink:  my_sinatra_project
---


After short deliberation I decided for my Sinatra portfolio project I would build a Model View Controller app to create, update, and delete recipes from a user's collection. I used four controllers for this app to ensure all routes are being directed correctly. I created a controller for the application which has been a common theme in most of the projects we've been working with. After creating this controller I decided I'd need another controller for my users, recipes and their sessions. In my application controller I store my homepage method and create helper functions to make my routes in the other controllers more simple. In my user controller I create routes to post a form for a user to signup as well as another post form to create a new user from the params entered. In my sessions controller I placed routes that help complete the user's login as well as sign the user out of the app. Finally I created a controller for my recipes that is capable of creating a new recipe, updating an existing recipe, deleting an old recipe and storing it all. 

Along with these controllers I, of course, created views for my recipes, users, and sessions to display the proper information on each page I'm rendering or redirecting to. Each route I previously created in the controllers has it's own view. In order to store my data, I then created migration tables to hold my user's and recipes information. I created additional migrations to add new columns to my table and allow my user to include more information on themselves and the recipes they create. Once the whole project came together my user should be able to log in with an email, username, and secure password into their account and only view and edit the recipes they've created. Once a user is finished they can log out of the account and return to the login page to either sign in or sign up. 
