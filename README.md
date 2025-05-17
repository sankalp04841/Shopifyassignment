#  Shopify Liquid Coding Assignment

This project demonstrates Liquid templating skills by customizing the **Dawn** theme in a Shopify development store. All features were implemented using native Liquid logic—no external apps or paid services were used.

---

##  Objective

To assess and showcase proficiency in Shopify’s Liquid templating language by creating dynamic, reusable theme components.

---

## Tasks Completed

### Task 1: Dynamic Product Badge

**File:** `product-card.liquid`

- Shows badges based on price and stock:
  - `Budget Pick` → If product price < ₹500
  - `Limited Stock` → If inventory < 5
  - Displays both if both conditions are true

### Task 2: Custom Collection Filter
 **File:** `collection.liquid`

- Adds a dropdown filter for custom product tags:
  - `best-seller`
  - `new-arrival` → If inventory < 5
  - `discounted`
- Filters the product list based on the selected tag
- Does not interfere with pagination

### Task 3: Personalized Greeting (Homepage)
 **File:** `index.liquid`

- Displays a greeting based on the current time:
  - Before 12 PM → `Good Morning, Shopper!`
  - Between 12 PM – 6 PM → `Good Afternoon, Shopper!`
  - After 6 PM → `Good Evening, Shopper!`

### Task 4: Custom Upsell Section (Cart Page)
 **File:** `cart.liquid`


 - Displays a dynamic upsell product suggestion:
  - If cart total < ₹1000 → Suggest product from `Accessories`
  - If cart total ≥ ₹1000 → Suggest product from `Premium`

### Bonus Task: Buy More, Save More
 **File:** `cart.liquid`

 - Displays a dynamic shipping message:
  - If cart total < ₹500 → `Spend ₹500 more to get free shipping!`
  - If cart total ≥ ₹500 Suggest product from `You’ve unlocked free shipping!`

Files Submitted:
`product-card.liquid`

`collection.liquid`

`index.liquid`

`cart.liquid`




