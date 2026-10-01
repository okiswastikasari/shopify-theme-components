# Shopify Theme Components Setup Guide

This document explains how to install, configure, and use the custom Shopify Online Store 2.0 components included in this repository.

---

# Overview

This project contains custom Shopify theme components built using:

- Shopify Liquid
- Online Store 2.0 Sections
- JavaScript
- CSS
- Product Metafields
- Shopify Cart API

The components are designed for DTC ecommerce brands that require flexible product pages, upsells, cross-sells, recommendations, and conversion-focused storefront features.

---

# Installation

## 1. Upload Theme Files

Copy the following files into your Shopify theme structure:

```
sections/
├── product-recommendations.liquid
├── bundle-builder.liquid
├── sticky-add-to-cart.liquid
└── product-information-tabs.liquid


snippets/
└── product-card.liquid


assets/
├── custom-theme.js
└── custom-theme.css


templates/
└── product.custom.json


config/
└── settings_schema.json
```

---

# Component Overview

## 1. Product Recommendations Section

File:

```
sections/product-recommendations.liquid
```

Purpose:

Creates a dynamic product recommendation carousel based on product tags and assigned collections.

Features:

- Online Store 2.0 section architecture
- Theme Editor configuration
- Product tag matching
- Collection-based recommendations
- Responsive product slider
- Mobile-friendly layout


Example workflow:

```
Product
   ↓
Product Tag
   ↓
Recommendation Collection
   ↓
Recommended Products Section
```

Example:

Product tag:

```
surf shorts
```

Collection:

```
recommended-surf-shorts
```

---

# 2. Bundle Builder Section

File:

```
sections/bundle-builder.liquid
```

Purpose:

Creates product bundles to increase average order value.

Example:

```
BUILD YOUR BEACH SET

Bikini Top
+
Bikini Bottom
+
Accessories

ADD COMPLETE SET
```

Features:

- Product selection blocks
- Multiple product selection
- Cart API integration
- Theme editor configuration
- Conversion-focused shopping experience

---

# 3. Sticky Add To Cart

File:

```
sections/sticky-add-to-cart.liquid
```

Purpose:

Improves product page conversion by keeping the purchase action available while scrolling.

Features:

- Sticky purchase bar
- Product information display
- Variant selection
- Mobile optimized layout
- Quick add-to-cart experience

---

# 4. Product Information Tabs

File:

```
sections/product-information-tabs.liquid
```

Purpose:

Displays dynamic product information using Shopify metafields.

Supported metafields:

## Material

Namespace:

```
custom.material
```

Example value:

```
Recycled Nylon Fabric
```


## Technology

Namespace:

```
custom.technology
```

Example value:

```
UPF 50+ Protection
```


## Care Instructions

Namespace:

```
custom.care
```

Example value:

```
Machine Wash Cold
```


## Features

Namespace:

```
custom.features
```

Example value:

```
Quick Dry
Chlorine Resistant
```

---

# Product Metafield Setup

Create metafields inside Shopify Admin:

```
Settings
↓
Custom Data
↓
Products
↓
Add Definition
```

Recommended definitions:

| Name | Namespace and Key |
|---|---|
| Material | custom.material |
| Technology | custom.technology |
| Care | custom.care |
| Features | custom.features |

---

# Theme Editor Setup

After uploading the components:

Go to:

```
Shopify Admin
↓
Online Store
↓
Themes
↓
Customize
↓
Product Template
```

Add sections:

```
Product Information Tabs

Bundle Builder

Product Recommendations

Sticky Add To Cart
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

# Development Principles

This project follows Shopify Online Store 2.0 development standards:

- Custom Liquid sections
- JSON templates
- Section schema settings
- Merchant editable components
- Reusable snippets
- Dynamic product data
- Responsive ecommerce UX
- Conversion-focused storefront features

---

# Technology Stack

Built with:

- Shopify Liquid
- HTML5
- CSS3
- JavaScript
- Shopify Cart API
- Shopify Metafields
- Shopify Online Store 2.0

---

# Future Improvements

Possible future development:

- Shopify Metaobjects integration
- Advanced bundle discount logic
- Shopify Functions
- Checkout Extensibility
- Storefront API integration
- Product recommendation API
- A/B testing framework

---

# Author

Shopify Theme Developer

Building custom storefront experiences using Shopify Liquid, JavaScript, and Online Store 2.0 architecture.
