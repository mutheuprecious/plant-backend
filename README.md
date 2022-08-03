# plant-backend
iPlant is an e-commerce plant shop. User can look for plants, add plants to their cart, add plants to their favorites list and delete from their favorites list. After adding an item to their cart, the user is prompted to either "Checkout" or "Continue Shopping". When selecting the "Checkout" option the user is able to pay with either a credit/debit card or with PayPal.

# Technologies-Used
Ruby on Rails API on the back end
React & Semantic UI on the front-end 
PostgreSQL

# Environment Setup

# Requirements
Ruby 2.7.4
NodeJS (v16), and npm
Heroku CLI
Postgresql

# Rails Setup

To start, cd into a directory where you'd like to create your project. Then run this command to generate a project folder with all the starter code for a new Rails API:

$ rails new example-project -T -d=postgresql --api
-T skips creation of test files
-d=postgresql configures PostgreSQL as the database instead of SQLite
--api configures the app with a limited set of middleware, and skips views/helpers/assets on resource generation.