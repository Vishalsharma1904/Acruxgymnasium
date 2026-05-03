# Acrux Gym Website 🏋️‍♂️

A premium, modern, and ultra-fast single-page web application built for **Acrux Gym** in Ghaziabad.

## 🚀 Features
- **Modern Luxury UI:** Dark/Light theme toggle, smooth parallax scroll effects, and glassmorphism elements.
- **AI Workout Plan Generator:** A smart calculator that generates a customized, 7-day workout routine based on the user's fitness goals, experience level, and available equipment.
- **Client-Side PDF Generation:** Users can export their custom workout plans directly to a high-quality PDF on any device (Mobile, Tablet, Desktop) without needing a server.
- **Health Metrics (BMI) Calculator:** Built-in tool for users to calculate their exact Body Mass Index and ideal weight ranges.
- **Web3Forms Integration:** Fully functional, backend-free contact form that sends lead information straight to the owner's email.
- **WhatsApp Widget:** Floating sticky widget that redirects instantly to the gym owner's WhatsApp to drastically boost lead conversion.
- **Zero Dependencies:** Built with 100% vanilla JavaScript, HTML5, and CSS3. Extremely fast load times and an offline-first capability.

## 💻 Tech Stack
*   **Frontend:** HTML5, CSS3, Vanilla JavaScript
*   **Libraries:** `html2pdf.js` (loaded via CDN for PDF exporting)
*   **Typography:** Google Fonts (Playfair Display, Cormorant Garamond, DM Sans)
*   **Icons:** Inline SVG paths for maximum performance

## 🌐 Deployment (GitHub & Vercel)
This repository is pre-optimized for instant deployment to Vercel.

**Steps to deploy:**
1. Upload this repository to **GitHub**.
2. Log into your [Vercel](https://vercel.com/) account.
3. Click **Add New Project** and import the repository from GitHub.
4. Click **Deploy**. Vercel will automatically detect the `index.html` and deploy it globally on its Edge Network.

**Note:** No build step (`npm run build`) is required since this is a pure Vanilla JS/HTML setup.

## 📝 Configuration
*   **Email Forwarding:** The contact form is powered by Web3Forms. Ensure your `access_key` in `index.html` is properly linked to your email address.
*   **WhatsApp Number:** The WhatsApp floating widget points to `+91 83768 68838`. To change this, modify the `wa.me` link in `index.html`.

---
*Designed & Optimized for Acrux Gym, Ghaziabad.*
