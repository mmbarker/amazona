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

18. Create Signin Screen

a. create sign in form
b. add email and password
c. add signin button

19. Connect to MongoDB Database

a. create atlas mongodb database
b. install local mongodb database
c. npm install mongoose
d. connect to mongodb database

20. Seed Sample Data

a. create product model
b. create user model
c. create seed route
d. use route in server.js
e. seed sample product

21. Seed Sample Users

a. create user model
b. seed sample users
c. create user routes

22. Create Signin Backend API

a. create signin api
b. npm install jsonwebtoken
c. define generateToken

23. Complete Signin Screen

a. handle submit action
b. save token in store and local storage
c. show username in header

24. Create Shipping Screen

a. create form inputs
b. handle save shipping address
c. add checkout wizard bar

25. Create Sign Up Screen

a. create input forms
b. handle submit
c. create backend api

26. Implement Select Payment Method Screen

a. create input form
b. handle submit

27. Create Place Order Screen

a. show cart items, payment and address
b. handle place orderaction
c. create order create api

28. Implement Place Order Action

a. handle place order action
b. create order create api

29. Create Order Screen

a. create backend api for order/:id
b. fetch order api in frontend
c. show order information in 2 columns

30. Pay Order by PayPal

a. generate paypal client id
b. create api to return client id
c. install react-paypal-js
d. use PayPalScriptProvider in index.js
e. use PayPalScriptReducer in order screen
f. implement loadPaypalScript function
g. render paypal button
h. implement onApprove payment function
i. create pay order api in backend

31. Display Order History

a. create order screen
b. create order history api
c. use api in the frontend

32. Create Profile Screen

a. get user info from context
b. show user information
c. create user update api
d. update user info

33. Publish to Heroku

a. create and config node project
b. serve build folder in frontend folder
c. create heroku account
d. connect it to github
e. create mongodb atlas database
f. set database connection in heroku env variables
g. commit and push

34. Add Sidebar and Search Box

a. add sidebar
b. add searchbox

35. Create Search Screen

a. show filters
b. create api for searching products
c. display results

36. Create Admin Menu

a. define protected route component
b. define admin route component
c. add menu for admin in header

37. Create Dashboard Screen

a. create dashboard ui
b. implement backend api
c. connect ui to backend

38. Manage Products

a. create product list ui
b. implement backend api
c. fetch data

39. Create Product

a. create products button
b. implement backend api
c. handle on click

40. Edit Product

a. create edit button
b. create edit product ui
c. display product info in the input boxes

41. Implement Update Product

a. create edit product backend api
b. handle update click

42. Upload Product Image

a. create cloudinary account
b. use the api key in env file
c. handle upload file
d. implement backend api to upload
