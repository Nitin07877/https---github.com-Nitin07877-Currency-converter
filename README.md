Currency Converter

A simple and user-friendly Currency Converter web application that converts one currency into another using real-time exchange rates. This project is built using HTML, CSS, and JavaScript, with a separate data file for country and currency codes.

Project Features

Convert between multiple international currencies

Real-time exchange rate conversion

Uses Frankfurter API with no API key required

Country and currency data stored in a separate file called codes.js

Clean and responsive user interface

Tech Stack

HTML
Used for structuring the application

CSS
Used for styling and layout

JavaScript
Used for logic, API integration, and DOM manipulation

Project Structure

currency-converter
index.html
style.css
script.js
codes.js (contains country and currency code data)
README.md

How the Application Works

The user enters the amount to convert

Currency options are loaded from codes.js

The user selects the source and target currencies

The app fetches live exchange rates from the API

The converted amount is displayed on the screen

API Used

Frankfurter Exchange Rate API

This project uses the Frankfurter API to fetch real-time currency exchange rates. The API is free to use and does not require an API key.

API Endpoint Example

https://api.frankfurter.app/latest?from=USD&to=INR

Sample API Response

{
"amount": 1,
"base": "USD",
"date": "2025-12-05",
"rates": {
"INR": 89.94
}
}

Explanation
base represents the source currency
rates contain the converted currency value
date shows the last update date

Installation and Usage

Clone the repository
git clone https://github.com/your-username/currency-converter.git

Open the project folder

Open index.html in your browser

Learning Outcomes

Understanding API integration in JavaScript

Working with external JavaScript data files

DOM manipulation and event handling

Structuring a real-world frontend project

Contributing

Contributions are welcome.
Fork the repository and submit a pull request.

License

This project is licensed under the MIT License.
