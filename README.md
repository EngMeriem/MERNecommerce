1. Manage State By Reducer Hook

   1. define reducer
   2. update fetch data
   3. get state from useReducer (install use-reducer-logger to show actions in console )

2. Add bootstrap UI Framework

   1. npm install react-bootstrap bootstrap react-router-bootstrap
   2. update App.js

3. Create Product and Rating Component

   1. create Rating component
   2. Create Product component
   3. Use Rating component in Product component

4. Create Product Details Screen

   1. fetch product from backend
   2. create 3 columns for image, info and action

5. Create Loading and Message Component

   1. create loading component
   2. use spinner component
   3. craete message component
   4. create utils.js to define getError

6. Create React Context For Add Item To Cart

   1. Create React Context
   2. define reducer
   3. create store provider
   4. implement add to cart button click handler

7. Complete Add To Cart

   1. check exist item in the cart
   2. check count in stock in backend

8. Create Cart Screen

   1. create 2 columns
   2. display items list
   3. create action column

9. Complete Cart Screen

   1. click handler for inc/dec item
   2. click handler for remove item
   3. click handler for checkout

10. Connect To MongoDB Database

    1. create atlas monogodb database
    2. npm install mongoose
    3. connect to mongodb database

11. Seed Sample Products

    1. create Product model
    2. create seed route
    3. use route in server.js
    4. seed sample product

12. Seed Sample Users

    1. create user model
    2. seed sample users

13. Create Signin Backend API

    1. create signin api
    2. npm install jsonwebtoken
    3. define generateToken

14. Complete Signin Screen

    1. handle submit action
    2. save token in store and local storage
    3. show user name in header

15. Create Shipping Screen

    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar

16. Create Sign Up Screen

    1. create input forms
    2. handle submit
    3. create backend api

17. Implement Select Payment Method Screen

    1. create input forms
    2. handle submit

18. Create Place Order Screen

    1. show cart items, payment and address
    2. calculate order summary

19. Implement Place Order Action

    1. handle place order action
    2. create order create api

20. Create Order Screen

    1. create backend api for order/:id
    2. fetch order api in frontend
    3. show order information in 2 cloumns

21. Pay Order By PayPal

    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use PayPalScriptProvider in index.js
    5. use usePayPalScriptReducer in Order Screen
    6. implement loadPaypalScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend

22. Display Order History

    1. create order screen
    2. create order history api
    3. use api in the frontend

23. Create Profile Screen

    1. get user info from context
    2. show user information
    3. create user update api
    4. update user info

24. Publish To Heroku

    1. create and config node project
    2. serve build folder in frontend folder
    3. Create heroku account
    4. connect it to github
    5. Create mongodb atlas database
    6. Set database connection in heroku env variables
    7. Commit and push

25. Add Sidebar and Search Box

    1. add sidebar
    2. add search box

26. Create Search Screen

    1. show filters
    2. create api for searching products
    3. display results

27. Create Admin Menu

    1. define protected route component
    2. define admin route component
    3. add menu for admin in header

28. Create Dashboard Screen

    1. create dashboard ui
    2. implement backend api
    3. connect ui to backend

29. Manage Products

    1. create products list ui
    2. implement backend api
    3. fetch data

30. Create Product

    1. create products button
    2. implement backend api
    3. handle on click
