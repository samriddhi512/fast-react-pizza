# 🍕 Fast React Pizza

---
A modern, full-featured pizza ordering web application built with React, Redux Toolkit, and React Router. Order your favorite pizzas with a smooth, intuitive user experience.


## 🎥 DEMO (CLICK TO WATCH)
👉👉👉 **[WATCH THE DEMO VIDEO](https://drive.google.com/file/d/1oo-bcCLDVRkTGdntFAO1yxIsyXgLaB6C/view?usp=drive_link)**

---


## ✨ Features

- **Menu Browsing**: Browse through a delicious selection of pizzas with detailed information
- **Shopping Cart**: Add items to cart, update quantities, and remove items
- **Order Management**: Create and track orders with customer information
- **User Authentication**: Simple username-based authentication
- **Priority Orders**: Option to prioritize your order for faster delivery
- **Order Tracking**: View order details and status
- **Form Validation**: Phone number and address validation
- **Responsive Design**: Beautiful, modern UI built with Tailwind CSS

## 🛠️ Tech Stack

- **React 18** - UI library
- **Redux Toolkit** - State management
- **React Router v6** - Client-side routing with data loaders and actions
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **ESLint** - Code linting
- **Prettier** - Code formatting

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd 16-fast-react-pizza
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

## 🚀 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the app for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## 📁 Project Structure

```
src/
├── features/          # Feature-based modules
│   ├── cart/         # Shopping cart functionality
│   ├── menu/         # Menu display and items
│   ├── order/        # Order creation and tracking
│   └── user/         # User authentication
├── services/         # API service functions
│   ├── apiGeocoding.js
│   └── apiRestaurant.js
├── ui/               # Reusable UI components
│   ├── AppLayout.jsx
│   ├── Button.jsx
│   ├── Error.jsx
│   ├── Header.jsx
│   ├── Home.jsx
│   └── LinkButton.jsx
├── utils/            # Utility functions
├── App.jsx           # Main app component with routing
├── main.jsx          # Application entry point
├── store.js          # Redux store configuration
└── index.css         # Global styles
```

## 🎯 Key Features Explained

### Menu
- Browse all available pizzas
- View pizza details including name, ingredients, and price
- Add pizzas to cart directly from the menu

### Shopping Cart
- View all items in your cart
- Update item quantities
- Remove items from cart
- See cart total and item count
- Proceed to checkout

### Order Creation
- Enter customer information (name, phone, address)
- Phone number validation
- Optional priority ordering
- Automatic cart clearing after successful order

### Order Tracking
- View order details by order ID
- See order status and estimated delivery time
- Track previous orders

## 🌐 API

This application uses the Fast Pizza API hosted at:
```
https://react-fast-pizza-api.jonas.io/api
```

The API provides endpoints for:
- `GET /menu` - Fetch menu items
- `GET /order/:id` - Get order details
- `POST /order` - Create a new order
- `PATCH /order/:id` - Update an existing order

## 🎨 Styling

The application uses Tailwind CSS for styling, providing:
- Responsive design that works on all screen sizes
- Modern, clean UI
- Consistent color scheme and typography
- Smooth user experience

## 📝 Development Notes

- The app uses React Router's data loaders and actions for server-side data fetching and form submissions
- Redux Toolkit is used for managing cart and user state
- Form validation is handled both client-side and server-side
- Error boundaries are implemented for better error handling

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.
