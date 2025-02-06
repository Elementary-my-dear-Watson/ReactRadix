# React Radix

## 📌 Overview
Welcome to **React Radix**, an enhanced e-commerce platform that utilizes Redux for global state management. Originally built with React’s Context API, this refactor integrates Redux to optimize performance, scalability, and maintainability. This project is designed to provide a seamless shopping experience, featuring category-based navigation, a product detail view, a dynamic shopping cart, and Stripe-powered checkout.

## 🎯 Features
- **Redux-powered state management**: Replaces Context API for better scalability.
- **Shopping cart functionality**: Add, remove, and manage products effortlessly.
- **Secure checkout with Stripe**: Test-friendly payment processing.
- **Modern UI/UX**: Responsive and intuitive design.

## 🛠️ Tech Stack
- **Frontend**: React, Redux, TypeScript, React Router
- **State Management**: Redux Toolkit
- **Backend**: Node.js, Express, MongoDB
- **Payments**: Stripe API

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- Node.js 18+
- npm or yarn

### Installation
Clone the repository:
```sh
git clone https://github.com/your-repo/react-radix.git
cd react-radix
```
Install dependencies:
```sh
npm install
# or
yarn install
```
Start the development server:
```sh
npm start
# or
yarn start
```
The app will run on `http://localhost:3000/`.

### Backend Setup
If using a local backend, navigate to the `server` directory and run:
```sh
npm install
npm start
```

## 🔥 Redux Implementation
### Store Setup
Redux is initialized with a global store and reducers:
```tsx
import { configureStore } from '@reduxjs/toolkit';
import rootReducer from './reducers';

const store = configureStore({ reducer: rootReducer });
export default store;
```
### State Access
State is accessed using Redux hooks:
```tsx
const cartItems = useSelector((state) => state.cart.items);
```
### Dispatching Actions
Actions are dispatched via Redux:
```tsx
dispatch(addToCart(product));
```

## 🖼️ Screenshots
**Homepage**
![Homepage](https://i.imgur.com/p31Yln8.png)

**Product Details**
![Product Details](https://i.imgur.com/o0fZb0z.png)

**Shopping Cart**
![Shopping Cart](https://i.imgur.com/p31Yln8.png)

## 👥 Collaborators
- **Martha Watson** - [GitHub](https://github.com/Elementary-my-dear-Watson) - marthacdenzer@gmail.com
- **Jacob Watson** - [GitHub](https://github.com/JakeStair) - jacob.watson00@yahoo.com
- **An Le** - [GitHub](https://github.com/An-109)
- **Justin Moore**

## 📜 License
This project is licensed under the MIT License.

---
**React Radix** is built with a focus on performance, usability, and modern development best practices. Happy coding! 🚀

