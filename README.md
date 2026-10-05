🛒 Pick n Cheaper Supermarket — Website & Digital Launch Campaign
A complete, production-ready, single-file responsive website and digital launch campaign dashboard for Pick n Cheaper Supermarket, built with clean semantic HTML5, modern CSS3, and vanilla JavaScript.

📋 Table of Contents
Project Overview

Key Features

JavaScript Interactivity

SEO & Accessibility

Digital Launch Campaign Strategy

File Structure & Setup

Usage Instructions

Technologies Used

🌐 Project Overview
Pick n Cheaper Supermarket is a budget-friendly South African supermarket brand focused on offering essential groceries, fresh bakery goods, butchery meats, and financial/pay-point till services at accessible prices.

This repository/file provides:

Four Connected Pages/Views within a single responsive document (Home, About Us, Products & Services, Contact & Lead Generation).

Four Built-in JavaScript Interactive Tools (Promotional Modal, Dynamic Category Filter, Digital Shopping List, and Mini Savings Calculator).

An Integrated Digital Launch Strategy Panel tailored for small business marketing, community outreach, and social media campaigns.

✨ Key Features
🏢 Web Pages / View Sections
Home Page (#page-home)

Hero banner with clear call-to-action (CTA) buttons.

Highlights of company promises and feature comparison boxes.

Live interactive Mini Savings Calculator section.

About Us (#page-about)

Mission statement, brand story, and core values.

Core differentiators card emphasizing local South African sourcing and transparent low pricing.

Products & Services (#page-products)

Comprehensive catalog across 4 distinct categories.

Integrated Dynamic Product/Category Filter.

Interactive Digital Shopping List Tool for budget planning.

Contact & Lead Generation (#page-contact)

Contact details (toll-free phone, email, head office address).

Interactive contact form with real-time field validation, POPIA consent check, and custom success state.

Digital Launch Campaign Panel (#page-campaign)

Turnkey strategy dashboard featuring target audience personas, multi-channel launch tactics (Meta, Google, WhatsApp, Community Flyers), budget allocation breakdown, and key performance indicators (KPIs).

⚡ JavaScript Interactivity
The webpage incorporates four core client-side interactive modules:

Promotional Modal Popup (#promoModal)

Automatically triggers 2 seconds after initial page load (with smart sessionStorage support to prevent annoyance on refresh).

Features a live 10-minute countdown timer to create urgency for claiming a R50 off digital coupon.

Dynamic Product / Category Filter (filterProducts(category))

Instant filtering across All Items, Fresh Foods & Bakery, Cheaper Value Range, and Pay Point Services.

Smooth transitions without requiring page reloads.

Digital Shopping List (addShoppingItem(), toggleItem(), deleteItem())

Allows users to type item names, select categories, enter estimated prices, and build a custom list.

Real-time calculation of total estimated basket cost.

Checkbox toggle to cross off completed items and one-click clear button.

Mini Savings Calculator (updateSavings())

Live range slider controls for Weekly Grocery Spend (R500 – R5,000) and Expected Savings Percentage (5% – 30%).

Instantly calculates and displays estimated Monthly Savings and Annual Savings in ZAR (R).

🔍 SEO & Accessibility
On-Page SEO: Includes meta tags for description, keywords, viewport settings, Open Graph social cards (Facebook/LinkedIn), and Twitter cards.

Semantic HTML: Built using <header>, <nav>, <main>, <section>, <article>, <aside>, and <footer> tags.

Accessibility (a11y):

Form fields include explicitly linked <label> tags and required attributes.

Buttons use descriptive text or aria-label attributes (e.g., mobile hamburger menu, modal close button).

High contrast color palette compliant with readability guidelines (#D91C24 red on #FFFFFF white).
