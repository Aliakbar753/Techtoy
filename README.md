# TechToy - Frontend E-Commerce Project

## Overview
TechToy is a frontend e-commerce project built with HTML, CSS, and JavaScript.  
It includes customer-side shopping features and an admin panel for managing products, categories, and orders.

## Main Features

### Customer Side
- Home page with hero, categories, featured products, testimonials, and contact form
- Product listing page with:
  - Search
  - Sort (name/price)
  - Product cards with stock badges
- Product detail page (`product.html?id=...`)
- Cart sidebar on public pages with:
  - Quantity controls
  - Remove item
  - Running total
  - Live cart count
- Checkout form and order summary
- Orders page with status and cancel option
- Responsive design for desktop, tablet, and mobile
- Mobile bottom navigation (Home, Notifications, Categories, Cart, Account)
- Categories drawer/sidebar opened from navbar and mobile categories button

### Admin Side
- Admin login/logout
- Product CRUD (add, edit, delete)
- Product validation and user feedback messages
- Category management (add/delete with in-use protection)
- Stock management
- Admin order management:
  - Search/filter orders
  - Update status
  - Export CSV
- Admin analytics cards and charts

## Project Pages
- `index.html` - Home
- `products.html` - All products
- `product.html` - Product details
- `checkout.html` - Checkout
- `orders.html` - User orders
- `login.html` - Admin login
- `admin.html` - Admin panel
- `admin-orders.html` - Admin order management

## Tech Stack
- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage (data persistence in browser)
- Chart.js (admin analytics)

## Data Stored in LocalStorage
- `techtoy_products`
- `techtoy_categories`
- `techtoy_cart`
- `techtoy_orders`

## Folder Structure
- `css/` - styles
- `js/` - scripts
- `images/` - assets
- root HTML files for pages

## How to Run
1. Open the project folder in VS Code (or any editor).
2. Run with Live Server or open `index.html` in browser.
3. Use admin login page to access admin features.

## Notes
- This is a frontend-only project (no backend/database API).
- Admin authentication is client-side for demo/learning purposes.
