# SubDupes - Waitlist Landing Page

![Project Status: In Development](https://img.shields.io/badge/status-in%20development-blueviolet) ![Technology: HTML/CSS/JS](https://img.shields.io/badge/tech-HTML%2F%2F%2FCSS%2FJS-brightgreen)

This repository contains the official waitlist landing page for **SubDupes**, a privacy-first subscription manager.

---

### ⚠️ Don't Forget!
**Before you make this repo public, add a screenshot of the landing page here!**
![SubDupes Landing Page Screenshot](httpsExample-Screenshot.png) 
*(Replace `Example-Screenshot.png` with a real image of your page)*

## 🚀 About The Project

**SubDupes** is a forthcoming SaaS product designed to help users find, track, and cancel their recurring subscriptions and "shadow charges."

Its primary competitive advantage is a **privacy-first model**. Unlike competitors (like Rocket Money or Trim), our V1 works *without* requiring users to connect their sensitive bank accounts via Plaid. Instead, it builds a comprehensive dashboard using a secure email scanner (for receipts) and a smart browser extension (for tracking new signups).

This repository holds the code for the `index.html` waitlist/coming-soon page. This page was built to validate the business idea, showcase the core value propositions, and collect interest from early adopters via a waitlist form.

## ✨ Key Features (as advertised on the page)

The SubDupes V1 product is designed to be a complete subscription "manager," not just a "tracker."

* **Privacy-First Discovery:** No bank connection (Plaid) required.
* **Smart Email Scan:** Securely scans your inbox (Gmail/Outlook) for receipts to find existing subs.
* **Browser Extension:** A smart companion that detects when you sign up for a new trial.
* **Concierge Cancellation:** A "Cancel for Me" button where a human team member handles the entire cancellation process for you.
* **Free Trial Alerts:** A 48-hour alert before a free trial converts to a paid plan.
* **Duplicate & Price Hike Detection:** Automatically flags "SubDupes" (duplicate subscriptions) and price increases found in receipts.
* **Visual Spending Dashboard:** A clean, graphical UI to see your spending by category.

## 💻 Built With

This landing page is intentionally lightweight, fast, and dependency-free.

* **HTML5:** For semantic and accessible structure.
* **CSS3 (Vanilla):** For all styling, layout (Flexbox/Grid), animations, and a fully responsive design.
* **JavaScript (Vanilla):** Used only for the mobile hamburger menu and the placeholder `alert()` on form submission.
* **No Frameworks:** No React, Vue, Bootstrap, or Tailwind. Just one self-contained, easy-to-deploy `index.html` file.

## 🛠️ How to Use & Deploy

This project is a single file. No builds or complex steps are needed.

### 1. View Locally
1.  Clone this repository:
    ```sh
    git clone [https://github.com/your-username/subdupes-landing.git](https://github.com/your-username/subdupes-landing.git)
    ```
2.  Navigate into the directory:
    ```sh
    cd subdupes-landing
    ```
3.  Open the `index.html` file in any modern web browser.

### 2. Deploy to the Web (for free)
You can host this static page for free on numerous platforms:
* **GitHub Pages:** The easiest option. Just enable it in your repository's "Settings" tab.
* **Netlify:** Drag and drop the `index.html` file into the Netlify dashboard.
* **Vercel:** Similar to Netlify, just push the repo and it's live.
* **Any static host:** Upload the `index.html` file to any web server.

## 📝 Next Steps for This Repo (TODO)

This landing page is a starting point. The next steps are to make the waitlist functional:

* [ ] **Connect Waitlist Form:** The email form currently shows a simple `alert()`. This needs to be connected to a real service.
    * **Easy:** Use a service like [Netlify Forms](https://www.netlify.com/products/forms/) (if hosting there), [Formspree](https://formspree.io/), or [Getform](https://getform.io/).
    * **Advanced:** Connect it to your email marketing tool (e.g., Mailchimp, ConvertKit) or a custom API endpoint that saves to a database.
* [ ] **Add Analytics:** Add a tracking script (e.g., Google Analytics, Plausible, or Fathom) to measure visits and conversions.
* [ ] **Add Screenshot:** Take a high-quality screenshot of the final page and add it to the top of this `README`.

## 🔒 License & Privacy

**Important Note:** This is the landing page for your commercial product. You should **make this GitHub repository private** to protect your branding, copy, and strategy.

If you choose to keep it public, the code is distributed under the MIT License. See `LICENSE.txt` for more information.
