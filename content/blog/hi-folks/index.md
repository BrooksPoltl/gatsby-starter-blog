---
title: 'week 3: Things are looking up'
date: "2015-05-28T22:40:32.169Z"
---
contribution graph: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/graphs/contributors

github handle: BrooksPoltl 

week 1 Pulls:

fixed the schema: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/23

fixed the endpoints: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/27

got functionality working: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/30

fixed the master branch: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/37

week 2 Pulls: 

question types: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/41

changed schema: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/46

finished fill a survey functionality and styling: https://github.com/Lambda-School-Labs/labs10-cleaner-tool/pull/55

part 1:

This week was the first week that we really put our schema and endpoints to the test, and created something
visible to the app. Working on the frontend alerted us to many problems on the schema. Not having a proper
schema can completely unravel the whole operation. Our endpoints left too much logic on the front end to make 
it work, and in some cases impossible. Therefore we had to change the schema. Ultimately you never want to spend
that much time refactoring work, especially with a deadline quickly looming, but this was an existintial issue that needed to be solved. We had to fix the leak instead of cleaning the water. 

detailed analysis for pull request "fixed the schema":

Originally when fixing the schema was proposed it was a controversial suggestion. The project "seemed" 
possible with how the current schema worked, because this connects to this connects to this. The simplest solution for every problem was continually putting off the inevitable. We just didn't know the inevitable was going to happen until we stared it straight in the face. We had issues with it such as missing the type of question and not having a user id attached to the survey.

screenshots: https://imgur.com/a/huTg6jH

detailed analysis for pull request "finished fill a survey functionality and styling":

Having various types of questions can make creating the questions complicated, but with 3 questions and 3 question types it leaves only 9 possibilities. So I used the "type" on the schema to decide what type 
of component it renders. At first the way that I made the Boolean component work was really complicated, but
I found a way to refactor it using useEffect to make the component handle different changes to the parent state. 
I was able to use the useEffect in the OutOfFive component with minimal changes. I tried various styling tactics
to create an active class, but ultimately I used a ternary operator which helped me realize that i could clean up the JSX for the buttons using map.


part 2:

I used to hate working with others in Git, now I love it. Ok, hate is probably a strong word. By hate I mean it
caused so much frustration. This is because I had no idea what I was doing. When you don't understand git, a merge conflict is the end of the world, but it is amazing how simple it truly is once you understand what it is doing. solving a merge conflict in git kind of feels like ordering a burger, and it is really pleasing to solve. 
I'll have jalepenos but no mayonaise. I'll have this new styled component, get rid of the old jsx div. 

features(only works on localhost): 

create a survey:'/createsurvey'

guest dashboard: '/guestdashboard/:id'

view your surveys: 'surveys'

view your survey's responses: 'surveys/:id/responses'

week 2:

guest survey landing page: '/guestdashboard/:stayId/surveys'

individual survey: '/guestdashboard/:stayId/surveys/userId/surveyId'
