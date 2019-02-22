---
title: 'week 2: Moving on Up'
date: "2015-05-06T23:46:37.121Z"
---
contribution graph: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/graphs/contributors

github handle: BrooksPoltl

setup new tables: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/5

changed the navbar: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/13

fixed all the URLs in the code: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/14

created survey endpoints: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/17

part 1:

This week we worked on the API. I setup some of the migrations to allow data to get stored to the database
Then added a survey tab to the the navbar, having the previous code made this process seamless. Dealing with
an existing codebase there were many places where our deployed version was pointing to the old backend, I 
was able to use VSCode's search feature to find all those places and switch them to our backend. Lastly I created
the post put and delete endpoints for the surveys route.  

detailed analysis:

for creating the endpoints I did a POST request that way people can create surveys. Currently the schema
requires a house ID, but I think we should replace that with a user ID. This will allow us to tie surveys
to the user instead of the house. A good way to do this would be to use the email or ext_it in the token.
I also made it possible to edit a survey that way you can correct mistakes created in the survey. I also
created an ability to delete a survey if you don't think it fits your need anymore.

picture of the added endpoints: https://i.imgur.com/A4sf0mz.png

picture of search example: https://imgur.com/wsyGPob

picture of added navbar item: https://imgur.com/069AT3o

part 2:

When our group came together we were all extremely shy. It took a while to break
the ice, but now I feel like people are a lot more comfortable contributing
ideas to the group. To help solidify the group I kept the energy positive. While
we were struggling last week I would laugh at it instead of being negative. Something that
I did to cause friction was probably being too direct when things aren't working. 
Being too direct can hurt peoples egos, and cause friction in the group. To create group cohesiveness
I've spent time getting to know everyone better. With us all being pretty shy it means we have
to feel comfortable to voice our opinions.

live:https://xenodochial-murdock-91cfeb.netlify.com/
