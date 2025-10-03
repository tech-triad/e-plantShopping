# Paradise Nursery – E-PlantShopping

A responsive e-commerce front end for a houseplant shop built with React 18, Redux Toolkit, and Vite. The product listing groups plants into multiple categories and supports Add to Cart (button disables while in cart and re-enables if removed). The header shows a live cart count. The cart page includes item thumbnails, unit prices, quantity increment/decrement, delete, per-item subtotals, and a grand total; a Continue Shopping button returns to the catalog and Checkout displays a “Coming Soon” notice. Deployed on GitHub Pages.

## 🌿 Demo

Live Website: [https://rc-15-coder.github.io/e-plantShopping/](https://rc-15-coder.github.io/e-plantShopping/)

## 🛠️ Tech Stack

- **Frontend:** React 18, Vite
- **State Management:** Redux Toolkit, React Redux
- **Styling:** CSS3
- **Deployment:** GitHub Pages (via gh-pages)
- **Other:** ESLint, Apache 2.0 License

## 🚀 Features

- **Landing Page:** Company branding, background image, mission statement, and "Get Started" CTA.
- **Product Catalog:** 
  - At least 6 unique houseplants, displayed in 3+ intuitive categories.
  - Each plant shows image, name, price, and a one-click “Add to Cart” button.
- **Redux Cart Functionality:**
  - Add/remove/increment/decrement plant quantities.
  - Cart state persists during session; badge count updates in real-time.
  - "Added to Cart" disables when already in cart, re-enables if item is removed.
- **Cart Page:**
  - View all items with images, names, price, per-item and total cost.
  - Change quantities or remove items.
  - “Continue Shopping” and “Checkout” actions (checkout: “Coming Soon!” popup).
- **Header:** Always displays company logo, navigation, and cart icon with live badge.
- **Mobile Responsive:** Adapts to all device sizes.

## 📁 Repository Structure

- `src/` – Source code (components, Redux slices, styles)
- `public/` – Static files
- `package.json`, `vite.config.js` – Project config, deployment scripts

## 🏗️ Setup & Local Development

```bash
# Clone the repository
git clone https://github.com/RC-15-coder/e-plantShopping.git
cd e-plantShopping

# Install dependencies
npm install

# Start local server
npm run dev

```
Visit http://localhost:5173/ (default) to view the app locally.

