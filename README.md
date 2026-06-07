# Armin Alborzi — Portfolio Website

Personal portfolio website for **Armin Alborzi**, Senior IT Specialist based in Tehran, Iran.

**Live URL:** [https://picormin.github.io/armin-alborzi-portfolio-static/](https://picormin.github.io/armin-alborzi-portfolio-static/)

---

## Overview

Static portfolio site built with **Next.js** (App Router) and exported for deployment on **GitHub Pages**. The site showcases professional experience, services, sample projects, and contact information.

| Page | Path | Description |
|------|------|-------------|
| Home | `/` | Hero section, bio, CV download, stats counter |
| Services | `/services/` | IT & development services offered |
| Resume | `/resume/` | Experience, education, skills, about me |
| Work | `/work/` | Portfolio projects with image carousel |
| Contact | `/contact/` | Contact form |

---

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Styling:** Tailwind CSS
- **Animations:** Framer Motion
- **UI Components:** Radix UI (Tabs, Tooltip, Scroll Area)
- **Carousel:** Swiper.js
- **Counter:** react-countup
- **Icons:** react-icons
- **Deployment:** GitHub Pages (static export)

---

## Project Structure

```
armin-alborzi-portfolio-static/
├── index.html                  # Home page
├── armin-alborzi-fa.pdf        # CV (Persian, downloadable)
├── assets/
│   ├── photo.png               # Profile photo
│   └── work/
│       ├── thumb1.png          # Pars Digital Store mockup
│       ├── thumb2.png          # Sadra Watch Store mockup
│       └── thumb3.png          # Hesab Yek Accounting mockup
├── services/index.html
├── resume/index.html
├── work/index.html
├── contact/index.html
├── _next/static/               # Compiled JS, CSS, fonts
└── .nojekyll                   # GitHub Pages config
```

> **Note:** This repository contains the **static export output** only. The original Next.js source code is maintained separately. Content is edited directly in the compiled JS bundles under `_next/static/chunks/app/`.

---

## Content Summary

### Home
- **Title:** Senior IT Specialist
- **Bio:** 15+ years in IT — Python, networking, WordPress, MQL5
- **CV Download:** `armin-alborzi-fa.pdf`
- **Stats:** 15 years experience · 20 projects · 25 technologies

### Work (Sample Projects)
| # | Project | Type | Stack |
|---|---------|------|-------|
| 01 | Pars Digital Store | E-commerce | WordPress, WooCommerce, PHP |
| 02 | Sadra Watch Store | E-commerce | Next.js, Tailwind, React |
| 03 | Hesab Yek Accounting | Web App | Django, Python, PostgreSQL |

### Services
1. Web Development (WordPress, Django, Next.js)
2. Network Infrastructure (MikroTik, VPN, Firewall)
3. Python Development & Automation
4. Hardware & Laptop Repair
5. MQL5 Trading Bot Development
6. VoIP Systems (Elastix, Asterisk)
7. CCTV & Security Systems
8. IT Support & Helpdesk

### Resume Highlights
- **Experience:** Kanwal (IT Manager), Pejvak (Network PM), MSI (Technical/QC)
- **Education:** Associate Degree in Computer Software — Azad University, Ramsar
- **Skills:** Python, WordPress, MikroTik, Django, Linux, MQL5, JavaScript
- **Languages:** Persian (native), English (intermediate), German (basic)

---

## Deployment (GitHub Pages)

1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch: main / root**
4. The site is served at `https://<username>.github.io/armin-alborzi-portfolio-static/`

The `basePath` is configured as `/armin-alborzi-portfolio-static` in the Next.js build.

---

## Editing Content

Since only the static export is in this repo, edit content in these files:

| Section | File |
|---------|------|
| Home stats | `_next/static/chunks/app/page-e61e83db6a5cd5dd.js` |
| Home hero text | `index.html` |
| Work projects | `_next/static/chunks/app/work/page-f473ec95e23c4c46.js` |
| Resume data | `_next/static/chunks/app/resume/page-49207ab58ce4ff48.js` |
| Services list | `_next/static/chunks/app/services/page-bf5e7aad68b0e48b.js` |

After editing, also update the corresponding `index.html` in each page folder to keep SSR and hydration consistent.

---

## Contact

- **Email:** rmin.alborzi@gmail.com
- **Phone:** (+98) 937 481 6440
- **Location:** Tehran, Valiasr Square, Iran
- **Website:** [Corlink.ir](https://corlink.ir)

---

## License

Personal portfolio — all rights reserved © Armin Alborzi
