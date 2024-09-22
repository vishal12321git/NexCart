# Nex Cart

[Live on Render](https://nexcart-2.onrender.com)

## Introduction

Nex Cart is an e-commerce platform that allows users to browse products, add them to their cart, and proceed with payments. The platform is powered by a React frontend and a Node.js backend. The application is deployed with the client hosted on Render.


Follow the instructions below to run the project on your local machine.

### Prerequisites

- Node.js
- NPM

### Run the Client ( Frontend )

1. cd client
2. npm install
3. Create a `.env` file in the `client` directory with the following environment variable:
   VITE_API_URL=
4. npm run dev

### Run the Server

1. cd server 
2. npm install
3. Create a `.env` file in the `client` directory with the following environment variable:
   
   - DB_URI=""
   - PORT= 

   - CLIENT_BASE_URL=

   - PAYPAL_MODE='sandbox'
   - PAYPAL_CLIENT_ID=''
   - PAYPAL_SECRET='' 

   - SECRET_KEY=""

   - CLOUDINARY_CLOUD_NAME=
   - CLOUDINARY_API_KEY=
   - CLOUDINARY_API_SECRET=
  
4. npm run dev



## Features

- User authentication and authorization
- Browse products and add them to the cart
- PayPal integration for secure payments
- Cloudinary integration for product image uploads

## Technologies Used

- **Frontend**: React, Vite, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Deployment**: Render, Cloudinary, PayPal
