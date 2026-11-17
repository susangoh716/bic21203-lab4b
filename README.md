# BIC21203-Lab 4b-JSON and jQuery

## Student Information

Name: Goh Shu Shan

Student ID: AI240150 

Course: BIC21203 Web Development

## Introduction

This lab focuses on using JSON, JavaScript and jQuery to retrieve data, manipulate HTML elements and handle user interactions.

## Question 1 - Create and Structure JSON Data

Created a JSON file named "books.json" containing two book records.

Each book includes:
- Title
- Author
- Publication Year
- Genres

## Question 2 - Retrieve and Display JSON Data

Used JavaScript "fetch()" to retrieve and read data from "books.json".

Displayed the following information on the webpage:
- First book title
- Second book author
- Genres of both books

Concepts used:
- Fetch API
- JSON parsing
- DOM manipulation
- "createElement()"
- "appendChild()"

## Question 3 - jQuery DOM Manipulation

Used jQuery to perform three DOM manipulation operations:

1. ".text()" - Change the text of an HTML element.
2. ".addClass()" - Add a CSS class to an HTML element.
3. ".on("click")" - Handle button click events.

### Native JavaScript and jQuery Comparison

**Advantage of Native JavaScript:**

Native JavaScript does not require an additional external library, making it lightweight and reducing project dependencies.

**Why an Existing Project May Still Use jQuery:**

An existing project may continue using jQuery if its current code already depends on jQuery methods. This avoids rewriting large amounts of existing code.

## How to Run

1. Open the project folder in Visual Studio Code.
2. Right-click "books.html" and select Open with Live Server.
3. View the book information displayed in Chrome.
4. Open "jquery-dom.html" using Live Server.
5. Test the text modification, CSS class and button click operations.

## Screenshots

### Question 1 - JSON Data

![Q1 JSON](Screenshots/q1.png)

### Question 2 - Display Book Information

![Q2 Screenshot](Screenshots/q2-display.png)

### Question 3 - jQuery DOM Manipulation

![Q3 jQuery](Screenshots/q3.png)

### Question 3 - Button Click Event

![Q3 Alert](Screenshots/q3-%20confirm%20click.png)
