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

**Logic Used:**  
```liquid
{% if product.price < 500 %}
  <span class="badge">Budget Pick</span>
{% endif %}
{% if product.variants.first.inventory_quantity < 5 %}
  <span class="badge">Limited Stock</span>
{% endif %}


