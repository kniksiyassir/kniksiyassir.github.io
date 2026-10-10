<div align="center">

# 👋 Yassir Kniksi — Data Science & AI Portfolio

**Master's student in Data Science · Machine Learning · Computer Vision · Big Data**
🎯 *Currently looking for a 6-month PFE internship in Data Science, Data Analysis, Machine Learning or AI.*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_the_portfolio-6C5CE7?style=for-the-badge)](https://kniksiyassir.github.io/portfolio/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-181717?logo=github&logoColor=white)
![Responsive](https://img.shields.io/badge/Design-Responsive-6C5CE7)

<a href="https://kniksiyassir.github.io/portfolio/">
  <img src="docs/demo.gif" alt="Animated demo of the portfolio (click to open the live site)" width="900">
</a>

<sub>👆 Click the animation to open the live portfolio</sub>

</div>

---

## 📑 Table of contents

- [About](#-about)
- [Live demo](#-live-demo)
- [Screenshots](#-screenshots)
- [Features](#-features)
- [Portfolio sections](#-portfolio-sections)
- [Featured projects](#-featured-projects)
- [Tech stack](#-tech-stack)
- [Project structure](#-project-structure)
- [Run locally](#-run-locally)
- [Deploy on GitHub Pages](#-deploy-on-github-pages)
- [Supabase configuration](#-supabase-configuration)
- [Contact](#-contact)

---

## 🧑‍💻 About

This is my personal portfolio, a single-page website that presents my journey **from networks & telecom to Data Science and AI**: education, internships, technical skills, academic projects and services.

The content (texts, skills, experience, education, projects, certificates) is stored in **Supabase** and can be edited from a private admin panel, so the site can be updated without touching the code.

---

## 🎬 Live demo

GitHub does not run JavaScript inside a README, so the animation above is a recording of the real site.

🌐 **Open the real, interactive portfolio:** [kniksiyassir.github.io/portfolio](https://kniksiyassir.github.io/portfolio/)

What you will see: animated loader, scrolling technology marquee, FR/EN switch, light/dark theme, project carousel and the contact form.

---

## 🖼️ Screenshots

### Home

<img src="docs/screenshots/home.png" alt="Home" width="800">

### About & journey

<img src="docs/screenshots/about.png" alt="About and journey" width="800">

### Skills

<img src="docs/screenshots/skills.png" alt="Skills" width="800">

### Projects

<img src="docs/screenshots/projects.png" alt="Projects" width="800">

---

## ✨ Features

| | Feature | Details |
|---|---|---|
| 🌍 | **Bilingual** | One-click switch between **English and French** (FR button) |
| 🌗 | **Light / dark theme** | Theme toggle in the navigation bar |
| 📱 | **Responsive** | Desktop, tablet and mobile (burger menu) |
| 🎞️ | **Animations** | Loader, scrolling marquee of technologies, animated dividers, floating decor, key figures |
| 🗂️ | **Dynamic content** | Texts, skills and sections loaded from Supabase |
| 🔐 | **Admin panel** | Private login to edit the portfolio content from the browser |
| ✉️ | **Contact form** | Opens the visitor's mail app with the message pre-filled |
| ⬆️ | **Navigation helpers** | Sticky navbar, scroll indicator, back-to-top button |

---

## 🧭 Portfolio sections

| # | Section | Content |
|---|---|---|
| 01 | **About** | Journey in 3 stages: Networks & Telecom → Computer Science & Maths → Data Science |
| 02 | **Contact** | Availability for a 6-month PFE, email, GitHub, LinkedIn, contact form |
| 03 | **Education** | Master's in Data Science, Professional Bachelor's, DUT, Scientific Baccalaureate |
| 04 | **Experience** | 3 internships: back-end (Laravel/MySQL), systems & networks, LAN/WAN security |
| 05 | **Skills** | Data, Networks & Security, Software & Databases, Big Data, AI & Machine Learning |
| 06 | **Projects** | 4 selected academic projects |
| 07 | **Services** | What I can build with Spark, Hadoop, Hive, Laravel, Cisco, Linux |
| 08 | **Certificates** | Certifications & credentials |

---

## 🚀 Featured projects

| Project | Description | Stack |
|---|---|---|
| 🫁 **Pneumonia Detection** | Deep Learning & Computer Vision project detecting pneumonia from chest X-rays with ResNet-18 | `PyTorch` `ResNet-18` `Computer Vision` |
| 🖼️ **Image Classification** | Supervised ML application for image classification and accessible model use | `Python` `Scikit-learn` `ML` |
| ⚡ **Apache Storm** | Academic Big Data project on real-time data processing | `Apache Storm` `Big Data` |
| 🛡️ **Windows Server Security** | Corporate network secured with Group Policy Objects | `Windows Server` `GPO` `Security` |

> The Pneumonia Detection project is also available as a full Flask web app: [pneumoscan-app](https://github.com/kniksiyassir/pneumoscan-app).

---

## 🧰 Tech stack

**Portfolio**

- HTML5, CSS3, vanilla JavaScript (single-file site)
- [Supabase](https://supabase.com) (`@supabase/supabase-js` v2) for content and authentication
- Google Fonts: *Bricolage Grotesque* and *Manrope*
- Hosting: GitHub Pages

**Skills showcased**

| Domain | Technologies |
|---|---|
| Data & AI | Python, PyTorch, TensorFlow, Scikit-learn, Pandas, NumPy, SQL |
| Big Data | Spark, Hadoop, Hive |
| Computer Vision & NLP | ResNet-18, image classification, NLP |
| Software | Laravel, MySQL, Git, Linux |
| Networks & Security | Cisco, Windows Server, Active Directory, DNS, IIS, GPO |

---

## 📁 Project structure

```
portfolio/
├── index.html          → the whole site (HTML + CSS + JS)
├── images/
│   ├── project-1.jpg   → Pneumonia Detection preview
│   ├── project-2.jpg   → Image Classification preview
│   ├── project-3.jpg   → Apache Storm preview
│   └── project-4.jpg   → Windows Server Security preview
├── docs/
│   ├── demo.gif        → animated demo shown at the top of the README
│   └── screenshots/    → README screenshots (home, about, skills, projects)
└── README.md
```

> The main file is named `portfolio-v5.html` during development. **Rename it to `index.html`** before publishing so GitHub Pages serves it as the home page.

---

## 💻 Run locally

No build step is needed.

```bash
git clone https://github.com/kniksiyassir/portfolio.git
cd portfolio
```

Then either double-click `index.html`, or serve it locally (recommended):

```bash
python -m http.server 8000
```

Open **http://localhost:8000**.

---

## 🌐 Deploy on GitHub Pages

The site is fully static (Supabase is called from the browser), so it runs on **GitHub Pages** without any server.

1. Rename `portfolio-v5.html` to `index.html`.
2. Push the project to GitHub.
3. Open the repository → **Settings** → **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Click **Save** and wait about a minute.

The site is then available at `https://kniksiyassir.github.io/<repository-name>/`.

---

## 🗄️ Supabase configuration

The portfolio reads its content from Supabase tables (for example `site_content` and `skills`) and uses Supabase Auth for the admin panel.

```js
const SUPABASE_URL = "https://<your-project>.supabase.co";
const SUPABASE_ANON_KEY = "<your-publishable-key>";
```

**Security notes**

- Only the **publishable (anon) key** belongs in the front-end. **Never** put the `service_role` key in this repository.
- Enable **Row Level Security (RLS)** on every table: public read access, write access only for the authenticated admin user.
- Create only one admin account and use a strong password.

---

## 📬 Contact

I'm open to a **6-month PFE internship** in **Data Science · Machine Learning · Data Analysis · Artificial Intelligence**.

- 📧 Email: [kniksi.yassir@gmail.com](mailto:kniksi.yassir@gmail.com)
- 💻 GitHub: [@kniksiyassir](https://github.com/kniksiyassir)
- 🔗 LinkedIn: *add your profile link here*

---

<div align="center">

© 2026 Yassir Kniksi · Data Science Portfolio

</div>
