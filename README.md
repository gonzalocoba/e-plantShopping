# e-plantShopping

**Paradise Nursery** — a React + Redux Toolkit shopping cart application for an online houseplant shop.

## Overview

This project is the final assignment for the IBM "Developing Front-End Apps with React" course. It implements a small e-commerce experience built with React and Redux Toolkit:

- **Landing page** with a welcome message and a "Get Started" button.
- **Product listing page** that groups houseplants into multiple categories (Air Purifying, Aromatic, Insect Repellent, Medicinal, Low Maintenance). Each plant card shows a thumbnail, name, description, price, and an "Add to Cart" button.
- **Shopping cart page** that lets the user increment/decrement quantities, remove items, view per-item subtotals and the cart grand total, continue shopping, or hit a placeholder checkout.
- **Navbar with a live cart icon** that reflects the total number of items currently in the cart.

## Tech stack

- React 18 (functional components + hooks)
- Redux Toolkit + react-redux for global cart state
- Vite as the build tool

## Run locally

```bash
npm install
npm run dev
```

Then open the URL printed in the terminal (usually http://localhost:5173).

## Build for production

```bash
npm run build
npm run preview
```
