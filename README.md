# Eatly - A Premium Food Ordering Platform

## Overview
Eatly is a modern **food ordering platform** that connects users with top restaurants and high-quality dishes. With an elegant user interface, seamless navigation, and smooth ordering experience, Eatly ensures users can enjoy meals from around the world effortlessly.

## Features
✔️ **Responsive & Modern UI** - Sleek design optimized for all devices.
✔️ **Restaurant Listings** - Discover top-rated restaurants.
✔️ **Menu Browsing** - Explore high-quality dishes with ratings and pricing.
✔️ **Authentication System** - Users can log in or sign up.
✔️ **Interactive UI Components** - FAQ section, sliders, and buttons.
✔️ **Multi-section Navigation** - Quickly move between home, app, menu, and FAQs.
✔️ **Real-Time Order Status** (Future Enhancement).

## Installation & Setup
### Requirements:
- A modern web browser (Chrome, Firefox, Safari, Edge).
- A web server (optional for testing locally).

### Running Locally:
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/eatly.git
   ```
2. Navigate into the project folder:
   ```sh
   cd eatly
   ```
3. Open `index.html` in your browser or start a local server:
   ```sh
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000/` in your browser.

## Folder Structure
```
Eatly/
│── index.html         # Main HTML file
│── style.css          # Main CSS file
│── imgs/              # Contains images used in the project
│── README.md          # Documentation
└── js/                # (Future) JavaScript files for dynamic functionality
```

## Code Breakdown
### **Navbar** - Navigation for a seamless user experience
```html
<nav class="navbar">
    <div class="wrapper">
        <a class="navbar-brand" href="#">
            <img src="imgs/Logo.png" alt="Logo" class="d-inline-block align-text-top"> eatly
        </a>
    </div>
</nav>
```
