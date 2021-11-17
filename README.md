# iOS Technical test

## Introduction

Thanks for applying for a development role at Fatsoma. To give us a good
indication of programming ability and style please submit your solution for
this iOS technical problem.

This is not a timed test, but you do not need to spend more than a couple of
hours on this. A partial solution is still very useful, and you can describe
your thoughts for next steps that would be taken.

Your submission must be your own work.

## Problem definition

We would like you to develop a iOS application consisting of a single infinitely loading list pulled from our main events [API](https://api.fatsoma.com/v1/events). The Fatsoma API is based on the [JSONAPI](https://jsonapi.org/) specification and supports various includes such as Location, Page

The app should display an appropriate UI to indicate to the user that it is busy while it fetches results from the API. If the API request fails it should display an error message and a “Try Again” button which can be used to retry the API call. 

The list item should display a minimum of   
- Event name  
- Location  
- Start date  

Technical requirements 
- Swift
- Use of an appropriate technical approach/design pattern 
- Feel free to use 3rd party libraries where appropriate 

You should also include whatever tests you feel are appropriate for the application and comments explaining your decisions and any improvements you would make given more time.

### Assessing the exercise will involve  
- Cloning your git repository and opening the project in Xcode.  
- Checking your code is well structured and free from errors.   
- Building your project and testing it in the iOS simulator.  
- Examining and running any tests.   
