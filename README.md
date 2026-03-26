# ShopHub – React E-Commerce App

A modern eCommerce web application built with React. Users can browse products, view product details, authenticate, add items to cart, and complete checkout using global state management with Context API.

---

## Features

* Product listing page
* Product details page
* Add to cart functionality
* Cart quantity indicator
* Update item quantity
* Remove items from cart
* Checkout page with order summary
* Authentication (Signup / Login)
* Form validation using react-hook-form
* Global state using Context API
* Dynamic routing with React Router
* Programmatic navigation
* Loading & fallback handling

---

## Tech Stack

* React
* React Router DOM
* Context API
* React Hook Form
* JavaScript (ES6+)
* CSS

---

## Routes

```
/               → Home page
/auth           → Login / Signup
/checkout       → Checkout page
/products/:id   → Product details page
```

---

## React Hooks Used

* useState
* useEffect
* useContext
* useParams
* useNavigate
* useForm

---

## Context API

### AuthContext

* Signup user
* Login user
* Authentication state
* Error handling
* Redirect after login

### CartContext

* Add to cart
* Remove from cart
* Update quantity
* Clear cart
* Calculate total
* Merge cart with products

---

## Pages

### Home Page

* Displays all products
* Uses reusable ProductCard component
* Dynamic rendering using map()

### Product Details Page

* Dynamic routing using useParams
* Displays full product information
* Add to cart with quantity indicator
* Redirect if product not found

### Auth Page

* Signup & Login toggle
* Form validation
* Error handling
* Redirect after authentication

### Checkout Page

* Order summary
* Increase/decrease quantity
* Remove items
* Subtotal calculation
* Total price
* Place order button
* Clear cart after order

---

## Project Structure

```
src/
│
├── components/
│   ├── Navbar.jsx
│   ├── ProductCard.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── Auth.jsx
│   ├── Checkout.jsx
│   ├── ProductDetails.jsx
│
├── context/
│   ├── AuthContext.jsx
│   ├── CartContext.jsx
│
├── data/
│   ├── products.js
│
├── App.jsx
└── main.jsx
```

---

## How It Works

1. Products load on Home page
2. User clicks "View Details"
3. useParams gets product id
4. ProductDetails loads selected product
5. Add to Cart updates global cart
6. Checkout displays cart items
7. User updates quantity or removes items
8. Place Order clears cart

---

## Future Improvements

* Cart persistence with localStorage
* Order history page
* Search products
* Filter by category
* Payment integration
* User profile page
* Protected checkout route

---

## Author

Nischal Shrestha
