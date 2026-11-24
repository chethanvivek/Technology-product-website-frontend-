Student Details:
name : Chethan Vivek Sai Sundar Sukkireddi
Niat Id: N26V01A0337
Section: 5
# PulseX Pro - Smartwatch Promotional Webpage

A sleek, responsive, single-page promotional launch website for the fictional **PulseX Pro** smartwatch. Built using pure **HTML5** and **CSS3** (Flexbox & Media Queries) with zero JavaScript or external CSS frameworks.

Designed for academic evaluation in **B.Tech CSE - Web Development**, following clean coding practices, semantic structure, accessibility guidelines, and beginner-readable architecture.

---

## 📸 Project Preview & Structure

```
Technology product website/
│
├── index.html            # Main semantic HTML5 webpage
├── css/
│   └── style.css         # Pure CSS3 stylesheet (Variables, Flexbox, Media Queries)
├── images/
│   ├── watch-hero.jpg    # Front display hero view
│   ├── watch-side.jpg    # 9.2mm aerospace chassis side view
│   └── watch-lifestyle.jpg # Active wrist workout lifestyle view
└── README.md             # Project documentation & grading notes
```

---

## 🚀 Key Webpage Sections (In Flow Order)

1. **Navigation Bar (`<header>`, `<nav>`)**:
   - Brand logo with electric blue accent (`PulseX Pro`).
   - Sticky navigation with glassmorphism backdrop blur.
   - Jump links to Overview, Features, Specs, Pricing, Reviews, and a high-contrast "Buy Now" CTA button.

2. **Hero Section (`#hero`)**:
   - Product headline with gradient typography.
   - Compelling value proposition tagline.
   - High-resolution hero smartwatch image (`images/watch-hero.jpg`).
   - Dual Call-To-Action buttons ("Buy Now" & "Learn More").

3. **Key Features (`#features`)**:
   - 6 responsive cards arranged in a multi-column flex layout.
   - Includes emoji visual icons, feature title, and single-line descriptive copy:
     - ❤️ **Heart-Rate Tracking** (24/7 optical sensor & alerts)
     - 🛰️ **Dual-Frequency GPS** (Multi-satellite positioning)
     - 🔋 **14-Day Battery Life** (Fast magnetic charge)
     - 🌊 **5ATM Water Resistance** (Up to 50 meters depth)
     - 🌙 **Advanced Sleep Scoring** (Deep, light & REM analysis)
     - 📞 **Bluetooth HD Calling** (Dual-mic ENC voice)

4. **Product Showcase (`#showcase`)**:
   - Alternating image-and-text rows for an editorial product launch aesthetic.
   - **Row 1**: Side profile (`images/watch-side.jpg`) highlighting the 9.2mm ultra-slim chassis & haptic digital crown.
   - **Row 2**: Lifestyle in action (`images/watch-lifestyle.jpg`) highlighting sports modes, VO2 max, and water resistance.

5. **Specifications Table (`#specs`)**:
   - Clean 2-column specifications table covering:
     - *Display*, *Battery*, *Connectivity*, *Sensors*, *Water resistance*, *Weight*, and *Compatibility*.
   - Accessible table structure (`<thead>`, `<tbody>`, `<th> scope="col"`).

6. **Pricing Plans (`#pricing`)**:
   - 3 variant cards with pricing in Indian Rupees (₹):
     - **Standard Edition**: ₹4,999
     - **Pro Edition (Most Popular)**: ₹7,999 (highlighted with an electric blue border, badge, and subtle scale effect)
     - **Ultra Edition**: ₹11,999
   - Feature checklists and individual action buttons.

7. **Customer Reviews (`#reviews`)**:
   - 3 testimonial cards featuring 5-star ratings (`★★★★★`), user feedback, reviewer names, and locations/roles.

8. **Purchase Order Form (`#purchase`)**:
   - Design-only clean order checkout card.
   - Semantic form fields with properly linked `<label for="...">` and `<input id="...">` attributes:
     - Full Name (`text`)
     - Email Address (`email`)
     - Model Edition (`select` dropdown)
     - Quantity (`number`)
     - Submit Button ("Buy Now") with security badges.

9. **Footer (`<footer>`)**:
   - Brand summary, secondary navigation links, support links, and copyright notice.

---

## 🎨 Design & Aesthetic Guidelines

- **Dark Mode Theme**: Deep near-black backgrounds (`#080b11`, `#0f1422`, `#141b2d`) for a premium gadget aesthetic.
- **Electric Blue Accent**: `#00d2ff` with subtle cyan glow (`rgba(0, 210, 255, 0.35)`) for key buttons, hover states, and badges.
- **Typography & Readability**: System font stack (`-apple-system`, `Segoe UI`, `Roboto`) optimized for instant loading and crisp legibility with WCAG high-contrast text ratios.
- **Micro-Interactions**: Smooth hover elevations (`transform: translateY(-4px)`), button glow transitions, and responsive image scaling.

---

## 📱 Responsive Breakpoints & Flexbox

The layout adapts seamlessly across all device screens without horizontal overflow:

- **Desktop (1280px and above)**: Full multi-column grid, side-by-side hero, 3-card features and pricing grids, alternating showcase rows.
- **Tablet (max-width: 768px)**: Navbar wraps neatly, hero stacks vertically with centered alignment, features reflow to 2 columns, showcase rows stack neatly.
- **Mobile (max-width: 480px / 375px)**: Feature cards and pricing cards stack into single columns, full-width touch-friendly CTA buttons, horizontally scrollable specification table if needed, optimized typography sizing.

---

## 🛠️ Code Quality Standards

- **Strictly HTML5 & CSS3**: No JavaScript files, no external libraries, no Bootstrap, and no Tailwind CSS.
- **CSS Variables (`:root`)**: Centrally managed color palette, border radii, transitions, and container widths.
- **Logical Grouping**: `css/style.css` is structured into 13 clearly commented sections.
- **Accessibility (a11y)**: Every `<img>` tag features descriptive `alt` text; all form fields have bound `<label>` tags.
- **Consistent Formatting**: Clean 2-space indentation throughout all files.

---

## 💻 How to Run the Project

1. Clone or download the project folder.
2. Ensure the files are structured as shown in the directory map above.
3. Open `index.html` directly in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
4. Resize your browser window or press `F12` to open DevTools device emulation to test responsiveness at **1280px**, **768px**, and **375px**.
