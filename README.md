# AUREX Full-Stack Engineering Internship

**Intern:** Hamna Asif
**Domain:** Full-Stack Development / UI-UX Design
**Month 1:** Frontend Foundation — **Week 3**
**Focus:** Advanced CSS Grid & Flexbox Masterclass + CSS Animations, Transitions & UI Polish

---

## 🔗 Live Deployment Link

_Add your GitHub Pages or Vercel URL here after deploying:_
`https://your-deployment-link.vercel.app`

## 📁 Repository Structure

```
aurex-web-internship-hamna/
├── index.html
├── styles/
│   ├── main.css
│   └── animations.css
└── README.md
```

## 📌 Project Overview

A single-page developer portfolio built as the Week 3 deliverable — a
showcase page that puts the week's CSS topics to direct use: an
`auto-fit` / `minmax` project grid, a full custom-property theme system
with a working dark/light toggle, keyframe animations, and scroll-based
reveal interactions across every section.

## ✅ What This Build Covers

### 1. Advanced CSS Grid Layouts
- Project showcase grid: `grid-template-columns: repeat(auto-fit, minmax(260px, 1fr))` — reflows from 1 to 4 columns with no column-count media query needed.
- Skills grid and stats grid built the same way for consistent responsive behaviour.
- Combined with Flexbox for the nav bar, button rows, tag lists, and the skill-bar layout.

### 2. Transitions & Keyframe Animations
- One orchestrated staggered fade-up on hero load (`--d` custom properties control the delay per element).
- `IntersectionObserver`-driven scroll-reveal on every section (About, Work, Skills, Timeline, Contact) — not just the hero.
- Animated skill progress bars that fill once their section scrolls into view.
- Hover micro-interactions: card border/background shift, link arrow slide, chip lift, nav underline sweep.
- A JS-driven button ripple effect on click.

### 3. Modern UI/UX Refinement
- Full CSS Custom Property token system in `:root`, redefined under `[data-theme="light"]` for a working dark/light toggle (persisted via `localStorage`).
- Type scale built with `Fraunces` (display), `Inter` (body), and `IBM Plex Mono` (labels/tags).
- Card elevation and hairline borders used deliberately instead of default drop shadows.

### 4. Responsive Optimization
- Fluid typography and spacing throughout via `clamp()` instead of fixed breakpoints.
- Mobile hamburger nav with a collapsing menu under 640px.
- Grid layouts collapse cleanly to a single column on small screens with no horizontal scroll.

### 5. Clean CSS Architecture
- BEM naming throughout: `.project-card`, `.project-card__title`, `.skill-group__title`, etc.
- Design tokens centralised in `:root` — no magic numbers scattered through the sheet.

## 🧩 Sections Included

| Section | Purpose |
|---|---|
| Hero | Staggered intro animation, primary CTAs |
| About | Bio + stats grid |
| Work | CSS Grid project showcase (4 projects) |
| Skills | Categorised skill groups with animated progress bars |
| Timeline | Education and internship path |
| Contact | Styled contact form + direct email |
| Footer | Social links |

## 🖥️ Performance & Responsive Testing Outcomes

_Fill in after testing on your own devices, e.g.:_
- Chrome DevTools mobile emulation (375px, 768px, 1024px): no horizontal scroll, grid collapses to 1 column under 560px.
- Lighthouse performance score: ___
- Tested on: ___ (list real devices/browsers)

## 📝 Weekly Progress Reflection

_A few sentences on what was hardest this week (e.g. getting `auto-fit`
vs `auto-fill` right, tuning the stagger timing, or wiring up the
scroll-reveal observer) and what you'd improve next week._

## ✔️ Completed Features Checklist

- [x] Multi-column CSS Grid showcase with `auto-fit` / `minmax`
- [x] Keyframe + hover animations
- [x] Scroll-triggered reveal animations (IntersectionObserver)
- [x] Animated skill progress bars
- [x] Responsive across mobile / tablet / desktop
- [x] Dark/light theme toggle with persisted preference
- [x] Mobile hamburger navigation
- [x] Styled contact form
- [ ] Deployed live and verified on a real browser
- [ ] Screenshots / GIF captured for submission

## 👤 Contact

- Email: hamnaasif623@gmail.com
- GitHub: [Hamna-Asif05](https://github.com/Hamna-Asif05)
- LinkedIn: [hamna-asif5](https://linkedin.com/in/hamna-asif5)
-
