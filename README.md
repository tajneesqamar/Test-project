# Deadline
This Task is due on 17th October 2022


# Task
To better assess a candidates development skills, we would like to provide the following challenge.

# Project description
# FrontEnd 
We want to develop a small web app that allows users to order pizza.

This client will interface with the API built in the backend portion of the challenge.

First of all we'll display the list of pizzas with ingredients and prices. Data will be loaded from /api/pizzas.

When the user chooses something from the list the order summary will update dynamically.

There will be a button to confirm the order. An ajax call will be performed to /api/order and the result will be displayed as a message like this: "Your order is cofirmed. Order summary: ...".

# Backend
This application serves the purpose of exposing a JSON API to be consumed by a frontend client for ordering pizza.

The following entities should be created (including proper relations):

pizza - has a name and price (e.g. Margherita $5, Pepperoni $6, ...)
order - has items
order item - has a pizza and quantity
The following endpoints should return a JSON response:
* /api/orders (list of orders)
* /api/orders/:id (details of an individual order)
* /api/pizzas (list of pizzas; see './backend/example-pizzas.json')


# Delivery
You must fork this repository and commit the solution in the solution folder. Your repository must be public. After that, send the repository link.
