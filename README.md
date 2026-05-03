# NextGen Gadgets – Online Tech Store

> A responsive e-commerce website for an Online Tech Gadget Store, built iteratively across four web development tutorials. Starting from a static HTML site with inline CSS, the project evolved through external CSS styling with Flexbox/Grid layouts, and culminated in a fully responsive design using CSS media queries. Features 10+ pages targeting students, gamers, remote workers \& tech enthusiasts. Built with HTML5, CSS3 \& JavaScript.

\---

## Table of Contents

* [Project Overview](#project-overview)
* [Development Journey](#development-journey)
* [Live Pages](#live-pages)
* [Product Catalogue](#product-catalogue)
* [Features](#features)
* [Target Audiences](#target-audiences)
* [Tech Stack](#tech-stack)
* [Folder Structure](#folder-structure)
* [Getting Started](#getting-started)
* [Design Decisions](#design-decisions)
* [Credits](#credits)

\---

## Project Overview

**NextGen Gadgets** is a fully static, multi-page e-commerce website simulating a real online tech retail store. The store is based in Cape Town, South Africa, and sells a curated range of smartphones, tablets, laptops, accessories, and smart home devices sourced from globally recognised brands.

The website was developed across four iterative university tutorials, with each iteration introducing new web technologies, design principles, and levels of polish. The final submission (Tutorial 4) is fully responsive across desktop, tablet, and mobile viewports.

\---

## Development Journey

|Tutorial|Focus|Key Additions|
|-|-|-|
|**Tutorial 1**|Website evaluation \& design theory|Research, wireframing, design planning|
|**Tutorial 2**|Static HTML + Inline CSS|All pages built, basic layout, inline styles|
|**Tutorial 3**|External CSS + Interactivity|Separated CSS file, Flexbox/Grid, hover effects, wishlist prototype, contact form, 2 video clips|
|**Tutorial 4**|Responsive Web Design|CSS media queries, hamburger menu, bottom navigation bar, mobile-first breakpoints|

\---

## Live Pages

The website is fully navigable and comprises the following pages:

|Page|File|Description|
|-|-|-|
|**Home**|`TechStore.html`|Hero video, trust strip, category tiles, best sellers, new arrivals, brands marquee|
|**About Us**|`about.html`|Store history, mission, vision, why choose us, careers section|
|**Categories**|`categories.html`|Overview of the three product categories with navigation tiles|
|**Smartphones \& Tablets**|`smartphones.html`|Product listing for smartphones and tablets|
|**Laptops \& Accessories**|`laptops.html`|Product listing for laptops and accessories|
|**Smart Home Devices**|`smarthome.html`|Product listing for smart home devices|
|**Featured Brands**|`brands.html`|Showcase of all 11 partner brands|
|**Shopping Cart**|`cart.html`|Static cart mockup with item summary and checkout button|
|**Checkout**|`checkout.html`|Shipping form with payment options|
|**Order Confirmation**|`confirmation.html`|Static confirmation page with order number and delivery estimate|
|**Contact Us**|`contact.html`|HTML5 contact form with required fields and placeholders|
|**Account / Login**|`accounts.html`|CSS-only tabbed login and registration form with wishlist access|

### Product Detail Pages

|Page|Product|Price|
|-|-|-|
|`iphone15.html`|iPhone 15|$999|
|`samsungS23.html`|Samsung Galaxy S23|$999|
|`AppleIpad.html`|Apple iPad 10|$599|
|`Asus vivobook.html`|Asus Vivobook|$1,099|
|`airpods.html`|Apple AirPods Max|$549|
|`mouse.html`|Wireless Mouse|$29|
|`fastcharger.html`|Fast Charger|$19|
|`Anker.html`|Anker PowerCore 10000mAh|$49|
|`smartspeaker.html`|Smart Speaker Voice Assistant|$20|
|`smartlightings.html`|Smart LED Motion Sensor|$49|
|`lightbulb.html`|Light Bulb Security Camera|$50|

\---

## Product Catalogue

### Smartphones \& Tablets

* iPhone 15 – $999
* Samsung Galaxy S23 – $999
* Apple iPad 10 – $599

### Laptops \& Accessories

* Asus Vivobook – $1,099
* Wireless Mouse – $29
* Apple AirPods Max – $549
* Fast Charger – $19
* Anker PowerCore 10000mAh – $49

### Smart Home Devices

* Smart Speaker Voice Assistant – $20
* Smart LED Motion Sensor – $49
* Light Bulb Security Camera – $50

\---

## Features

### Navigation \& Layout

* **Responsive header** with three breakpoints: desktop (>1024px), tablet (≤1024px), and mobile (≤853px / ≤600px)
* **Hamburger menu** (CSS-only, no JavaScript) for mobile and tablet views
* **Bottom navigation bar** on mobile, mirroring the primary nav links
* **Active link states** indicating the current page on every page

### Home Page

* **Hero section** with a background video (`Next.mp4`), typewriter heading animation, and a CTA button
* **Trust strip** displaying store rating, products sold, 24/7 support, fast delivery, and secure checkout badges
* **Shop by Category** tiles for the three main categories
* **Best Sellers** and **New Arrivals** product grids with add-to-cart and wishlist buttons
* **Second lifestyle video section** (`All.mp4`) with an overlay CTA
* **Auto-scrolling brands marquee** showcasing 11 partner brands
* **Chatbot button** (UI prototype) in the bottom-right corner

### Product Pages

* Product images, descriptions, and specifications
* Pricing with VAT-included note
* Star rating display
* Customer reviews section
* Add to Cart and Wishlist buttons

### Shopping Flow

* Cart → Checkout → Order Confirmation full navigation flow
* Checkout page includes shipping information form and payment method selection (Visa, Mastercard, PayPal, PayFast, PayFlex, Stripe)

### Forms \& Interactivity

* **Contact form** with HTML5 required fields, placeholders, autofocus, and a submit button
* **Account page** with CSS-only tab switching between Login and Register forms
* **Newsletter subscription** form in the footer (present on all pages)
* **Wishlist buttons** on all product cards (prototype; no backend)

### Styling \& Responsiveness

* Single external stylesheet (`styles.css`, 1,104 lines) linked to all pages
* CSS custom properties (variables) for consistent theming
* Flexbox and CSS Grid used for product grids, category tiles, and footer layout
* CSS media queries for mobile, tablet, and desktop breakpoints
* Page load animations on main sections
* Hover effects on navigation links, buttons, and product cards
* Horizontal scroll with visual fade cue on product grids at smaller viewports

### Footer

* Newsletter subscription input
* Social media icons (Facebook, X, Instagram, TikTok)
* Quick links, category links, and contact details
* Responsive: full 4-column grid on desktop, 2×2 on tablet, condensed on mobile

\---

## Target Audiences

|Audience|How the Site Serves Them|
|-|-|
|**Students**|Affordable accessories (mouse, charger, power bank), budget-friendly smart home items, student-appropriate laptop options|
|**Tech Enthusiasts**|Latest flagship phones (iPhone 15, Galaxy S23), new arrivals section, detailed specs on product pages|
|**Professionals / Remote Workers**|Laptops, peripherals, smart home devices, fast delivery and secure checkout messaging|
|**Content Creators**|AirPods Max, iPad, smart lighting and camera products, brand-name quality guarantees|

\---

## Tech Stack

|Technology|Usage|
|-|-|
|**HTML5**|All page structure and semantic markup (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)|
|**CSS3**|External stylesheet with Flexbox, Grid, custom properties, animations, and media queries|
|**JavaScript**|Minor interactivity (wishlist button feedback, chatbot button)|
|**MP4 Video**|Two embedded autoplay/muted video clips on the home page|
|**No frameworks**|No Bootstrap, Tailwind, React, or any external CSS/JS libraries|

\---

## Folder Structure

```
TechStore1.html/
│
├── TechStore.html          # Home page (entry point)
├── about.html
├── categories.html
├── smartphones.html
├── laptops.html
├── smarthome.html
├── brands.html
├── cart.html
├── checkout.html
├── confirmation.html
├── contact.html
├── accounts.html
│
├── iphone15.html           # Product detail pages
├── samsungS23.html
├── AppleIpad.html
├── Asus vivobook.html
├── airpods.html
├── mouse.html
├── fastcharger.html
├── Anker.html
├── smartspeaker.html
├── smartlightings.html
├── lightbulb.html
│
├── styles.css              # Single external stylesheet (1 104 lines)
│
├── Next.mp4                # Hero video
├── All.mp4                 # Lifestyle video
│
├── \[product images]        # .jpg / .png product and category photos
├── \[brand logos]           # Apple.jpg, Samsung.jpg, Asus.jpg, etc.
├── \[UI icons]              # search.png, user.png, shopping-cart.png, etc.
└── \[payment icons]         # visa.png, mastercard.png, paypal.png, etc.
```

\---

## Getting Started

No build tools or server setup is required. The website is fully static.

1. **Clone or download** this repository.
2. Open the `TechStore1.html/` folder.
3. Open `TechStore.html` in any modern browser (Chrome, Firefox, Edge, Safari).
4. Navigate using the header navigation bar or the bottom navigation bar on mobile.

> \*\*Note:\*\* Videos (`Next.mp4`, `All.mp4`) require the files to be present in the same folder. If they do not play, ensure the video files were included in your download and are not blocked by the browser.

\---

## Design Decisions

* **Colour scheme:** Dark navy/charcoal primary with an electric accent colour to evoke a modern tech aesthetic, consistent with brands like Newegg and Samsung's online store.
* **Typography:** Clean sans-serif fonts prioritising readability across all screen sizes.
* **Layout:** CSS Grid for the product and category tiles; Flexbox for header, footer columns, and card internals — chosen for their native browser support without any dependencies.
* **Responsiveness:** Three-tier breakpoint system (desktop > tablet > mobile) with a dedicated bottom navigation bar replacing the header nav on small screens, following mobile UX conventions used by major e-commerce apps.
* **Accessibility:** All images include `alt` text; form fields include `aria-label` attributes; semantic HTML5 elements used throughout.
* **Ohio State Framework alignment:** Design choices were guided by the OSF principles of usability, accessibility, and goal-directed design — ensuring the site is intuitive for the broad target audience range from students to professionals.

\---

## Credits

* Developed as part of a Web Development course (Tutorials 2–4).
* Product images and brand logos are used for educational purposes only.
* Social media icons (Facebook, X, Instagram, TikTok) are used for layout demonstration purposes.
* Contact: [support@nextgen.co.za](mailto:support@nextgen.co.za) | Cape Town, South Africa | +27 21 123 4567

\---

*© 2026 NextGen Gadgets. All rights reserved.*

