---
layout: post
title:      "Final Project"
date:       2020-04-23 01:24:58 +0000
permalink:  final_project
---


Now that I'm wrapping up my 10 month program, I really have no other choice but to be cliche and say it's truly bittersweet. Throughout my time at Flatiron I've gained an invaluable skill set, all the while surrounding myself with knowledgable and inviting people. I'm going to miss the weekly cohorts, and guidance for all questions and concepts I needed further explanation on. Although my journey as a student at Flatiron is coming to an end, it has led me to a new lifelong journey. If nothing else, I can say this program has sparked my curiousity and drive more than I could have ever imagined.

Going into my final project I was unsure of what to build. As a starting pointing, I decided to incorporate more than one API, since dealing with promises has been an ongoing battle for me since starting Javascript. This led me to explore and discover a couple popular ones that would pair well together. As a result, I built a CRUD app allowing users to store meal options for future reference. I used four APIs in the proccess; Google Maps, Yelp, HTML5 Geolocation, and a custom recipe API created by a Udemy instructor called, Forkify. 

My application allows users to signup for an account and store their information in a Rails API user table, to be accessed later for login.  Users accounts are secured using the bcrypt gem to ensure all passwords are encrypted. After a user is logged in, their info is persisted on the clientside using session cookies which remain available until session reset on logout. Users can create multiple lists which have full CRUD capability, and lists are capable of having multiple meals while also belonging to the user. This allows users to customize meal plans, and compile cooking or outing ideas. 

![](https://imgur.com/iEPd7dF)

I have two main pages for my Yelp API and Forkify API, which return the data of the fetch requests once a user enters a search term. My restaurants' component returns data displayed in cards,  including the place's location marker on the map rendered by Google. The user can then click on the restaurant cards and see more information about the specific restaurant, and also select a list of theirs to add it to. The recipes main page has the same funtionality minus the map. This allows users to easily browse meal options and then save them in a customizable list. Once a restaurant or recipe is added onto a list, the user is able to edit, delete, and show further details. Recipes have urls for easy follow-along instructions and restaurants have addresses for easy location tracking on their card block.

This project was by far my favorite to work on, and I definitely feel like the React and Redux framework made it more appealing. Using the Redux store to control almost every aspect of my app made debugging a lot easier by allowing me to have one main location to hunt down the majority of bugs. React components along with packages such as React Router allowed me to be completely in control of what the user was able to see and on which corresponding page. This project, as all of the previous, has led me to study a ton of new topics and dive deeper into advanced concepts such as React hooks. I really enjoyed being able to showcase everything I've learned up to this point and am excited for the next challenge to come. 
