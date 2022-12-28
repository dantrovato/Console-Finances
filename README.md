# Console-Finances

## Overview

This simple app extracts data from a two dimentional array representing the financial records of a fictitious company. Each sub array has a date in the form of a string and an amount represented as a number.

The result is formatted by the function `printResults()`. It uses the rest parameter to pass in any number of arguments. Around this central function are a number of helper functions, each one designed to produce one output.
Finally, on line 138, we log the results of the function. As an added bonus I add the results to the DOM by capturing the target p element and inserting the text which results from calling the `printResults()` function into it.
I also wrapped the whole thing in an IIFE to make sure no local variable clashes with any hypothetical outside code.

<!-- Original ReadMe from the starter folder
In this challenge, you'll be using the concepts you've learned to complete the required activity. This activity presents a real-world situation in which your newfound JavaScript skills will come in handy. You are tasked with creating code for analyzing the financial records of a company. You have been provided with a financial dataset in the `starter/index.js` file.

## Instructions

1. Create a new GitHub repo called `Console-Finances`. Then, clone it to your computer.

2. Copy the starter files in your local git repository.

You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.

Your task is to write JavaScript code that analyzes the records to calculate each of the following:

- The total number of months included in the dataset.

- The net total amount of Profit/Losses over the entire period.

- The average of the **changes** in Profit/Losses over the entire period.

  - You will need to track what the total change in profits are from month to month and then find the average.
  - (`Total/Number of months`)

- The greatest increase in profits (date and amount) over the entire period.

- The greatest decrease in losses (date and amount) over the entire period.

When you open your code in the browser your resulting analysis should look similar to the following:

```text
Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average  Change: $7803.48
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)
```

Your final code should print the analysis to the console.

**Hints:**

- You will need to do some research on your own for this project!

- Remember, in order to combine strings and variables in the console you will need to use **concatenation**.

- How do you only print to the nearest 100th in JavaScript?

## Grading Requirements

This homework is graded based on the following criteria:

### Technical Acceptance Criteria: 40%

- Satisfies all of the above acceptance criteria.

### Deployment: 32%

- Application deployed at live URL.

- Application loads with no errors.

- Application GitHub URL submitted.

- GitHub repository contains application code.

### Repository Quality: 12%

- Repository has a unique name.

- Repository follows best practices for file structure and naming conventions.

- Repository follows best practices for variable naming conventions, indentation, quality comments, etc.

- Repository contains multiple descriptive commit messages.

- Repository contains quality readme with description, screenshot, link to deployed application.

## Review

You are required to submit BOTH of the following for review:

- The URL of the deployed application.

- The URL of the GitHub repository that contains your code. Give the repository a unique name and include a README file that describes the project.

---

## Copyright

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved. -->
