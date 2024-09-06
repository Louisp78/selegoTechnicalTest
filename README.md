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
 - Input some activities to track your work in the good project
  
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
1. **Modification of profile form fix input disabled:** The disabled property was not setup correctly. This bug was important to fix to permit to modify the profile.
2. **Register form input save not working:** Because blocking for profile modification. Invalid condition to form disabled.
3. **Invalid username value filled value in the profile modification form:** The username was not retreived correctly from the api.
4. **Fix user position on user card (in the list):** not displayed because of invalid naming.
5. **Fixing all the linter problems to ensure code redability:** Thank to my amazing friend Eslint i have fixed all the linting problems in the code.
6. **Fix the setOpen side section for navigation**: implementation of a state to hide / show the nav section on click.
7. **Fix project forms:** fix the project return by api which is inside an array.
- Which feature did you develop and why ? 
1. **Add the input for setup availability of profile:** Add the input in user modification because it's an essential feature.

- Do you have any feedback about the code / architecture of the project and what was the difficulty you encountered while doing it ?
1. Linter ESlint needed to fix some errors : displayName errors, invalid end of line.
2. It could be better to use Typescript for better type checking and avoid "the magic of JS", permit to avoid lots of bugs.
