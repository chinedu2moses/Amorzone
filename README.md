
01-Website-Template
02-Product-List
03-Sidebar
04-Create-React-App
05-Render-Products-Array
06-Render-Products-Array
07-React-Router-Product-Details
08-Create-Node-Express-Server
09-Fetch-Server-Data-Using-React-Hooks
10-Manage-State-With-Redux
11-Add-Redux-To-Product-Details
12-Shopping-Cart-Screen
13-Connect-to-MongoDB
14-Signin-Users
15-Manage-Products-Screen
1. isAuth token = req.headers.authorization token.slice(7, token.length)
2. Create ProductsScreen.js and add to Add Route to App.js
3. product list
4.  Define State for id, name, brand, category, image, price, countInStock, description
16-Checkout-Wizard-Screen
17-Create-Order
18-Connect-to-Paypal
19-User-Profile
20-Manage-Order-Screen
21-Filter-Sort-Products
22-Deploy-Website-on-Heroku
1. create new App
2. git remote add heroku https://git.heroku.com/myamazona.git
3. Install Heroku CLI
4. heroku login
5. git push heroku master
6. create https://www.mongodb.com/cloud
7. create database and copy connection string
8. add MONGODB_URL to config var of heroku
9. add PAYPAL_CLIENT_ID to config var of heroku
10. Update package.json
11. "build": "rm -rf dist && babel backend -d dist",
12. "heroku-postbuild": "npm run build && cd frontend && npm install && npm run build"
13. "engines": { "node": "12.4.0", "npm": "6.9.0"}
14. Procfile web: node dist/server.js