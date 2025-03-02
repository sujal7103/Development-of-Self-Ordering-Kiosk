# Food Self-Order Kiosk
Build a Self-Order Kiosk like Macdonalds. In this , the essential tools and skills to a web application for Self-Order Kiosk using React, Context API, and Material UI in the frontend and Node and MongoDB in the backend.
: 
- Material UI to build professional looking web applications
- Themes, Animations, Modals, Boxes, Forms and etc
- React Hooks like useState and useReducer to manage state in single components
- Context API to handle complex states between multiple components
-  Node and Express to build a simple simple and elegant backend
- MongoDB and Mongoose to manage orders in the backend
- Heroku to deploy your web application on cloud servers

Knowing React basics like component, state and props.

## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:basir/self-order-kiosk
$ cd self-order-kiosk
```

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/self-order-kiosk  
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection

### 3. Run Backend

```
$ npm install
$ npm run server
```

### 4. Run Frontend

```
# open new terminal
$ npm start
```

### 5. Seed Sample Data

- Open: http://localhost:5000/api/products/seed
- It creates 9 sample products

### 6. Open App

- Open: http://localhost:3000
