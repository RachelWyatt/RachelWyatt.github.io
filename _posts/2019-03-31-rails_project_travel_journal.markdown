---
layout: post
title:      "Rails Project: Travel Journal"
date:       2019-03-31 14:14:57 +0000
permalink:  rails_project_travel_journal
---


For my Rails Project, I created a Travel Journal. The idea behind this was to create a Twitter-like application where "tweets" (AKA journal entries) can be viewed by the trip they were written on. A user can create Trips, and Trips have Trip_Entries. Trip_entries serves as the join table for Trips and Locations, but also has a user-submittable input of Journal-Entry. 

For me, the most intimidating part of this project was trying to figure out where to get started--with so much to do at the start, it feels overwhelming! To help with this, for both my Sinatra and Rails projects I've followed along with the Live Coding series on the Learn Instruct website. 

A high-level overview of how I went about building this project:

1. Create models and associated migrations, and add validations to models (and use Rails console to ensure they're working correctly!)
2. Work on scope method--I actually ended up redoing this at the end of my project because I changed my mind about what I wanted, but this is a good time to build it and be able to test whether or not it works in the console without other complicating factors.
3. Create routes and controllers
4. At this point, my work started pivoting back and forth between views and controllers. Generally, I would add an action to a controller and then generate the associated view. I drew out the functionalities that I wanted a user to be able to do, so I followed that flow chart here. For example, in one flow, I want a user to Sign In, View their Trips Index Page, click a link to a trip show page, etc. Since I don't have all the CRUD actions for all my models, this let me stay focused on just the pages I need for my MVP.
5. Add Omniauth 
6. Add styling! I still have a lot more I want to do here, but I used bootstrap to get things looking somewhat acceptable for the time being. 
