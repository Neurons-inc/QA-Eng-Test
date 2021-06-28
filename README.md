# Neurons QA Engineering Coding Test
Be sure to read **all** of this document carefully, and follow the guidelines within.

## Context
Our test contains two parts, one for functional test  and the other part is API testing. 

Use Cypress.js to implement the functional test cases. You will be using Trello as the main test application. You are required to set up your own test account and set up a board with To Do, In Progress, on Hold, and Done columns. 

Use Postman to implement the functional test cases. You will be using Tvmaze as the main test application. 

## Requirements
We should be able to run the test suite ourselves, both for cypress but also for load in Postman collection for test the api.


## Test cases 

### Trello with Cypress.js 
Create 10 random fruits name cards 
Add random lipsum in description to the 10 cards
Add add #n of comments on each card 
Move random cards around in the difference columns 
Delete all the fruit cards 
Find the max length of card names
Find the max numbers of cards that can be created 
Delete all cards 

### TV Maze with postman 
Set up a test suit for this public API http://api.tvmaze.com/schedule 
URL: /schedule?country=:countrycode&date=:date
(optional) countrycode: an ISO 3166-1 code of the country; defaults to US
(optional) date: an ISO 8601 formatted date; defaults to the current day
Test cases: USA 15 of aug 2021. United Kingdom 01 of jan 2015
Ensure that the API give correct response based on correct and incorrect formatting 
Find the rate limit policies and validate they are enforced


### Bonus

- Make the application using CI/CD
- Write clear **documentation** on how the test framework was designed and how to run the suit. 
- Provide screenshots and video from the Cypress test cases 
- Describe improvement opportunities when you conclude
- The test cases have been created for multiple browsers and devices. 




## What We Care About
Use any libraries that you would normally use if this were a real QA set up. Be prepared to justify those choices. Please note: _we care more about how you approach the problem than the end result. Code cleanliness and design are more important than using the "right" library._

Here's what you should strive for:

- Good use of current TypeScript, and Cypress framework and Plugin infrastructure. 
- Extensible code
- How ready the code could be to implement in CI/Production environment.
- Thorough explanation of decisions and tradeoffs

## Questionnaire
Please fill out this questionnaire and commit your answers to the repo 
...


## Q&A

> Where should I send back the result when I'm done?

Fork this repo and share a repo with the hiring manager in an email when you think you are done. There is no deadline for this task unless otherwise noted to you directly.

> What if I have a question?

Please write the hiring manager an email with any questions you may have along the way. 
