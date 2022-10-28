# AMAZONA

# Lessons

1. Introduction

2. Install Tools

3. Create React App

4. Create Git Repository

5. List Products

   1. create products array
   2. add product images
   3. render products
   4. style products

6. Add Routing

   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen

7. Create Node.JS Server

   1. run npm init in root folder
   2. update package.json set type: module
   3. add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start

8. Fetch Products from Backend

   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

9. Manage State By Reducer Hook

   1. define reducer
   2. update fetch data
   3. get state from useReducer

10. Add bootstrap UI Framework

a. npm install react-bootstrap bootstrap
b. update app.js

11. Create Product and Rating Component

a. create rating component
b. create product component
c. use rating component in product component

12. Create Product Details Screen

a. fetch product from backend
b. create 3 columns for image, info and action

13. Create Loading and Message Component

a. create loading component
b. use spinner component
c. create message component
d. create utils.js to define getError function

14. Implement Add to Cart

a. create react context
b. define reducer
c. create store provider
d. implement add to cart button click handler

15. Complete Add to Cart

a. check exist item in cart
b. check count in stock in backend

16. Create Cart Screen

a. create 2 columns
b. display items list
c. create action column

17. Complete Cart Screen

a. click handler for inc/dec item
b. click handler for remove item
c. click handler for checkout