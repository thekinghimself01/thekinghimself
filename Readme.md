# Michael Esan — Portfolio Website

> Personal portfolio of **Michael Esan**, Full Stack Developer based in Sheffield, UK.  
> Built with pure HTML, CSS, and JavaScript — no frameworks, no build tools.

🌐 **Live Site:** [thekinghimself.netlify.app](https://thekinghimself.netlify.app)

---

## ✦ Preview

```
Dark luxury aesthetic · Gold accent system · Animated cursor · Scroll reveals
```

---

## ✦ Features

- **Custom animated cursor** with a magnetic lag ring
- **Hero section** with staggered text reveal and mouse-parallax orbs
- **Count-up stats** that animate on scroll into view
- **Skill cards** with hover shine effect
- **Project showcase** with animated gold reveal bars
- **About section** with a live code block displaying the dev stack
- **Smooth scroll-triggered reveals** throughout every section
- **Contact section** with hover fill animations
- Fully **responsive** — mobile, tablet, and desktop

---

## ✦ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, clip-path, animations) |
| Logic | Vanilla JavaScript (IntersectionObserver, RAF) |
| Fonts | Syne · Instrument Serif · DM Mono (Google Fonts) |
| Hosting | Netlify |

---

## ✦ Project Structure

```
portfolio/
└── king.html       # HTML file
└── the.css         #CSS file 
└── himself.js      #JavaScript file
└── README.md       # You are here
```

---

## ✦ Customisation

All content lives in `index.html`. Key areas to update:

| What | Where in the file |
|------|------------------|
| Name / role | `#hero` section |
| Bio text | `#about` section |
| Project links | `href` on `.project-item` anchors |
| Contact details | `#contact` section + nav links |
| Stats numbers | `data-target` attributes on `.stat-num` |

Colors are controlled via CSS variables at the top of the `<style>` block:

```css
:root {
  --gold: #C9A84C;
  --bg:   #0A0A0A;
  --text: #F0EDE8;
}
```

---

## ✦ Projects Featured

### MUMU AI `2026`
AI-powered research assistant · React · Node.js · MongoDB · REST API

### RadiantClean `2025`
Full-stack website for a cleaning service · HTML5 · CSS3 · JavaScript · MongoDB

---

## ✦ Contact

| | |
|--|--|
| 📧 Email | [1stmking@gmail.com](mailto:1stmking@gmail.com) |
| 📞 Phone | +44 739 154 6849 |
| 🌐 Website | [thekinghimself.netlify.app](https://thekinghimself.netlify.app) |

---

<p align="center">
  Made with ♥ in Sheffied, UK &nbsp;·&nbsp; © 2026 Michael Esan
</p>