# Frontend Coding Challenge

## Overview of this Assessment 🌍	

This task is made up of 2 parts. The first part tests your design proficiency and how well you can handle your CSS. The second part tests your logic skill and how familiar you are with the Tech Stack we endorse.

## Getting Started

* Bootstrap a React or Next Application.
* Push the application to a new public repository named paddle-frontend-assessment on your github remote server.
* Add a README.md file explaining in details the specifications of your application. This should include among others:
  * The libraries and dependecies you used in implementing the application.
  * Step by step guide on how to run the application.
  * What you would like to improve in this application if it was not an assessment.(optional).
* When you are done with the assessment, send the link of the repository to
.https://docs.google.com/forms/d/e/1FAIpQLSdIPZjPB3J-2FCzrpRv5BZ_utA44FiWF01YlaISgpiKQzg-UQ/viewform?usp=sf_link

  

## Task 1 💪
Here is a adobe file with a prototype for a coming soon page.
 https://xd.adobe.com/view/b9ed8245-2809-4b31-a3c4-5c2e76ddb7e8-ecbe/?fullscreen 

In this Task:
* Reproduce the coming soon design prototype in either jsx or tsx and css.
* Display the landing page it via the "/comingsoon" route in your application and the Contact Us should have the same effect as it's on the prototype.
* Display the About Us it via the "/about" route in your application.
* Display the Blog it via the "/blog" route in your application (Not compulsory).
* You are free to use styled components, CSS or any other styling conditions for this page.
* This task will be tested based on the following:
  * Your file and folder structure.
  * Your ability to write clean maintainable code.
  * The responsiveness of your landing page.
  
## Task 2 🧠
This task tests your proficiency in working with REST API and React Frameworks. You'll using the Github api for this task.

In this Task:
* Via the "/github" route. Implement the following:
* List the most starred Github repos that were created in the last 30 days.
* Show the result as a list. One repository per row.
* Show the Following fields in your display: 
  * Repository name,
  * Repository description.
  * Number of stars for the repo.
  * Number of issues for the repo.
  * Username and avatar of the repo owner.
* Implement data pagination with infinite scroll.(optional)

## Things to keep in mind 🚨

* Features are less important than code quality. Put more focus on code quality and less on speed and number of features implemented. 
* Your code will be evaluated based on: code structure, programming best practices, legibility (and not number of features implemented or speed). 
* Your git commit history (and git commit messages) will be also evaluated.

## How to get the data from Github 

To get the most starred Github repos created in the last 30 days (relative to 2021-09-13), you'll need to call the following endpoint : 
`https://api.github.com/search/repositories?q=created:>2021-08-13&sort=stars&order=desc`

The JSON data from Github will be paginated (you'll receive around 100 repos per JSON page). 

To get the 2nd page, you add `&page=2` to the end of your API request : 

Read more about the Github API over [here](https://developer.github.com/v3/search/#search-repositories
).

## Mockups
![alt text](https://raw.githubusercontent.com/hiddenfounders/frontend-coding-challenge/master/mockup.png)

Here's what each element represents :

![alt text](https://raw.githubusercontent.com/hiddenfounders/frontend-coding-challenge/master/row_explained.png)
