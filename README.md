# Food Fusion – Restaurant Website

A responsive, multi-page static website for **Food Fusion**, a fictional restaurant brand. Built with **HTML5**, **CSS3**, and **Vanilla JavaScript**, the project showcases the restaurant's featured dishes, categorized food menu, culinary story, chef profiles, working hours, and an interactive contact page without relying on any backend or external libraries.

---

## Features

### General & Shared UI
- **Consistent Navigation Bar:** Available on all pages (`Home`, `Menu`, `About`, `Contact`) with hover highlight effects and a current-page label.
- **Dark & Orange Theme:** Styled with a unified dark color palette (`#111`, `#1b1b1b`, `#1f1f1f`), orange/gold accents, hover animations, and fixed background overlays.
- **Floating "Back to Top" Button:** Appears smoothly in the bottom-right corner on all pages after scrolling down more than `300px` and scrolls the viewport smoothly back to the top when clicked.

### Home Page (`home.html`)
- **Hero Banner:** Full-width welcome section with a background food image, tagline, and an **Explore Menu** button that navigates to `menu.html`.
- **Featured Dishes:** Highlights signature items (*Margherita Pizza*, *Chicken Cheese Burger*, *Chicken Dum Biryani*, and *Creamy Alfredo Pasta*).
- **Why Choose Food Fusion?:** Showcases key service highlights (fresh ingredients, expert chefs, cozy atmosphere, and fast service).
- **Customer Reviews:** Displays star-rated customer testimonials in styled review cards.

### Menu Page (`menu.html`)
- **Categorized Food Menu:** Organizes **15 menu items** across **6 categories**:
  - **Pizza** (3 items)
  - **Burgers** (2 items)
  - **Biryani** (2 items)
  - **Pasta** (2 items)
  - **Desserts** (2 items)
  - **Beverages** (4 items)
- **Dish Cards:** Each card displays a dish image, title, description, price in INR (`₹`), and interactive **Order Now** and **Add to favourites** buttons with alert feedback.
- **Responsive Grid Layout:** Uses CSS Grid to display 3 columns on desktop screens, 2 columns below `1100px`, and 1 column below `700px`.

### About Page (`about.html`)
- **Brand Overview:** Presents Food Fusion's story, mission, vision, and core values.
- **Meet Our Chefs:** Introduces Chef Daniel, Chef Sarah, and Chef Michael along with their culinary specialties.
- **Restaurant Highlights:** Lists key restaurant milestones and an interactive **Know More** button.

### Contact Page (`contact.html`)
- **Location & Contact Details:** Shows the restaurant address, phone number, clickable `mailto:` email link, and website reference.
- **Working Hours & Live Clock:** Displays weekday/weekend timings, a live digital clock updated every second using JavaScript `Date` and `setInterval()`, and a **Call Restaurant** button.
- **Validated Contact Form:** Includes inputs for Full Name, Email Address, Phone Number, Subject, and Message, with JavaScript validation requiring Full Name and Email Address plus a confirmation dialog on submission.

---

## Technology Stack

- **HTML5** – Multi-page document structure, forms, tables, and inline SVG icon for the Back to Top button
- **CSS3** – Single external stylesheet (`style.css`) using CSS Grid, Flexbox, media queries, transitions, gradients, and fixed backgrounds
- **JavaScript (Vanilla JS)** – DOM manipulation, scroll and click event listeners, smooth scrolling (`window.scrollTo`), form validation, alert/confirm dialogs, and live clock updates (`Date` + `setInterval`)

> **Note:** This is a pure front-end static website—no frameworks, external CSS/JS libraries, build tools, backend servers, or databases are used.

---

## Live Website

This project is not currently hosted or deployed online. You can run and preview it locally on your machine using the setup instructions below.

---

## Installation & Setup

Since this project uses plain HTML, CSS, and JavaScript, no package installation or build step is required.

### 1. Clone the Repository

```bash
git clone https://github.com/Abhilash-KK/Restaurant-project.git
cd Restaurant-project
```

### 2. Run Locally

You can view the website using either of the following methods:

- **Option A: Open directly in a browser**
  - Open `home.html` in any modern web browser (Chrome, Edge, Firefox, etc.) by double-clicking the file.

- **Option B: Run with a local server (recommended)**
  - **Using VS Code Live Server:** Open the project folder in VS Code, right-click `home.html`, and select **Open with Live Server**.
  - **Using Python:**
    ```bash
    python -m http.server 8000
    ```
    Then open `http://localhost:8000/home.html` in your browser.

---

## Project Structure

```text
Restaurant-project/
├── home.html          # Main landing page (hero banner, featured dishes, reviews, footer)
├── menu.html          # Interactive menu page with 6 categories and 15 food cards
├── about.html         # Restaurant story, mission, vision, values, chef profiles, highlights
├── contact.html       # Address, working hours, live clock, and validated contact form
├── style.css          # Shared styles for layout, dark/orange theme, responsive grid, and scroll button
├── README.md          # Project documentation
└── images/            # Image assets (17 PNG files for backgrounds and menu dishes)
    ├── background img.png    # Hero banner background on home.html
    ├── back for about.png    # Fixed page background for menu, about, and contact pages
    ├── pizza1.png            # Margherita Pizza
    ├── pizza2.png            # Pepperoni Pizza
    ├── pizza3.png            # Veggie Supreme
    ├── burger1.png           # Chicken Cheese Burger
    ├── burger2.png           # Veg Burger
    ├── biriyani1.png         # Chicken Dum Biryani
    ├── biriyani2.png         # Mutton Biryani
    ├── pasta1.png            # Creamy Alfredo Pasta
    ├── pasta2.png            # Red Sauce Pasta
    ├── desert1.png           # Chocolate Brownie
    ├── desert2.png           # Cheesecake
    ├── lime.png              # Fresh Lime Juice
    ├── coffee.png            # Cold Coffee
    ├── mojito.png            # Mojito
    └── watermelon.png        # Fresh Watermelon Juice
```

---

## Screenshots

No dedicated screenshots of the rendered web pages are currently included in the repository. Visual dish and background assets used in the website are stored in the `images/` directory.

---

## Author

- **Name:** Abhilash KK
- **GitHub:** [@Abhilash-KK](https://github.com/Abhilash-KK)
- **Email:** kkabhilash30@gmail.com
