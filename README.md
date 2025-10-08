# 💙 Accquainted

**Accquainted** is a campus-based social and dating app for UCI’s ACC community — built to help students connect through shared culture, clubs, and events.  

This repository hosts the **official landing page** for the app, powered by [Jekyll](https://jekyllrb.com/) and the [Automatic App Landing Page](https://github.com/emilbaehr/automatic-app-landing-page) theme.

---

## 🌐 Live Site
**[https://accquainted.com](https://accquainted.com)**

---

## 🧩 Overview

**Accquainted** connects students across the ACC communities at UC Irvine.  
The app is designed for genuine, campus-first connections through:
- Verified UCI email signup
- Matching based on shared interests and club tags
- A clean, simple chat system
- Optional event listings for ACC mixers and socials  

The **website** serves as:
- A preview of the app
- A sign-up and waitlist portal
- A place for updates, FAQs, and privacy info

---

## 🛠️ Tech Stack

| Layer | Tool |
|-------|------|
| Framework | [Jekyll](https://jekyllrb.com) |
| Theme | [Automatic App Landing Page](https://github.com/emilbaehr/automatic-app-landing-page) |
| Hosting | [GitHub Pages](https://pages.github.com) |
| Domain | [accquainted.com](https://accquainted.com) (via Squarespace DNS) |

---

## ⚙️ Local Development

To test or modify the site locally:

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/accquainted-site.git
cd accquainted-site

# 2. Install Jekyll (if not already installed)
gem install bundler jekyll

# 3. Install dependencies
bundle install

# 4. Run the local server
bundle exec jekyll serve
