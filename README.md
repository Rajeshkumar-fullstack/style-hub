# StyleHub – Online Clothing Store Website

A modern, commercial fashion store website built with **HTML5** and **CSS3** as part of the Commercial Website Mini Project Assignment.

---

## 🌟 Project Highlights & Features

- **Website Branding:** Clean and elegant branding for **StyleHub**.
- **Responsive Navigation Bar:** Fixed / sticky navbar with links to **Home**, **About**, **Products**, and **Contact**, featuring a pure CSS responsive hamburger menu for mobile devices.
- **Hero Section:** Full-bleed hero banner with a high-resolution fashion background image, overlay gradient, title, descriptive copy, and a prominent **"Shop Now"** call-to-action button.
- **Curated Product Showcase:** CSS Grid layout displaying **6 distinct clothing products**:
  1. *Classic Denim Jacket* (Outerwear)
  2. *Casual Linen Shirt* (Shirts)
  3. *Floral Summer Wrap Dress* (Dresses)
  4. *Urban Streetwear Hoodie* (Streetwear)
  5. *Slim-Fit Chino Pants* (Bottoms)
  6. *Minimalist Wool Overcoat* (Coats)
  - Every product card features high-quality fashion imagery, category tags, product title, description, formatted pricing, and an interactive **"Buy Now"** button.
- **About Us Section:** Two-column split layout detailing the brand's heritage, sustainability pledge, experience metric badge, and value propositions.
- **Contact Us Section:** Complete contact portal with input fields for **Full Name**, **Email Address**, and **Message**, alongside boutique address, phone support, and opening hours.
- **Footer:** Brand summary, quick navigation links, customer service links, newsletter subscription, social media channels, and copyright statement.

---

## 🛠️ Technology & CSS Requirements Checklist

| Requirement | Implementation Detail |
|---|---|
| **External CSS File** | Linked via `<link rel="stylesheet" href="style.css">` |
| **Class & ID Selectors** | IDs (`#main-header`, `#home`, `#about`, `#products`, `#product-list`, `#contact`, `#contact-form`, `#main-footer`, etc.) and Classes (`.navbar`, `.hero-title`, `.btn`, `.btn-primary`, `.product-card`, `.product-grid`, etc.) |
| **Background Images & Colors** | Hero section uses `background-image: url(...)` with dark gradient overlay, along with theme colors (`#1e293b`, `#c28b5e`, `#f8fafc`, `#ffffff`) |
| **Flexbox & Grid** | CSS Grid used for the product catalog (`grid-template-columns: repeat(3, 1fr)`); Flexbox used for navbar, hero actions, feature bar, card rows, and footer |
| **Margin, Padding & Borders** | Standardized box model, section vertical padding, card borders, rounded corners, and input borders |
| **Hover Effects** | Interactive transitions on cards (`translateY(-8px)`, box-shadow elevation, image zoom `scale(1.06)`) and buttons (`translateY(-2px)`, shadow glow) |
| **Responsive Media Queries** | Breakpoints at `992px` (tablets), `768px` (mobile hamburger menu & single/double column switch), and `480px` (small mobile devices) |

---

## 📂 File Structure

```text
CSS MINI PROJECT/
├── index.html     # Semantic HTML5 markup
├── style.css      # External CSS3 stylesheet with variables & media queries
└── README.md      # Project documentation
```

---

## 🚀 How to Open and View

1. Double click on `index.html` to open it in your default web browser (Chrome, Edge, Firefox, Safari).
2. Alternatively, right click `index.html` and select **Open with** &rarr; choose your preferred browser.
3. Resize the browser window or use Developer Tools (F12 &rarr; Toggle Device Toolbar) to test tablet and mobile screen responsiveness.
