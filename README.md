Sweet Scoop Ice Cream - Ordering System
A front-end user interface for an ice cream shop ordering system, built with HTML and CSS. This project simulates a complete customer journey from browsing flavors to customizing and reviewing an order.
Features
Homepage:

Shop logo and name in the header.

Navigation bar with links to all pages.

"About Us" section describing the shop.

"Featured Flavors" list (Vanilla Dream, Chocolate Bliss, Strawberry Swirl).

Footer with copyright notice.

Login Page:

Simple login form with username, password, and a "Forgot Password" checkbox.

Login button (non‑functional, but redirects to Menu View when clicked).

Navigation only contains a link back to the homepage.

Menu View:

Dropdown to select the current season (Winter, Fall, Summer, Spring).

Available Flavors section: tiles displaying ice cream name, category, image, description, price range, dietary info, and a link to customize the order.

Seasonal Specials section: tiles with name, image, price, and two non‑functional buttons (Add / Remove).

All tiles arranged in a responsive grid using inline-block.

Customize Order:

Banner image at the top.

Two hardcoded ice cream options:

Vanilla Dream: choose Cup or Cone via radio buttons.

Chocolate Bliss: choose toppings (Sprinkles, Chocolate Syrup, Nuts) via checkboxes.

"Submit Selection" buttons (non‑functional) and a "Finish Order" button that navigates to the Order Summary page.

Order Summary:

Table displaying a completed order with rows for Flavor, Type, Toppings, and Price.

"Edit Order" button (links back to Customize Order) and a non‑functional "Confirm Order" button.

Tech Stack
HTML5 – semantic markup for all pages.

CSS3 – styling using Flexbox, inline‑block layouts, rounded corners, shadows, and custom colour schemes.

No external libraries or frameworks – pure HTML/CSS.

File Organization
text
project-root/
├── index.html               # Homepage
├── login.html                # Login page
├── menu_view.html            # Menu display with tiles
├── customize_order.html      # Order customization page
├── order_summary.html        # Order summary with table
├── styles.css                # Global styles for all pages
├── logo.jpeg                 # Shop logo 
├── Picture1.webp             # ice cream images
└── README.md                 # This file
Note: The image files (logo.jpeg and Picture1.webp) are placeholders. In a real deployment, replace them with actual images.

Getting Started
To view the project locally:

Clone or download the repository to your computer.

Open the index.html file in any modern web browser (Chrome, Firefox, Edge, Safari).

Navigate through the pages using the links in the navigation bar.

No build tools or server are required – it’s a static website.


License
© 2026 Sweet Scoop Ice Cream. For educational purposes only.

