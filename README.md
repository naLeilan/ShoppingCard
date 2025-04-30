# 🛒 Shopping Cart

🧩 Overall Concept
A Shopping Cart allows users to browse products, add them to a cart, view their cart, adjust quantities, and see the total cost.

---

### 🔧 Core Features

1. Product List
   • Show a grid or list of products
   • Each product has:
   o Name
   o Price
   o Image
   o “Add to Cart” button
2. Shopping Cart
   • Appears in a sidebar or modal
   • Displays:
   o List of added items (name + quantity + price)
   o Total cost
   o “Remove” or “Update Quantity” buttons
   • “Checkout” button (optional)
3. State Management
   • products: List of available products (static or fetched)
   • cartItems: State for items in the cart (array of { id, name, price, quantity })
4. Reusability + Component Structure
   • App
   o ProductList
    ProductCard
   o Cart
    CartItem
   o CartButton (toggle cart view)
5. UX Enhancements
   • Show message: “Cart is empty” if no items
   • Disable "Add to Cart" if item already in cart (optional)
   • Quantity selector (+/- buttons)
   • Confirmation toast/snackbar on add/remove (optional)

---

### 🌟 Bonus (Advanced/Optional)

• Persist cart in localStorage
• Sort/filter products (by price, name)
• Use context or Redux to manage state across deeply nested components
• Dark/light mode
• Currency formatting (Intl.NumberFormat)

---

### 🧠 Concepts You’ll Practice

• useState, useEffect
• Conditional rendering
• Props and state lifting
• Reusable components
• Forms and input handling
• Dynamic list rendering
• Optional: Context API or Redux

### 🧠 Key Features to Consider for Your Mini Shopping Cart App

Based on the examples and inspirations above, here are some features you might want to implement:
• Product Listing: Display products with images, names, prices, and "Add to Cart" buttons.
• Cart Overview: Show a summary of selected items, quantities, and total price.
• Quantity Adjustment: Allow users to increase or decrease item quantities directly in the cart.
• Remove Items: Enable users to remove items from the cart.
• Responsive Design: Ensure the cart is accessible and functional on various devices.
• Checkout Process: Provide a clear and straightforward path to complete the purchase.
• Promotional Messages: Display messages like "Free shipping on orders over €50" to encourage higher spending.
• Persistent Cart: Use local storage to retain cart items between sessions.
