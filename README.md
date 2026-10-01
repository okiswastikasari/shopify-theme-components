# Shopify Theme Components

![Shopify](https://img.shields.io/badge/Shopify-Online%20Store%202.0-green)
![Liquid](https://img.shields.io/badge/Shopify-Liquid-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![CSS](https://img.shields.io/badge/CSS3-Responsive-orange)

Custom Shopify Online Store 2.0 components built with Liquid, JavaScript, and CSS.

This repository contains reusable Shopify theme components designed for DTC ecommerce brands that need flexible storefront experiences, conversion-focused product pages, and merchant-friendly customization.

---

# Overview

This project demonstrates custom Shopify theme development using:

- Shopify Liquid
- Online Store 2.0 Sections
- Section Schema
- JavaScript
- CSS
- Product Metafields
- Shopify Cart API
- JSON Templates


The goal is to create scalable storefront components that can be managed directly through the Shopify Theme Editor without relying on page builders.

---

# Features

## Product Recommendations

File:

```
sections/product-recommendations.liquid
```

A dynamic product recommendation component.

Features:

- Shopify Online Store 2.0 section
- Custom schema settings
- Product tag based recommendation logic
- Collection-based recommendations
- Responsive product carousel
- Mobile optimized layout


---

## Bundle Builder

File:

```
sections/bundle-builder.liquid
```

A product bundle component designed to improve average order value.

Features:

- Product selection blocks
- Multiple product selection
- Cart API integration
- Custom bundle experience
- Theme Editor configuration


Example:

```
Build Your Beach Set

Bikini Top
+
Bikini Bottom
+
Accessories

ADD COMPLETE SET
```

---

## Sticky Add To Cart

File:

```
sections/sticky-add-to-cart.liquid
```

A conversion-focused product purchase component.

Features:

- Sticky purchase bar
- Product information display
- Variant selection
- Quick add-to-cart
- Responsive mobile experience


---

## Product Information Tabs

File:

```
sections/product-information-tabs.liquid
```

A dynamic product information component powered by Shopify metafields.


Supported metafields:

```
custom.material
custom.technology
custom.care
custom.features
```


Example:

```
Material:
Recycled Nylon Fabric

Technology:
UPF 50+ Protection

Care:
Machine Wash Cold
```

---

# Project Structure

```
shopify-theme-components

├── README.md
│
├── sections
│   ├── product-recommendations.liquid
│   ├── bundle-builder.liquid
│   ├── sticky-add-to-cart.liquid
│   └── product-information-tabs.liquid
│
├── snippets
│   └── product-card.liquid
│
├── assets
│   ├── custom-theme.js
│   └── custom-theme.css
│
├── templates
│   └── product.custom.json
│
├── config
│   └── settings_schema.json
│
└── docs
    └── SHOPIFY_SETUP.md
```

---

# Shopify Development Skills Demonstrated

This repository demonstrates experience with:

✅ Shopify Liquid development  
✅ Online Store 2.0 architecture  
✅ Custom sections and blocks  
✅ Theme schema configuration  
✅ Product metafields  
✅ JSON templates  
✅ Dynamic storefront components  
✅ Responsive ecommerce UX  
✅ Conversion-focused development  


---

# Installation

For installation and configuration guide:

See:

```
docs/SHOPIFY_SETUP.md
```

---

# Use Cases

Designed for:

- Fashion ecommerce
- Swimwear brands
- Beauty brands
- Lifestyle DTC stores
- Shopify Plus storefront customization


---

# Development Approach

All components are built with:

- Reusable Liquid architecture
- Merchant editable settings
- Lightweight JavaScript
- Responsive CSS
- Shopify native functionality


---

# Future Improvements

Planned extensions:

- Shopify Metaobjects integration
- Advanced bundle discounts
- Shopify Functions
- Checkout Extensibility
- Storefront API integration
- Advanced recommendation engine
- A/B testing components


---

# Author

Shopify Theme Developer

Building custom storefront experiences using Shopify Liquid, JavaScript, and Shopify Online Store 2.0.
