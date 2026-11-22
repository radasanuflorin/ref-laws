# ⚽ REF-LAWS · referee training platform

<p>
  <img src="https://img.shields.io/badge/source-private-ff2e3b?style=for-the-badge&labelColor=0a0a0f&logo=github"/>
  <img src="https://img.shields.io/badge/JavaScript-0a0a0f?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
  <img src="https://img.shields.io/badge/GSAP-0a0a0f?style=for-the-badge&logo=greensock&logoColor=88CE02"/>
  <img src="https://img.shields.io/badge/PWA-0a0a0f?style=for-the-badge&logo=pwa&logoColor=5A0FC8"/>
</p>

> This is a showcase repository. The source code is kept in a private repository.

A training platform for football referees: the full **Laws of the Game**, every law change for the **IFAB 2026/27**
season, and quizzes built on real match situations. It is bilingual (English and Romanian) and installs as a PWA.

<p align="center">
  <img src="./assets/preview.webp" width="100%" alt="REF-LAWS in use"/>
</p>

## Features

- **Laws of the Game:** every chapter opens in a reader, one sub-chapter at a time, with a table of contents, previous / next buttons, arrow keys and swipe on phones.
- **Law changes 2026/27:** one card per change, checked against the official IFAB documents, with a clear note when a rule is a competition option and not mandatory.
- **Quizzes** based on real match situations, with progress saved on the device.
- **English and Romanian:** the Romanian text uses the terminology of Romanian refereeing.
- **Installable and offline:** a service worker keeps the site available without internet.
- Login and sign-up pages ready for a real backend; for now the account is a clearly marked demo.

<p align="center">
  <img src="./assets/screenshot.webp" width="100%" alt="Home page"/>
</p>

## Under the hood

- **Plain HTML, CSS and JavaScript**, with no framework, and animations made with GSAP and ScrollTrigger.
- **Accessibility:** focus traps in all modals, colours measured against WCAG AA contrast, Lighthouse scores of **100** for Accessibility, Best Practices and SEO.
- **Performance:** compressed hero videos with poster images, correctly sized images, and a Cumulative Layout Shift of 0.
- **Structured data** (JSON-LD), a sitemap and Open Graph tags.
- A git hook that bumps the cache version on every commit, so visitors never get stale files.
- Tested in Chromium, Firefox and WebKit (Safari).

## Tech stack

JavaScript · HTML5 · CSS3 · GSAP · ScrollTrigger · Service Worker · PWA · SVG

## Source code

The code is private. If you would like to see it, contact me through my [GitHub profile](https://github.com/radasanuflorin).

<sub>REF-LAWS is an independent educational project and is not affiliated with The IFAB.</sub>
