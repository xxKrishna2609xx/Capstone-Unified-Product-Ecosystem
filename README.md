# Unified Product Experience Ecosystem

A modern, cohesive 5-page frontend web application built purely with **HTML5 and CSS3**, demonstrating multi-role product architecture, responsive design, and a unified design system.

---

## 🚀 Key Highlights & The 5 Pages

1. **`index.html` — Ecosystem Portal & Landing Hub**:
   - Architectural workflow visualizer explaining the relationship between the modules.
   - Dynamic ecosystem KPI counters (Products, Sales, Orders, Wishlist).
   - Module navigators for direct access to Customer, User, and Administrator experiences.
   - Featured product showcase cards.

2. **`catalog.html` — Product Catalog Module**:
   - Filter sidebar with keyword search, category radio selectors (*Audio, Wearables, Electronics, Accessories*), price range slider, and stock availability filter.
   - Multi-column product grid with product images, badges, price tags, and action buttons.

3. **`product-detail.html` — Detailed Product View**:
   - Breadcrumb navigation (`Portal > Catalog > Aura Wireless Headphones`).
   - High-resolution product gallery with status badges (*Flagship Device*, *In Stock*).
   - In-depth technical specifications table (battery life, connectivity, driver size, warranty).
   - Quantity selector UI and customer review breakdown with verified badges.

4. **`dashboard.html` — User Dashboard Module**:
   - Customer profile card with avatar, VIP badge, and key activity metrics.
   - Saved Wishlist section with item previews, prices, and action buttons.
   - Chronological Order History timeline with status badges (*Delivered*, *In Transit*) and itemized receipts.
   - Profile & shipping settings form.

5. **`admin.html` — Admin Operations Console**:
   - Operations KPI cards (Gross Revenue, Active Catalog Items, Total Units in Stock, Low-Stock Warnings).
   - Comprehensive inventory data table with thumbnails, categories, stock levels, and management actions (*View*, *Edit*, *Delete*).
   - Add New Product form styled with responsive CSS grid components.

---

## 🎨 Unified Design System (`css/`)

- **`css/design-system.css`**: Design tokens, color palettes, typography, glassmorphism cards, buttons, badges, and form controls.
- **`css/navbar.css`**: Sticky navigation bar, brand logo, role badges, and responsive menu layout.
- **`css/pages.css`**: Page-specific layouts for the architecture visualizer, catalog filters, product specifications, and dashboard timelines.

---

## 📁 Project Structure

```
Mini-Project 2/
├── index.html            # [Page 1] Portal Gateway & Ecosystem Overview
├── catalog.html          # [Page 2] Product Catalog (Search, Filter, Sort)
├── product-detail.html   # [Page 3] In-Depth Product Specs & Order Flow
├── dashboard.html        # [Page 4] User Profile, Wishlist & Order History
├── admin.html            # [Page 5] Admin Inventory Management & Analytics
│
├── css/
│   ├── design-system.css # Core variables, typography, buttons, badges, cards
│   ├── navbar.css        # Responsive navigation header & role badges
│   └── pages.css         # Page-specific grids, tables, and layouts
│
└── README.md             # Project documentation
```

---

## 💻 How to View the Project

Simply double-click **`index.html`** in your file explorer to open it in any web browser (Chrome, Edge, Firefox, Safari). You can also run a simple local server if preferred:
```bash
python -m http.server 3000
```
Then navigate to `http://localhost:3000`.
