# Technical test

## Introduction

Fabien just came back from a meeting with an incubator and told them we have a platform “up and running” to monitor people's activities and control the budget for their startups !

All others developers are busy and we need you to deliver the app for tomorrow.
Some bugs are left and we need you to fix those. Don't spend to much time on it.

We need you to follow these steps to understand the app and to fix the bug : 
 - Sign up to the app
 - Create at least 2 others users on people page ( not with signup ) 
 - Edit these profiles and add aditional information 
 - Create a project
 - Input some information about the project
 - Input some activities to track your work in the good 
  
Then, see what happens in the app and fix the bug you found doing that.

## Then
Time to be creative, and efficient. Do what you think would be the best for your product under a short period.

### The goal is to fix at least 3 bugs and implement 1 quick win feature than could help us sell the platform

## Setup api

- cd api
- Run `npm i`
- Run `npm run dev`

## Setup app

- cd app
- Run `npm i`
- Run `npm run dev`

## Finally

Send us the project and answer to those simple questions : 
- What bugs did you find ? How did you solve these and why ? 
- Which feature did you develop and why ? 
- Do you have any feedback about the code / architecture of the project and what was the difficulty you encountered while doing it ? 


I found quite a bit of bugs. The problem was, I found it hard to solved this bugs because I didn't have access to the Database.

-  I can now update my user infos from the section "My account" but the one with a ton of infos noting happened and I couldn't find the problem because I couldn't test the "route" and I didn't have access to the Database.

- I can now add new users but I failed to update the users infos because I couldn't find the problem and I couldn't test the "route" and I didn't have access to the Database.

- There was one when I try to enter a specific project, I couldn't find the infos and I couldn't access the "routes" once again.

I find it difficult because I couldn't see precisely where the bugs came from (if it was the requests or the code).

If I could have solved the bugs I would have done a notification system for the startup so they know if they make a financial deficit or not and maybe give them tips or maybe put them in contact with a specialist.
