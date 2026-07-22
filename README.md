# 📄 My Resume — Styled Web Resume Page

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**A clean, modern, single-page HTML + CSS resume — showcasing the professional profile of *Gautam Chauhan*.**

</div>

---

## 📸 Preview

<div align="center">
<img src="resume_preview.png" alt="Resume Page Preview" width="650">
</div>

---

## ✨ Overview

This is a lightweight **HTML + CSS resume page** built with semantic markup and a polished, card-style design. It presents:

- 🧑‍💼 Name, title & contact details
- 📝 A professional summary
- 🎓 Education background
- 💼 Work experience with achievements
- 🛠️ Technical skills
- © Footer with copyright

**Design highlights:**
- 🎨 Soft gradient background (`#e0e7ff → #f0f4ff`) with a dark slate header/footer
- 🃏 Card-style container with rounded corners and a soft drop shadow
- 🔵 Blue accent underlines on section headings
- ✨ Subtle hover effect on each section (light background transition)
- 📱 Fully responsive layout with a mobile breakpoint at `600px`

No frameworks, no dependencies — just pure **HTML5 + CSS3**.

---

## 🗂️ Page Structure (Flowchart)

```mermaid
flowchart TD
    A[📄 My Resume Page] --> S[🎨 CSS Styling Layer]
    A --> B[🏷️ Header]
    A --> C[📝 Summary]
    A --> D[🎓 Education]
    A --> E[💼 Work Experience]
    A --> F[🛠️ Skills]
    A --> G[© Footer]

    S --> S1[Gradient background]
    S --> S2[Card container + shadow]
    S --> S3[Section hover effect]
    S --> S4[Responsive breakpoint]

    B --> B1[Name: Gautam Chauhan]
    B --> B2[Title: Web Developer]
    B --> B3[Contact: Email & Phone]

    D --> D1[B.Tech in Computer Science]
    D --> D2[University of Example - 2020]

    E --> E1[Frontend Developer @ ABC Web Agency]
    E1 --> E2[Developed landing pages]
    E1 --> E3[Collaborated with designers & backend devs]

    F --> F1[HTML & CSS]
    F --> F2[JavaScript]
    F --> F3[Git & GitHub]

    style A fill:#4f46e5,color:#fff,stroke:#333,stroke-width:2px
    style S fill:#ec4899,color:#fff
    style E fill:#f59e0b,color:#fff
    style D fill:#0ea5e9,color:#fff
    style F fill:#10b981,color:#fff
```

---

## 🧱 Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5**  | Page structure & semantic markup |
| **CSS3**   | Styling, layout, gradients, shadows & responsiveness |

---

## 📁 File Structure

```
📦 my-resume
 ┣ 📜 index.html          → Main HTML file (with embedded CSS)
 ┣ 🖼️ resume_preview.png   → Screenshot of the styled page
 ┗ 📄 README.md            → You are here!
```

---

## 🚀 Getting Started

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/your-username/my-resume.git
   ```
2. **Open the file** — no build step needed
   ```bash
   cd my-resume
   open index.html   # or double-click the file
   ```
3. That's it — the resume renders entirely in your browser! 🎉

---

## 🧩 Sections Breakdown

| Section | Tag(s) | Description |
|---|---|---|
| **Header** | `<header>` | Name, job title, email & phone |
| **Summary** | `<section>` | One-line professional overview |
| **Education** | `<section>` | Degree, university & graduation year |
| **Work Experience** | `<section>` + `<ul>` | Role, company, duration & key contributions |
| **Skills** | `<section>` + `<ul>` | Core technical skills |
| **Footer** | `<footer>` | Copyright notice |

---

## 🔮 Future Improvements

- [x] Add CSS styling for a polished, professional layout
- [x] Make the page responsive for mobile & tablet
- [ ] Add a downloadable PDF version button
- [ ] Add icons next to contact details and skills
- [ ] Add a "Projects" section with links
- [ ] Add print-friendly styles for physical resumes
- [ ] Add dark mode toggle

---

## 📬 Contact

| | |
|---|---|
| 📧 **Email** | Gautam.chauhan@example.com |
| 📞 **Phone** | (123) 456-789 |

---

<div align="center">

Made with ❤️ by **Gautam Chauhan**

</div>
