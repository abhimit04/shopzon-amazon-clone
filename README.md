# Shopzon — Amazon-style storefront

A single-page, Amazon-style e-commerce UI built with plain HTML, CSS and JavaScript (no dependencies, no build step).

## Features
- Sticky header with delivery location, category-scoped search, account links and live cart count
- Category nav bar and auto-rotating hero carousel
- Overlapping category cards, "Today's Deals" carousel
- Product grid with ratings, MRP / % off, Prime badge, delivery dates and sorting
- Product quick-view modal with Add to Cart / Buy Now
- Slide-out cart with quantity controls, subtotal, free-delivery threshold and demo checkout
- Cart persisted in `localStorage`; responsive layout

Product data is mock data defined in `index.html`.

## Run locally
Open `index.html` directly in a browser, or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```
