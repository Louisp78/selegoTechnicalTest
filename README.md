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
1. Profile Form Modification - Fix Input Disabled: The disabled property was not correctly configured, which was a crucial bug that needed fixing to allow profile modifications.

2. Register Form Input Save Not Working: This issue was blocking profile modifications due to an invalid condition that incorrectly disabled the form.

3. Invalid Username Value in Profile Modification Form: The username was not correctly retrieved from the API, leading to an incorrect value being displayed in the profile modification form.

4. Fix User Position on User Card (in the List): The user's position was not displayed due to incorrect naming. This has been fixed.

5. Resolved Linter Issues to Ensure Code Readability: Thanks to ESLint, all linting problems in the code have been addressed, significantly improving code readability.

6. Fix Navigation Side Section Toggle: Implemented state management to properly show/hide the navigation side section on click.

7. Fix Project Forms: Corrected the handling of project data returned by the API, which was previously encapsulated in an array.


- Which feature did you develop and why ? 
1. Add the input for setup availability of profile: Add the input in user modification because it's an essential feature.

- Do you have any feedback about the code / architecture of the project and what was the difficulty you encountered while doing it ?
1. Linter ESlint needed to fix some errors : displayName errors, invalid end of line.
2. It could be better to use Typescript for better type checking and avoid "the magic of JS", permit to avoid lots of bugs.
