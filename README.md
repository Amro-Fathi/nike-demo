👟 Nike — Interactive Product Showcase

<p align="center">
  <strong>A dynamic Nike-inspired shopping experience built with HTML, CSS, and JavaScript.</strong>
  <br />
  Explore products, switch between shoe collections, manage favourites, and interact with a custom shopping interface.
</p><p align="center">
  <a href="https://amr-sudu7.github.io/nike-demo/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Explore_Nike-ea580c?style=for-the-badge" alt="Live Demo" />
  </a>
  <a href="https://github.com/Amro-Fathi/nike-demo">
    <img src="https://img.shields.io/badge/💻_Source_Code-GitHub-181717?style=for-the-badge&logo=github" alt="Source Code" />
  </a>
</p><p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=222" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/LocalStorage-Storage_API-64748b?style=flat-square" alt="Local Storage" />
</p>---

✨ Overview

Nike Demo is a front-end shopping website inspired by Nike's product presentation and visual identity.

The project combines a bold, image-focused design with interactive JavaScript functionality. Visitors can explore a rotating hero showcase, browse product collections, open product details, and interact with shopping and favourites interfaces.

The main goal was to go beyond a simple landing page by creating a more dynamic experience using vanilla JavaScript, browser storage, reusable functions, and custom UI interactions.

🚀 Live Preview

"Open the Nike Demo →" (https://amr-sudu7.github.io/nike-demo/)

🔥 Features

- Interactive hero carousel — cycle through different shoe presentations with coordinated imagery and visual themes.
- Dynamic product sections — display the latest and featured products using JavaScript-generated content.
- Product details popup — inspect an individual product in a dedicated overlay.
- Shopping interface — open a custom shop popup to explore selected products.
- Favourites system — manage favourite products through a separate interface.
- Browser-based persistence — use Local Storage to retain supported application data across page reloads.
- Login interface — access a custom login popup from the navigation.
- Product search interface — open the search field and interact with the product-search UI.
- Responsive navigation — navigate between the main sections with a collapsible Bootstrap navbar.
- Custom loading screen — display a branded loading popup while the page initializes.
- Responsive styling — adapt the layout for different viewport sizes.
- Animated UI — use custom JavaScript and CSS effects to enhance transitions and interactions.

🎨 Design & User Experience

The visual direction is inspired by Nike's bold sportswear aesthetic, with large shoe imagery, prominent typography, and product-focused sections.

The interface is organized around a few key experiences:

🏁 Hero Showcase

The opening section features a carousel with different shoe color variations. Navigation controls let visitors switch between slides while exploring the featured product presentation.

👟 Product Collections

The Latest Products and Featured Products sections organize product content into dedicated areas. JavaScript handles the generation of product elements, keeping the page structure separate from much of the content.

🪟 Custom Popup System

Rather than navigating away from the main page for every interaction, the website uses overlays for product details, shopping, favourites, and login.

This creates a more cohesive experience while providing a foundation for reusable interaction logic.

🧠 JavaScript & Application Logic

JavaScript is central to the project. The interface uses dedicated scripts to separate product data, shared functionality, page interactions, and animations.

File| Responsibility
"js/shoes.js"| Product data used by the application
"js/functions.js"| Shared functions and reusable UI behavior
"js/index.js"| Main page interactions and interface logic
"js/animation.js"| Animation-related behavior

Why this structure matters

- Separation of concerns — product data, shared functions, and page-specific interactions are kept in separate files.
- Dynamic rendering — product cards and related interface content can be generated with JavaScript.
- Reusable logic — common operations can be shared across multiple UI components.
- State persistence — Local Storage provides browser-side persistence for supported application state.
- Event-driven interactions — user actions trigger updates to the relevant interface elements.

These concepts are useful foundations for building larger front-end applications without immediately introducing a framework.

🛠️ Tech Stack

Technology| Purpose
HTML5| Semantic page structure
CSS3| Custom layouts, styling, and responsive design
JavaScript (ES6+)| Application logic, dynamic rendering, and interactions
Bootstrap| Responsive grid, navigation, and UI utilities
Local Storage| Client-side persistence
Font Awesome| Interface icons
Custom CSS animations| Visual transitions and interaction effects

📁 Project Structure

nike-demo/
├── css/
│   ├── all.min.css
│   ├── bootstrap.css
│   ├── font.css
│   ├── global.css
│   ├── index.css
│   └── index.responsive.css
├── images/
│   └── # Product images, banners, and visual assets
├── js/
│   ├── bootstrap.js
│   ├── shoes.js
│   ├── functions.js
│   ├── index.js
│   └── animation.js
├── webfonts/
└── index.html

💻 Run Locally

You can run the website locally without installing a JavaScript framework or package manager.

1. Clone the repository

git clone https://github.com/Amro-Fathi/nike-demo.git

2. Enter the project directory

cd nike-demo

3. Start a local server

If Python is installed, run:

python -m http.server 8000

4. Open the website

Visit "http://localhost:8000" (http://localhost:8000) in your browser.

A local server is recommended for consistent asset loading and browser behavior.

📚 What I Learned

This project explores several practical front-end development concepts:

- Manipulating the DOM to build dynamic interfaces.
- Organizing JavaScript into separate files with distinct responsibilities.
- Working with browser Local Storage.
- Implementing carousel and popup interactions.
- Managing product-oriented UI state.
- Building responsive layouts with CSS and Bootstrap.
- Creating visual effects with CSS and JavaScript.
- Connecting user actions to updates in the interface.

The most interesting part is combining these concepts into a cohesive experience without relying on a front-end framework.

⚠️ Project Scope

This is a front-end demonstration project inspired by Nike's website. It is not an official Nike product or a production e-commerce platform.

Browser storage provides client-side persistence; it does not provide a shared database or secure user authentication. Real payments, inventory management, and backend account services are outside the scope of this demo.

👨‍💻 Author

Amr Fathi

- GitHub: "@Amro-Fathi" (https://github.com/Amro-Fathi)
- Repository: "nike-demo" (https://github.com/Amro-Fathi/nike-demo)
- Live Demo: "Nike Website" (https://amr-sudu7.github.io/nike-demo/)

---

<p align="center">
  <strong>Designed to explore. Built to interact.</strong>
  <br />
  <sub>A front-end project focused on product presentation, JavaScript, and user experience.</sub>
</p>
