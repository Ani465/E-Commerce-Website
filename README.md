# 🛒 E-Commerce Website

A full-stack e-commerce web application built with **React**, **Redux**, **Firebase**, **Stripe**, and **Express**. This platform delivers a seamless shopping experience with secure authentication, dynamic product management, and real-time order tracking.

## 🚀 Features

- **User Authentication:** Register, login, Google sign-in, and password recovery via Firebase Auth.
- **Admin Panel:** Add, edit, and delete products with role-based access.
- **Product Search & Filtering:** Browse products by category with dynamic filtering.
- **Shopping Cart:** Add/remove items, view cart, and proceed to checkout.
- **Stripe Payments:** Integrated secure payment gateway using Stripe API.
- **Order History:** View past orders and detailed order information.
- **Responsive Design:** Optimized for mobile, tablet, and desktop devices.

## 🧰 Tech Stack

- **Frontend:** React, Redux, Redux-Saga, SCSS
- **Backend:** Firebase Functions (Express), Stripe API
- **Database:** Firebase Firestore
- **Authentication:** Firebase Auth
- **State Management:** Redux, Redux-Persist

## Project Structure

.
├── functions/           # Firebase Cloud Functions (Express backend, Stripe integration)
├── public/              # Static assets and HTML template
├── src/                 # React source code
│   ├── components/      # Reusable UI components
│   ├── customHooks/     # Custom React hooks
│   ├── firebase/        # Firebase configuration and utilities
│   ├── hoc/             # Higher-order components for auth
│   ├── layouts/         # Page layouts
│   ├── pages/           # Route pages (Homepage, Cart, Admin, etc.)
│   ├── redux/           # Redux store, actions, reducers, sagas
│   ├── stripe/          # Stripe payment integration
│   ├── Utils/           # Utility functions
│   ├── assets/          # Images and static assets
│   ├── App.js           # Main app component
│   ├── index.js         # Entry point
│   └── default.scss     # Global styles
├── package.json         # Project dependencies and scripts
├── firebase.json        # Firebase configuration
└── README.md            # Project documentation

## Getting Started

## Installation
1. Clone the Repository:
 
git clone https://github.com/yourusername/ecommerce-website.git
cd ecommerce-website

2. Install Dependencies:
 
npm install
cd functions
npm install
cd ..

3. Configure Firebase:

- Create a Firebase project.
- Add your Firebase config to config.js.
- Update .firebaserc and firebase.json if needed.

4. Configure Stripe:

- Add your Stripe secret key in index.js.

## Running Locally
- Start React app:

npm start

- Start Firebase Functions (backend):

cd functions
firebase emulators:start

- Building for Production

npm run build

## Deployment

- Frontend: Deploy using Firebase Hosting.
- Backend: Deploy Firebase Functions.
