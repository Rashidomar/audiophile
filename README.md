# Audiophile e-commerce website

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Add/Remove products from the cart
- Edit product quantities in the cart
- Fill in all fields in the checkout
- Receive form validations if fields are missed or incorrect during checkout
- See correct checkout totals depending on the products in the cart
  - Shipping always adds $50 to the order
  - VAT is calculated as 20% of the product total, excluding shipping
- See an order confirmation modal after checking out with an order summary
-  Keep track of what's in the cart, even after refreshing the browser (`localStorage` could be used for this if you're not building out a full-stack app)

### Built with

- Semantic HTML5 markup
- Flexbox
- Grid
- Mobile-first workflow
- LocalStorage for cart (may be replaced with a CMS or a database in the future)
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [TailwindCSS](https://tailwindcss.com/) - For styling
- [zod](https://zod.dev/) - For form validation
- [react-hook-form](https://react-hook-form.com/) - For form handling


### Setting up the project locally 
- Open your terminal:
  - Clone the project: git clone https://github.com/Rashidomar/audiophile.git
  - npm install
  - npm run dev
You should see output that shows something like this:
Next.js 14.0.1
   - Local: http://localhost:3000

