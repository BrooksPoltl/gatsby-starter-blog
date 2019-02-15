---
title: 'Week 1: Trials and Tribulations'
date: "2015-05-01T22:12:03.284Z"
---


This week was the first week of Lambda Labs, a 5 week capstone for lambda school.
Our group is a part of an experiment group in that we have to add features
to an already existing project.

We were tasked this week with getting a Technical Design Document done
and  getting the project deployed with the frontend and the backend.

On the TDD I wrote out a couple of the features that we will be adding. I created the
user stories and added the backend API requirements that we will need for the
features. I also added most of the reasons for the the architectural decisions that we made.
Our choices were limited based on the existing codebase, but we believe that the choices of 
the previous group were solid. 

Deployment... Sounds easy enough, but dealing with environment variables and tons of test
already written into the code made this extremely dificult. We were in zoom working hard on trying to
get the front and back deployed. We were able to get the frontend deployed on our local machines,
but we were encountering errors with signing in via firebase auth. I started bug fixing trying different
things out with the environment variables. I used the previous groups backend url and it worked! 
This showed me that the issue was relating to the url. I reverted to the localhost backend and opened the console to see a post request with a 403 error to http://localhost:4500//users i did it! the additional
slash in the URL was creating a faulty request, I got rid of the slash, and quickly went to run it again.
opened up the console and... 400 error. Life is good. A member from the previous group came and helped us.
The issue was we needed to migrate the latest schema. We were unable to complete MVP for the week on time,but eventually we were able to get the frontend and backend deployed. 

model 
https://dbdiagram.io/d/5c61f6b4f7c5bb70c72efe44

frontend: 

https://labs10-cleaner-app-frontend.herokuapp.com/
https://xenodochial-murdock-91cfeb.netlify.com/

backend: 
https://labs10-cleaner-app-2.herokuapp.com/