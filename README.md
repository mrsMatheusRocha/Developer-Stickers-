# Developer Stickers

Welcome to **Developer Stickers**!

This project is a web-based application built with **HTML** (56%), **JavaScript** (33%), and **CSS** (11%), focused on delivering a fast, fun, and performant sticker experience for developers.  
Our mission: **Optimize Web Performance and Web Vitals** for every user.

---

## 🚀 Web Performance & Core Web Vitals

**Why care?**  
Fast-loading, responsive sites create happy users and better SEO.  
We optimize for the key metrics tracked by [Google's Core Web Vitals](https://web.dev/vitals/):

### Core Metrics:
- **Largest Contentful Paint (LCP):** Measures loading performance. Aim: <2.5 seconds.
- **First Input Delay (FID):** Measures interactivity. Aim: <100 ms.
- **Cumulative Layout Shift (CLS):** Measures visual stability. Aim: <0.1.

### How We Optimize:
- **Efficient Asset Delivery**
  - Stickers and images use modern formats (SVG, WebP) and are compressed.
  - Images and non-critical content are lazy-loaded.
- **Fast, Clean HTML**
  - Semantic HTML for quick parsing.
  - Inlined critical CSS for faster rendering.
- **Optimized JavaScript**
  - Minimal, modular scripts.
  - Async & deferred loading for non-essential code.
- **Responsive CSS**
  - Mobile-first, adaptive layouts.
  - Styles are minified and purged for unused rules.
- **Stable Layouts**
  - Dimensions set for images and stickers to prevent layout shifts.
- **Caching & CDN**
  - Leverage browser caching and CDN delivery for quick repeat visits.

---

## 🏁 Quick Start

1. **Clone the Repo**
   ```bash
   git clone https://github.com/mrsMatheusRocha/Developer-Stickers-.git
   ```
2. **Open `index.html`**
   - No build step required—just open in your browser.

---

## 🛠️ Development Tips for Web Vitals

- **Measure:**  
  Use [Lighthouse](https://developers.google.com/web/tools/lighthouse), [WebPageTest](https://www.webpagetest.org/), or [Chrome Web Vitals Extension](https://chrome.google.com/webstore/detail/web-vitals/ahfhijdlegdabablpippeagghigmibma) to audit and improve.
- **Optimize Images:**  
  Compress before adding. Prefer SVG for stickers.
- **Limit Third-Party Scripts:**  
  Only add what’s essential—each extra script impacts performance.
- **Minimize Main Thread Work:**  
  Keep JS lean and avoid blocking rendering.

---

## 🤝 Contributing

We welcome PRs that improve speed, stability, and web vitals!

- Compress assets and refactor code for faster loads
- Suggest new stickers (SVG preferred, optimized for size)
- Help stabilize layouts and reduce shifts

---

## 🌟 Performance Targets

| Metric                    | Target        |
|---------------------------|--------------|
| Largest Contentful Paint  | < 2.5s       |
| First Input Delay         | < 100ms      |
| Cumulative Layout Shift   | < 0.1        |
| Total Page Weight         | < 150KB      |

---

## 📬 Feedback

Open an [issue](https://github.com/mrsMatheusRocha/Developer-Stickers-/issues) for suggestions or performance ideas.

---

**Make developer stickers fun—and blazing fast!**
