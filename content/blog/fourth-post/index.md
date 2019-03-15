---
title: 'week 4: UI with the UX'
date: "2015-06-28T22:40:32.169Z"
---

contribution graph: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/graphs/contributors

github handle: BrooksPoltl 

Pulls:

responses fixed: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/23

changed survey response endpoint: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/64

added styling to guest survey dashboard: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/68

part 1:

This sprint was really about getting the app to not just be functional, but
seemless to use. We still had a few functionality things to do, and sasha and myself tag teamed to get it done. I got the endpoint returning the structure that she needed for the front end for the final functionality. We added a lot of styling to make the project look better. I changed the JSX a little that way when you select a survey you only have to hit the card instead of the link. This makes 
the user experience so much more enjoyable. With only having to click the card it allows the user to not have to concentrate on the accuracy of the mouse click. 

Detailed Analysis: changed survey response endpoint

Getting the correct data for all of the stay responses was really difficult. 
Maybe GraphQL could have made it easier to get the data exactly how we wanted it, but I was ultimately able to get the endpoint to return exactly what sasha wanted
at the cost of O(n^2). Luckily the nested for loop won't have a high n, the high n possibilities are limited to O(n) time complexity. I'm not super happy about how
the algorithm went, but it got the job done. If I had more time I would go back and refactor it to be faster, or find a tool that would help complete my goal efficiently.

screenshots: https://imgur.com/a/VjkzEEA

part 2: 

The goal of UX is for the user to be able to understand how the app works
without having anything be explained to them. It is also important to have
consistency throughout the looks of the app. You don't want to be able to tell
that two different developers worked on different parts. We did this by
sharing components to have consistent styling. It is honestly really hard to shift to UX, because maximally efficient functionality feels so important, but
UX focuses on the customer instead of the  developer. Which without the customers your app is useless. This was the change in headspace that made the shift easier to commit to. 