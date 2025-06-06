# ===============================================
# ARTTULOS.ORG - THE GORGEOUS LINUX EXPERIENCE
# ===============================================

## Where Stability Meets Stunning Design.
Bringing the Future of Open Source to Your Desktop.

---

### **Welcome to the ArttulOS Website Repository!**

This repository houses the source code for the official ArttulOS website: `arttulos.org`. Our website is designed to reflect the core philosophy of ArttulOS itself: a blend of robust functionality, user-centric design, and stunning aesthetics. It serves as the primary hub for users and contributors to learn about our project, explore features, engage with the community, and download ArttulOS.

The website aims to be as performant and user-friendly as the operating system it represents, with a focus on clean code, modern web technologies, and a visually immersive experience.

---

### **Website Features**

*   **Responsive Design:** Fully optimized for viewing across desktops, tablets, and mobile devices, ensuring a seamless experience.
*   **Modern Aesthetics:** A visually rich design featuring deep gradients, subtle animations, transparent card effects, and a consistent color palette inspired by the ArttulOS brand.
*   **Intuitive Navigation:** A sticky, dynamic navigation bar with smooth scrolling to key sections and clear pathways to all informational pages.
*   **Comprehensive Information:** Dedicated sections for:
    *   **About ArttulOS:** Our vision, mission, and journey.
    *   **Features:** Highlighting the key strengths of the OS.
    *   **Community:** How to connect, contribute, and collaborate.
    *   **Roadmap:** A detailed timeline of upcoming milestones and future goals.
    *   **Documentation:** An interactive knowledge base with smart search.
    *   **Download:** Access to stable and development builds.
    *   **ArttulCat Browser:** Dedicated page for our privacy-focused browser.
    *   **Contact:** Multiple ways to get in touch with the team.
    *   **Legal:** Privacy Policy, Terms & Conditions, and Behavioral Guidelines.
*   **Performance Optimized:** Prioritizes fast loading times through minimized HTTP requests, efficient font loading, and deferred JavaScript execution.
*   **Interactive Modals:** Engages users for email contact choices and documentation checks.
*   **Mascot Integration:** Features the charming Artty mascot to enhance brand identity and user engagement.

---

### **Technologies Used**

*   **HTML5:** For semantic structure and content.
*   **CSS3:** Extensive custom styling, CSS variables for theming, advanced gradients, and animations.
*   **JavaScript (Vanilla & jQuery):** For dynamic interactions, form handling, smooth scrolling, and UI enhancements.
*   **Bootstrap 5.2.3:** A robust front-end framework for responsive layout and UI components.
*   **Bootstrap Icons 1.10.5:** For a wide range of vector icons used throughout the site.
*   **Custom Fonts:** `FreeSans` (served locally in `woff2`/`woff` for performance).
*   **Lunr.js:** A lightweight full-text search library for the documentation section.
*   **jQuery Sticky.js:** For sticky header functionality.
*   **Click-Scroll.js:** For enhanced smooth scrolling.

---

### **Getting Started (Local Development)**

To get a local copy of the ArttulOS website up and running for development or testing:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-org/arttulos-website.git
    cd arttulos-website
    ```
2.  **Open in your browser:**
    Simply open the `index.html` file in your web browser. Since this is a static website, no web server or build process is required for basic viewing.

    *Note: For some local features (like specific font loading or certain API calls if you implement them in the future), a simple local server (e.g., using Python's `http.server`) might be beneficial, but it's not strictly necessary for general browsing.*

    ```bash
    # Optional: If you encounter issues with local file paths (e.g., fonts)
    # or want to simulate a server environment:
    python3 -m http.server 8000
    # Then navigate to http://localhost:8000 in your browser
    ```

### **Project Structure**
arttulos-website/
├── index.html # Homepage
├── about.html # About ArttulOS page
├── community.html # Community page
├── roadmap.html # Roadmap page
├── download.html # Download page
├── contact.html # Contact Us page
├── documentation.html # Documentation page
├── arttulcat.html # ArttulCat browser page
├── behavioralguidelines.html # Code of Conduct / Behavioral Guidelines
├── privacypolicy.html # Privacy Policy
├── TermsandConditions.html # Terms and Conditions
├── arttulos_contributing.html # Detailed Contribution Guidelines for the OS
├── 404.html # Custom 404 Page
├── Artty.png # The adorable ArttulOS mascot
├── css/
│ └── templatemo-festava-live.css # Main template stylesheet
├── js/
│ ├── jquery.sticky.js # For sticky elements
│ ├── click-scroll.js # For smooth scrolling navigation
│ └── custom.js # General custom JavaScript
├── fonts/ # Custom font files (FreeSans variants)
│ ├── FreeSans.woff2
│ ├── FreeSans.woff
│ ├── FreeSans.ttf
│ ├── FreeSansBold.woff2
│ ├── FreeSansBold.woff
│ ├── FreeSansBold.ttf
│ ├── FreeSansOblique.woff2
│ ├── FreeSansOblique.woff
│ ├── FreeSansOblique.ttf
│ ├── FreeSansBoldOblique.woff2
│ ├── FreeSansBoldOblique.woff
│ └── FreeSansBoldOblique.ttf
└── images/ # Placeholder images or general assets
└── placeholder-desktop.jpg
---

### **Contributing to the Website**

We welcome contributions to the ArttulOS website! If you find issues, have suggestions for improvements, or want to help with design or content:

*   **Report Issues:** Open an issue on our GitHub repository.
*   **Submit Pull Requests:** If you've made changes, feel free to open a Pull Request.

Please ensure your contributions adhere to our general project guidelines (linked below).

---

### **License**

The code for this website is open-source, distributed under the **MIT License**.

This project's website design incorporates elements from the "Festava Live" template by [TemplateMo](https://templatemo.com/tm-583-festava-live), distributed by [ThemeWagon](https://themewagon.com).

**Important Note:** The ArttulOS operating system itself is licensed under the [GNU AGPL v3.0](https://www.gnu.org/licenses/agpl-3.0.html), as detailed in our [Terms and Conditions](TermsandConditions.html).

---

### **Contact**

Have questions, feedback, or just want to connect?

*   **General Inquiries:** `arttulos@proton.me`
*   **Community Chat:** Join us on [Matrix](https://matrix.to/#/#arttulos:matrix.org)
*   **Contribution Guidelines (for the OS):** See our [developer guidelines](https://arttulos.org/behavioralguidelines.html) page.

---
*Crafted with care by The ArttulOS Team.*
