<div align="center">

# Colorful Portfolio

**A responsive, animated personal portfolio website built with HTML, CSS, and vanilla JavaScript.**

### [🔗 View Live Demo](https://hadilberavi.github.io/Colorful-portfolio/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
[![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://hadilberavi.github.io/Colorful-portfolio/)

</div>

> [!NOTE]
> **🌱 Where it all started:** This is one of the very first projects I built when I began my web development journey. I've intentionally kept it exactly as it was, without rewriting or polishing it, because I'm proud of how far I've come and this is where it began.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Deployment](#deployment)
- [Roadmap](#roadmap)
- [Author](#author)

## About the Project

This is the personal portfolio website of **Hadel Berawi**, a web developer and student at Bitlis Eren University. It is a single-page site written entirely in hand-coded HTML, CSS, and JavaScript, with no frameworks and no build step. The focus is a clean, playful design with smooth animations and a fully responsive layout.

The page is organized into four sections:

| Section | Description |
| --- | --- |
| **Home** | Hero introduction with a rotating "profession wheel", profile photo, social links, and a CV button |
| **About** | A short personal introduction and background |
| **Skills** | Animated progress bars showing proficiency in HTML, CSS, and JavaScript |
| **Contact** | A contact form for name, email, phone number, subject, and message |

## Features

- **Fully responsive design:** layout and typography adapt across multiple breakpoints, from large desktop screens down to 315px-wide phones.
- **Sticky header:** the fixed navigation bar gets a subtle drop shadow once the page is scrolled past 100px.
- **Scroll-spy navigation:** the active navigation link updates automatically to match the section in view.
- **Mobile hamburger menu:** below 768px the navbar collapses into a toggleable menu whose icon switches between menu and close. The menu also closes automatically on scroll.
- **Rotating profession wheel:** a pure-CSS keyframe animation in the hero section cycles through roles on a continuous 13-second loop.
- **Scroll reveal animations:** headings, hero content, the About text, and the contact form slide into view from different directions, powered by ScrollReveal.
- **Animated skill bars:** HTML (90%), CSS (70%), and JavaScript (50%) progress bars fill in with a staggered animation, each with a percentage tooltip.
- **Contact form:** a clean, responsive form layout. *(Front-end only: submissions are not yet connected to a backend.)*
- **Back-to-top button:** a footer shortcut that smoothly scrolls back to the top of the page.
- **Themeable styling:** colors are defined as CSS custom properties, so the palette can be changed in one place.

## Tech Stack

| Technology | Usage |
| --- | --- |
| **HTML5** | Semantic page structure |
| **CSS3** | Flexbox and Grid layouts, custom properties, keyframe animations, media queries |
| **JavaScript (ES6)** | Mobile menu toggle, scroll-spy, sticky header, and library initialization |
| [ScrollReveal](https://scrollrevealjs.org/) | Scroll-triggered reveal animations |
| [Swiper](https://swiperjs.com/) 9 | Touch slider, set up for the testimonials carousel |
| [Boxicons](https://boxicons.com/) 2.1.4 | Icon set for navigation, social media, and professions |
| [Poppins](https://fonts.google.com/specimen/Poppins) (Google Fonts) | Typography |

All third-party libraries are loaded from CDNs. There are no package dependencies and no build tools.

## Project Structure

```text
Colorful-portfolio/
├── index.html      # Single-page markup (Home, About, Skills, Contact)
├── css/
│   └── style.css   # Styles, animations, and responsive breakpoints
├── js/
│   └── script.js   # Menu toggle, scroll-spy, sticky header, ScrollReveal and Swiper setup
├── images/         # Image assets for portfolio and testimonial content
└── hedil.jfif      # Profile photo shown in the hero section
```

## Getting Started

Nothing needs to be installed or built. The site runs in any modern browser.

1. **Clone the repository**

   ```bash
   git clone https://github.com/Hadilberavi/Colorful-portfolio.git
   cd Colorful-portfolio
   ```

2. **Open the site**

   Open `index.html` directly in your browser, or serve the folder with a local static server:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit [http://localhost:8000](http://localhost:8000).

> **Note:** the fonts, icons, and animation libraries load from CDNs, so an internet connection is required.

## Deployment

The site is deployed with **GitHub Pages**, served directly from the root of the `main` branch. The live site is built from exactly the files in this repository, with no build step and no separate deployment folder.

- **Live URL:** [https://hadilberavi.github.io/Colorful-portfolio/](https://hadilberavi.github.io/Colorful-portfolio/)
- **Automatic updates:** every push to `main` triggers a new GitHub Pages deployment.

To deploy your own copy:

1. Fork this repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, then select the **`main`** branch and the **`/ (root)`** folder.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/Colorful-portfolio/` within a few minutes.

## Roadmap

- [ ] Dark / light mode toggle
- [ ] Projects gallery, Services, and Testimonials sections
- [ ] Connect the contact form to an email or form-handling service

## Author

**Hadel Berawi**

- GitHub: [@Hadilberavi](https://github.com/Hadilberavi)
