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
### **Main Page** - Hero Section
```html
<div class="main-page" id="home">
    <h1 class="header">Enjoy Foods All Over The World</h1>
    <p class="usual-text">EatLy helps you set saving goals and order from premium restaurants.</p>
</div>
```
### **Menu Section** - Displaying Top Restaurants
```html
<div class="menu-rests" id="menu">
    <h2 class="medium-header"> Our Top Restaurants </h2>
    <div class="menucontainer">
        <div class="rests-item">
            <img src="imgs/RestImage1.png">
            <h3 class="small-header"> The Chicken King </h3>
        </div>
    </div>
</div>
```
## Technologies Used
- **HTML** - Structuring the application.
- **CSS** - Styling and making the UI responsive.
- **JavaScript** (Future Enhancements) - Dynamic interactions and real-time updates.

## Future Enhancements
🚀 **User Authentication** - Enable login/signup functionality.
📱 **Mobile App Integration** - Extend Eatly to iOS and Android.
📦 **Cart & Checkout System** - Allow users to add items to a cart and place orders.
