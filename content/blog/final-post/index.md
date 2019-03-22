---
title: 'week 5: The Final Countdown'
date: "2015-07-28T22:40:32.169Z"
---

contribution graph: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/graphs/contributors

github handle: BrooksPoltl 

Pulls:

added map: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/108

fixed updates: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/106

changed to id: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/105

changed back endpoint: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/103

fixed bug that allowed multiple submits: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/99

added documentation: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/89

part 1: 

This week we added the finishing touches of the project. We had issues with the deployment of the features we had implemented because of the differences between sqlite and postgres. After we found out about this issue, we spent most the week finding the differences within the backend and altering them to work in the production environment as well. We also fixed tiny bugs that caused unintended things to happen. 

detailed analysis for pull request "fixed bug that allowed multiple submits":

As the project closes we had to add things to production to check them. This meant that we had a lot more pull request this week, but the content was not really feature changing or noticable. Initially I did not program the post endpoints to check if the question has already been submitted, so I added a check at the beginning to make sure. If it fails it returns a 400 error. The way the application works now you should never be able to submit twice, but if you change the route and fill the form again, it won't submit again. 

part 2: 

Working on this project truly taught me about the importance of working together as a team. Throughout the project we had dysfunction and often times found ourselves being inefficient with our time because of bottlenecking other group members. Things that could have been fixed by 1 person ended up costing the entire group time because of lack of communication. This project was a great learning experience, because before now our coding journey had been independent, when in reality all of us will have to work with a team in our career. Our hardest task at the end was dealing with sqlite and postgres differences, we hadn't really thought about it until we encountered it, and had to go into panic mode. Ultimately this project was a great learning experience as far as teamwork, and I'm excited to apply it in my career.