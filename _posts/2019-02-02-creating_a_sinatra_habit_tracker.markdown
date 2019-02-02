---
layout: post
title:      "Creating a Sinatra Habit Tracker"
date:       2019-02-02 14:52:04 +0000
permalink:  creating_a_sinatra_habit_tracker
---


**Basic Overview**
For my Sinatra project, I decided to create a simple habit tracker with the following structure:
* A user has_many habits
* A habit belongs_to a user, and has_many days
* A day belongs_to a habit 

The user can complete all CRUD actions--create, read, update, and delete--on a Habit, and then view how many times they've completed the habit. 

**Stretch Goals:**
I've completed the MVP verison of my app that I'm happy with, but I have some stretch goals I'd like to implement when I have time: 
* Give the Day class more functionality (or figure out how to use Date class with Active Record Associations)-- Right now the days for any given habit are stored as a string, which works for an MVP, but I'd like to have the ability to display the dates nicely and maybe even get a calendar view in there some day.
* Create a page that shows ALL habits, regardless of user, for a user to view for habit inspiration
* Give each Habit a Plan-- I recently read *Atomic Habits* by James Clear, which emphasized the importance of planning habits. At the lowest level, I think a plan would be a text input but with guidelines to help a user effectively plan a habit with some of the methods that have proven success.
* Add verification that e-mail is actually an e-mail--Right now, you can put anything into the "email" box and it will sign you up. I'd like to add verification so that each e-mail has an "@" and a "." for the account to create.
* And, of course--better styling!

**Looking Forward...**
I want to go into UX, which I assumed was primarily front end design when I started Flatiron. Through this project, I also learned that I get a lot of satisfaction from working on the back end code to make things easier for the user. I love thinking about how a user will interact with what I'm creating, and I liked that this project (as well as Howard's instructional videos) gave me a lot of opportunity to do that through back-end code with custom error messages and validation. 
