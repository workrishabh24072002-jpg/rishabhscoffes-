═══════════════════════════════════════════════════════════════
  RISHABH'S COFFEE — COMPLETE HEADLESS SHOPIFY WEBSITE
  Ready to deploy to Netlify
═══════════════════════════════════════════════════════════════

STORE DETAILS (already connected):
  Store: rishabhscoffee.myshopify.com
  Token: 894827c544e3458fd0ca049c6fa786f9

PAGES INCLUDED:
  index.html       → Homepage (hero carousel + products)
  products.html    → Shop all coffees (loads from Shopify API)
  product.html     → Product detail + Add to Cart (Shopify API)
  cart.html        → Cart page + Shopify checkout redirect
  about.html       → About Us
  contact.html     → Contact form
  faq.html         → FAQ accordion (10 questions)
  blog.html        → Journal / Blog listing
  article.html     → Individual article page
  terms.html       → Terms of Service
  privacy.html     → Privacy Policy

STEP 1 — ADD YOUR VIDEOS:
  Place your video files in the videos/ folder with these names:
  
  hero-video-1.mp4  → Dark Espresso slide
                      (use: Explosive_coffee_spill video)
  
  hero-video-2.mp4  → French Vanilla slide
                      (use: French_vanilla_overflow video)
  
  hero-video-3.mp4  → Hazelnut Brew slide
                      (use: Coffee_cup_lifting video)
  
  pour.mp4          → "Perfect Pour" split section
                      (use: Extracting_coffee video)
  
  roasting.mp4      → "Masterfully Roasted" section
                      (use: Whisk_kty video)

  Simply rename your video files and drop them into the videos/ folder.

STEP 2 — DEPLOY TO NETLIFY:
  1. Go to netlify.com/drop
  2. Drag the entire rishabhs-coffee-website folder onto the page
  3. Wait 30 seconds — your site is live!
  4. You'll get a URL like: https://amazing-name-123.netlify.app

STEP 3 — TEST YOUR SITE:
  ✓ Click "Add to Cart" on any product
  ✓ Go to cart.html — you should see your item
  ✓ Click "Proceed to Checkout" — this redirects to Shopify checkout
  ✓ Test a purchase using Shopify's test card:
    Card: 1 (in Bogus Gateway test mode)
    Expiry: Any future date
    CVV: Any 3 digits

STEP 4 — ADD YOUR LECTURER:
  Shopify Admin → Settings → Users and permissions
  → Add staff → cara.callaghan@tus.ie → All permissions → Send invite

STEP 5 — REMOVE STORE PASSWORD:
  Shopify Admin → Online Store → Preferences
  → Uncheck "Restrict access to visitors with the password"
  → Save

HOW THE CART WORKS:
  - Click "Add to Cart" on any product page
  - The Shopify Storefront API creates/updates a cart
  - Cart ID is saved in localStorage (persists across pages)
  - Cart page shows all items with +/- quantity controls
  - "Proceed to Checkout" redirects to Shopify's hosted checkout
  - Shopify handles payment, tax, shipping calculations

FOLDER STRUCTURE:
  rishabhs-coffee-website/
  ├── index.html
  ├── products.html
  ├── product.html
  ├── cart.html
  ├── about.html
  ├── contact.html
  ├── faq.html
  ├── blog.html
  ├── article.html
  ├── terms.html
  ├── privacy.html
  ├── css/
  │   └── main.css
  ├── js/
  │   ├── shopify.js
  │   └── carousel.js
  ├── images/
  │   └── (all product + lifestyle images)
  └── videos/
      └── (your video files go here)

Good luck with your assignment! ☕
