# Coregen AI — Landing Page

> **Internship Project** | Frontend Web Development  
> Built as part of a frontend development internship to design and implement a fully responsive, production-ready SaaS landing page.

---

## 📌 Project Overview

**Coregen AI** is a fictional autonomous AI developer agent platform. This project involved designing and building a complete marketing landing page from scratch using only HTML and CSS — no frameworks, no libraries, no shortcuts.

The goal was to practice real-world frontend skills: layout design, responsive breakpoints, animation, glassmorphism UI, and clean component structuring.

---

## 🎯 Objectives

- Build a pixel-perfect, responsive landing page using semantic HTML5 and vanilla CSS
- Apply modern UI/UX design patterns (glassmorphism, micro-animations, gradient typography)
- Implement a fully functional sticky navbar with mobile hamburger menu
- Structure reusable component sections (Hero, Features, Pricing, Testimonials, Footer)
- Follow SEO best practices with proper meta tags and heading hierarchy

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Page structure & semantic markup |
| **CSS3** | Styling, animations, responsive layout |
| **Google Fonts** | Space Grotesk, JetBrains Mono |
| **Font Awesome 6** | Icons (navbar, footer socials) |
| **CSS Custom Properties** | Design token system (`--accent-purple`, `--bg-dark`, etc.) |
| **CSS Grid & Flexbox** | Layout system throughout |

> No JavaScript frameworks or CSS libraries (Tailwind, Bootstrap) were used. All interactivity is handled with vanilla JS for the mobile nav toggle.

---

## 📁 Project Structure

```
Coregen/
├── index.html          # Main HTML file — all page sections
├── styles.css          # All styling — design system, components, responsive
├── images/
│   └── Logo.png        # Brand logo asset
└── README.md           # Project documentation
```

---

## 🧩 Sections Built

### 1. 🔝 Sticky Glassmorphic Navbar
- Fixed positioning with `backdrop-filter: blur()`
- Animated underline hover effect on nav links
- Mobile-responsive hamburger menu with JS toggle

### 2. 🚀 Hero Section
- Gradient headline with `background-clip: text`
- Animated badge with pulsing dot
- CTA buttons (Primary + Secondary)
- Mock terminal dashboard preview card

### 3. ⚡ Features Section
- 2-column responsive grid layout
- Feature cards with border-left accent on hover
- Icon + heading + description pattern

### 4. 💰 Pricing Section
- 3-tier pricing cards (Starter / Pro / Team)
- Featured card with purple border highlight
- Checkmark list items using CSS `::before`

### 5. 💬 Testimonials Section
- 3-column responsive grid
- Quote cards with author attribution

### 6. 🦶 Footer
- Text-based branded logo (`CoreGen AI`)
- Social icons (GitHub, X, LinkedIn) with hover animation
- Newsletter email signup form
- 3-column link grid (Product / Company / Legal)
- Footer link sliding underline animation
- Balanced copyright row with flex layout
- Purple accent top border

---

## ✨ Key Design Decisions

| Decision | Rationale |
|---|---|
| Dark theme (`#030014` bg) | Matches modern SaaS/dev tool aesthetic |
| `Space Grotesk` font | Clean, geometric, tech-forward feel |
| `#a855f7` purple accent | Consistent brand color used throughout |
| CSS custom properties | Makes theming and consistency easy to maintain |
| Dot-grid background | Adds depth without heavy visuals |
| `clamp()` for font sizes | Fluid typography without extra breakpoint overrides |

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Change |
|---|---|
| `> 900px` | Full desktop layout — 2-col features, 3-col pricing |
| `≤ 900px` | Features grid collapses to 1 column |
| `≤ 768px` | Mobile nav slides in, footer stacks vertically, newsletter stacks |

---

## 🚀 How to Run

This project has **zero build steps** — just open in a browser:

```bash
# Option 1: Open directly
# Double-click index.html in File Explorer

# Option 2: VS Code Live Server
# Install the "Live Server" extension → Right-click index.html → Open with Live Server
```

---

## 🧠 What I Learned

- How to build a complete UI design system using only CSS custom properties
- Implementing glassmorphism and `backdrop-filter` correctly across browsers
- Writing truly responsive layouts using Grid + Flexbox without a CSS framework
- Micro-animation techniques: sliding underlines, fade-in-up, pulse keyframes
- Structuring large CSS files by section/component for maintainability
- SEO fundamentals: meta descriptions, semantic heading hierarchy, `aria-label` usage

---

## 🔮 Potential Future Improvements

- [ ] Add scroll-triggered animations using Intersection Observer API
- [ ] Implement a working newsletter form backend (e.g., Formspree)
- [ ] Add a light/dark mode toggle
- [ ] Build an interactive pricing toggle (Monthly / Annual)
- [ ] Optimize images with WebP format
- [ ] Deploy to Vercel or GitHub Pages

---

## 👤 Author

**Aryan** — Frontend Development Intern  
Project built as part of internship training in UI/UX and frontend web development.

---

## 📄 License

This project is built for learning and portfolio purposes. All brand names and testimonials used are fictional.