# Fullstack App 2: Momma Knows Pizza

A user-authentication enabled app where you can customize and order a pizza (actual pizzas still under development). You can pick from four different toppings. The app will remember your three most recent unique pizza orders, which you can click to quickly recreate a past order.

![momma-knows-pizza](https://github.com/user-attachments/assets/97ad1669-1b2f-4a9a-86f2-11f3a36e4ad8)

*Screenshot of the pizza making page*

## How It’s Made

**Tech Stack:**  
- **Backend:** Node.js, Express.js, Passport.js (user authentication)
- **Database:** MongoDB, Mongoose
- **Frontend:** EJS, HTML, CSS, JS  

## How It Works
- When a user toggles one of the topping checkboxes, the corresponding topping is added/removed from the toppings array
- Upon clicking the **order** button, an API request with the user ID and the toppings array is sent to the server
- The pizza order is compared to the user's three most recent pizza orders, and if the new order is unique, it is added to the database

## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8080`
3. Create an account

## Inspiration & Credit

README.md layout modified from **CodingWCal**'s template
