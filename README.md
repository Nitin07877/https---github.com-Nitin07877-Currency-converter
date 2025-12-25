Currency Converter

A simple and user-friendly Currency Converter web application that converts one currency into another using real-time exchange rates. This project is built using HTML, CSS, and JavaScript, with a separate data file for country and currency codes.

 Features

Convert between multiple international currencies

Real-time exchange rate conversion

Uses Frankfurter API (no API key required)

Currency & country data stored in codes.js

Responsive and clean UI

 Tech Stack

HTML – Structure of the application

CSS – Styling and layout

JavaScript – Logic, API integration, DOM manipulation

📂 Project Structure
currency-converter/
│
├── index.html
├── style.css
├── script.js
├── codes.js   // Contains country & currency code data
└── README.md

 How It Works

User enters the amount to convert

Currency options are populated using codes.js

User selects From and To currencies

App fetches real-time exchange rates from the API

Converted amount is displayed instantly

 API Used – Frankfurter API

This project uses the Frankfurter Exchange Rate API to fetch real-time currency conversion rates.

 Why Frankfurter API?

Free and open-source

No API key required

Simple and fast JSON responses

Supports multiple currencies

 API Endpoint Used
https://api.frankfurter.app/latest?from=USD&to=INR

 Sample Response
{
  "amount": 1,
  "base": "USD",
  "date": "2025-12-05",
  "rates": {
    "INR": 89.94
  }
}


base → Source currency

rates → Target currency & conversion rate

date → Last updated date

 Installation & Usage

Clone the repository

git clone https://github.com/your-username/currency-converter.git


Navigate to the project folder

cd currency-converter


Open index.html in your browser

 Learning Outcomes

API integration using JavaScript

Working with external data files (codes.js)

DOM manipulation & event handling

Building a real-world frontend project

 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

📜 License

This project is licensed under the MIT License.
