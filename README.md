# 🌐 Colmar Academy Webpage Project

➡️ **Live Demo:**  
https://danialzac.github.io/fsd-colmar-academy-danial/

This project is a full front-end build of the **Colmar Academy landing page**, based on Codecademy’s specifications.

I built the site across multiple branches to document my development process.

---

## 🏷 Git Branches Used

| Branch                 | Purpose                                         |
| ---------------------- | ----------------------------------------------- |
| `main`                 | Initial HTML skeleton                           |
| `version1`             | Desktop layout styling                          |
| `version1_1`           | First responsive attempt                        |
| `version2`             | ⭐ Final working version (desktop + responsive) |
| `Instructor’s-Version` | Reference branch (not my code)                  |

➡️ I am currently working in **`version2`**

---

## 🚀 Deployment

The site is deployed using **GitHub Pages**.

To update the live version, I run:

```sh
git add .
git commit -m "update"
git push

🖥️ 1. Setting Up the Skeleton
🎯 Objective

---

## 🖥️ 1. Skeleton Setup (Branch: `main`)

### 🎯 Purpose
This branch contains the **initial project setup** — creating `index.html` and linking the project folders, before any CSS or layout styling was added.

### 📄 Files Created

| File | Purpose |
|------|---------|
| `index.html` | Base HTML document |
| `assets/` | Folder for images & media |
| `styles/` | Folder for CSS |

### 🔑 Key Notes
- Only **semantic HTML structure** existed at this point.
- No layout or styling was added yet.
- Sections were marked with `<!-- TODO -->` comments for later development.

---

## 🖥️ 2. Desktop Layout (Branch: `version1`)

### 🎯 Purpose
This branch introduces **full desktop styling** using CSS Flexbox and Grid.

### Key Additions
- Navigation bar
- Hero banner
- Practice + Events sections
- Desktop typography and colors
- Footer

---

## 🛠 3. Responsive Layout (Branches: `version1_1` → `version2`)

| Branch | What Happened |
|--------|---------------|
| `version1_1` | First attempt at mobile responsiveness |
| `version2` | ⭐ Final working version — fully responsive |

### Key Mobile Fixes
- Mobile navbar added
- Images replaced with mobile variants
- Flex sections stack vertically
- Text resized for small screens
- Hidden desktop elements using `display: none`

---

### 🚀 Final Result

✔ Desktop & mobile views both working
✔ Matches Codecademy design specs
✔ Live deployment via GitHub Pages:

👉 https://danialzac.github.io/fsd-colmar-academy-danial/

---

---

## 🚀 Live Deployment

My final working version is live here:

👉 **https://danialzac.github.io/fsd-colmar-academy-danial/**

✔ Hosted on GitHub Pages
✔ Built from branch `version2`
✔ Fully responsive


🖥️ 1️⃣ Setting Up the Skeleton
🎯 Objective
Create the base HTML structure using semantic tags — no CSS yet.

## 🗂️ Files Used

| File / Folder | Purpose |
|---------------|---------|
| `index.html` | Main HTML structure |
| `styles/styles.css` | Styling for all sections |
| `assets/images/` | Images used across the site |
| `assets/videos/` | Thesis exhibit video |



🛠 Tasks Completed
✔ Added semantic structural elements
✔ Inserted <!-- TODO --> placeholders
✔ Divided the page into meaningful sections

🧩 Key HTML Concepts
ConceptPurpose<header>, <nav>, <section>, <footer>Semantic layout structure<!DOCTYPE html>Defines HTML5<meta charset="UTF-8">Required for special characters<meta name="viewport" …>Enables responsive behaviorComments (<!-- -->)Mark future work

🏗 Base Layout Structure
<body>

  <nav></nav>

  <header></header>

  <section id="practice"></section>

  <section id="events"></section>

  <section id="learning"></section>

  <section id="thesis"></section>

  <footer></footer>

</body>


🖥️ 2️⃣ Creating the Desktop Design
🎯 Objective
Convert the HTML skeleton into a fully styled desktop webpage.

🗂 Files Used


index.html


styles/styles.css



🛠 Tasks Completed
✔ Added images and text content
✔ Styled the page using Flexbox + Grid
✔ Built navbar, header, practice, events, and footer sections
✔ Applied typography + button styles

💡 CSS Concepts Used
ConceptPurposedisplay: flexAlign navigation + practice sectiondisplay: gridLayout content blockshover statesInteractive linksfont-weightVisual hierarchymax-width imagesPrevent overflow

🧭 Navbar Example
<nav>
  <a href="#">
    <img src="assets/images/ic-logo.svg" alt="Colmar Logo">
    <span class="logoname-bold">Colmar</span>
    <span class="logoname-light">Academy</span>
  </a>

  <ul>
    <li><a href="#">Campus</a></li>
    <li><a href="#">Online</a></li>
    <li><a href="#">Companies</a></li>
    <li><a href="#">Sign in</a></li>
  </ul>
</nav>


📱 3️⃣ Creating the Responsive Mode
🎯 Objective
Make the webpage fully responsive for tablet and mobile screens.

🗂 Files Used


index.html
styles/styles.css

🎨 Styling Techniques Used
Feature	Tool Used
Global Reset	*{ margin:0; padding:0; }
Page Layout	CSS Grid (container class)
Section Layout	Flexbox (nav, practice, events blocks)
Font Consistency	System font stack (Arial / Helvetica)
Design Tokens	CSS Variables (--transition-speed, --border-radius)
Hover Effects	Button hover transition
Card UI	Borders, shadows, spacing
Responsive Images	max-width:100% + object-fit:cover

🧩 Desktop Page Behavior

✔ Navbar logo + links aligned with Flexbox
✔ Two-column hero section (image left, text right)
✔ Grid layout for learning cards (3 × 2)
✔ Thesis section contains a self-playing muted video
✔ Footer spans full width


🛠 Tasks Completed
✔ Created mobile navbar (#nav-mobile)
✔ Used media queries to restructure layout under 640px
✔ Swapped images for smaller devices
✔ Adjusted font sizes and spacing
✔ Made thesis video responsive

📱 3️⃣ Responsive Design (version1_1 → version2)
🎯 Objective

Convert the desktop layout into a fully responsive mobile-first experience using media queries.

🔧 Key Features Added
Mobile Feature	Implementation
Mobile Navbar	New <nav id="nav-mobile"> showing icons only
Hide Desktop Nav	display: none; inside media query
Mobile Event Images	class="events-img-mobile" only shown under 640px
Layout Stack	Flex → Column, Grid → Single column
Larger Tap Targets	Increased font sizes + spacing
Mobile Typography	font-size: xx-large for headings

🧪 Final Completion Checklist
RequirementStatusHTML skeleton✅Desktop styling✅Responsive mode✅Semantic elements✅Git branches✅Deployment✅

🏁 Result
🎉 version2 contains the final working desktop + mobile website
📱 Fully responsive on small screens
🖥 Matches Codecademy desktop spec
🚀 Successfully deployed via GitHub Pages

👤 Author
Name: <Danial>
GitHub Repo: <version2>
Live Site: <https://danialzac.github.io/fsd-colmar-academy-danial/>

