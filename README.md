# SoftSell – Software Licensing Website

A modern and responsive React + Tailwind CSS-based single-page website for a software licensing business. Designed with clean UX, subtle animations via Framer Motion, and support for dark mode.

---

## 🚀 Features Implemented

### 🌐 General
- Fully responsive design for desktop, tablet, and mobile.
- Dark mode support via Tailwind’s `dark:` classes.
- Smooth scroll navigation with section IDs.
- Google Fonts integration (`Inter`).
- Modular React structure using functional components.

### 🎨 Design & Layout
- **Hero Section:** Clean intro with headline, subtext, CTA, and background image.
- **Feature Cards:** Grid of service highlights (Microsoft, Adobe, Antivirus, etc.).
- **Testimonials Section:** Animated customer reviews with staggered motion effects.
- **Contact Section:**
  - Embedded Google Map.
  - Contact details.
  - Fully styled form with validation-ready inputs and dropdown.
- **Footer:**
  - Organized in four columns: Services, Company, Resources, and Social Links.
  - Copyright bar.
- **Floating Chat Button:**
  - Opens a live chat box (mocked).
  - Supports real-time user input and message display.
  - Fixed positioning and animated toggle.

---

## 🎥 Framer Motion Animations

- `motion.div` used for all key entrance animations (Hero, Features, Testimonials, Contact, Footer, Chat).
- `AnimatePresence` used to handle conditional rendering of animated elements (like ChatBox).
- Animations include:
  - Fade-in
  - Slide-in
  - Scale transitions
  - Staggered children entrance for testimonial cards

---

## 🛠️ Tech Stack

| Tool            | Purpose                                  |
|-----------------|------------------------------------------|
| **React**       | Front-end framework                      |
| **Tailwind CSS**| Utility-first styling                    |
| **Framer Motion** | Declarative animations                  |
| **Google Fonts**| Custom font styling (`Inter`)            |
| **Heroicons / SVG** | Scalable iconography                 |
| **FontAwesome** | Social icons in footer (optional CDN)    |

---

## 🧠 Design Choices

- **Tailwind CSS** was chosen for rapid UI development and dark mode capabilities.
- **Framer Motion** brings life to static components with minimal overhead.
- **Component-driven structure** allows reusable and isolated UI elements.
- **Accessibility-first markup** (e.g., semantic tags, labels, aria attributes).
- **Responsive from the start**, leveraging Tailwind’s `sm`, `md`, `lg`, etc. breakpoints.

---
## ⏱️ Time Spent

| Task                                  | Duration |
|---------------------------------------|----------|
| Initial setup (React + Tailwind)      | 1 hour   |
| Navbar with animated hamburger menu   | 1 hour   |
| Hero section and responsive layout    | 1 hour   |
| Cards, features, and testimonials     | 2 hours  |
| Chatbot button + chat UI + logic      | 2 hours  |
| Footer with sections + dark mode      | 1.5 hours|
| Framer Motion integration             | 1 hour   |
| Responsive adjustments + polish       | 1 hour   |
| Final testing and refinements         | 0.5 hour |

**🕒 Total Time Spent:** ≈ **11 hours**

# 🚀 How to Run

### 1. Install Node.js
Make sure [Node.js](https://nodejs.org/) is installed (v16+ recommended).

### 2. Clone the Repository
bash
git clone https://github.com/yourusername/softsell-ui.git
cd softsell-ui

3. Install Dependencies
bash
npm install
4. Run Development Server
bash
npm run dev
Then open http://localhost:5173 in your browser.

5. Build for Production
bash
npm run build


⚡ I prioritized clean component architecture, smooth UX transitions, responsive design, and accessibility best practices to deliver a professional, production-ready UI experience.

---

## 📁 Folder Structure (Simplified)

src/
│
├── components/
│ ├── Hero.jsx
│ ├── Features.jsx
│ ├── Testimonials.jsx
│ ├── Contact.jsx
│ ├── Footer.jsx
│ └── ChatBox.jsx
│
├── App.jsx
└── index.js
