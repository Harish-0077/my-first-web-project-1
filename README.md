# Anniyappa Publications & SB Institute Web Portal

Welcome to the official static informational web portal of **Anniyappa Publications & SB Institute**. This portal is designed with state-of-the-art UI/UX patterns, offering a premium, highly responsive, and interactive experience for academic textbook explorations, internship enrollments, workshop activities, and contact channels.

---

## 📂 Project Architecture

The codebase strictly adheres to the requested professional directory map:

```text
staticwebpage/
├── index.html                 # Home landing page with video embeds & showcases
├── about.html                 # Multi-section narrative corporate timeline
├── bookshelf.html             # Library grid portal with live category filters
├── books-production.html      # Coming Soon book roadmaps & timelines
├── internship.html            # Skill modules and enrollment forms
├── gallery.html               # Filterable masonry activity portfolios
├── contact.html               # Google Maps coordinates and validation forms
│
└── assets/
    ├── css/
    │   └── style.css          # Design system, CSS variables & layout styling
    └── js/
        ├── main.js            # Programmatic WhatsApp float widget, sticky nav, year update
        ├── bookshelf.js       # Dynamic textbook DB rendering & sample chapter download modal
        └── gallery.js         # Interactive photo grid filtering & native image lightbox
```

---

## 💎 Features & Custom Implementations

1. **Academic Imperial Palette**: Uses **Deep Imperial Indigo** (`#1e1b4b`) as primary for institutional authority and **Bright Amber Gold** (`#d97706`) as secondary accenting for buttons, highlights, active states, and custom vectors.
2. **Glassmorphic Navigation**: Sticky header equipped with `backdrop-filter: blur(12px)` that automatically transitions to a compact dark layout (`.navbar-scrolled`) when scrolling past 50px to ensure premium readability over content banners.
3. **Programmatic WhatsApp Floating Widget**: Auto-injected on *every page* via global script parameters, showing a custom pulsing glow effect.
4. **Dynamic Digital Library**: Powered by JavaScript data bindings. Allows real-time filtering without reloading pages across 9 categories (*Computer Science, AI, Web Technology, Data Science, Blockchain, IoT, Cloud Computing, and Internship Materials*).
5. **Interactive Sample Chapter Downloads**: Dynamic textbook card clicks launch customized modular dialogs displaying detailed Table of Contents outlines and downloading sample syllabus kits (PDF).
6. **Campus Masonry Portfolio**: Smooth flexbox column gaps organizing event images with description overlays. Clicking a thumbnail opens a native, lightweight image lightbox for high-resolution reviews.
7. **Form Validation & Custom Toast Messages**: Submitting any inquiry coordinates validates fields and returns beautiful, custom-designed sliding alerts.

---

## 🚀 How to Run Locally

Since this is a high-performance, client-side static web application built on HTML5, CSS3, Bootstrap 5.x (via jsDelivr CDN), and Vanilla JS, **no local server installations or command-line dependencies are required!**

### Standard Browser Access
1. Open the project root folder.
2. Double-click [index.html](file:///c:/Users/HARISH/OneDrive/Desktop/staticwebpage/index.html) to open the homepage directly inside your favorite browser (Chrome, Firefox, Safari, Edge).
3. Click navbar elements or CTA buttons to smoothly navigate between portals.

### Local Development Server (Optional)
If you want to run a lightweight local development server using `Node.js` or Python:
- **Node.js (npx)**:
  ```bash
  npx serve .
  ```
- **Python 3**:
  ```bash
  python -m http.server 8000
  ```
Then access the site in your browser at `http://localhost:8000` or `http://localhost:3000`.

---

## 📜 Credits & Author Details
- **Client & Publisher**: Anniyappa Publications
- **Director & Chief Author**: Dr. C.V. Suresh Babu (SB Institute)
- **Developed by**: Antigravity AI Web Development Agent
