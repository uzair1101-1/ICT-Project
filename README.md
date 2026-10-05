# Student Portfolio Website

A simple two-page personal portfolio website, created as an ICT lab project using only **HTML** and **CSS**.

## About the Project

This website introduces me (Uzair Khan), a Software Engineering student at Capital University of Science and Technology (CUST), Islamabad. It shows my skills, interests, learning journey and contact details.

## Pages

| Page | File | What it shows |
|------|------|---------------|
| Home | `index.html` | Introduction, profile photo, skills and hobbies |
| About | `about.html` | About me, my journey timeline, contact form and social links |

## Features

- Two linked pages with a navigation bar and Next / Back buttons
- Profile photo in a circle
- Skills and hobbies shown as hover-animated cards
- Journey timeline on the About page
- Contact form (HTML form fields with validation)
- Links to GitHub and LinkedIn
- Responsive design that works on mobile, tablet and desktop

## Technologies Used

- **HTML5**: page structure (header, nav, main, section, article, footer, form)
- **CSS3**: all styling and layout, including:
  - Flexbox (navbar, hero section, buttons)
  - CSS Grid (skill cards)
  - CSS variables for colours
  - Hover effects and transitions
  - Media queries for mobile screens

No JavaScript or external libraries are used.

## How I Built It

1. Planned two pages: Home and About.
2. Wrote the page structure in HTML (`index.html` and `about.html`).
3. Styled both pages with one shared CSS file (`style.css`).
4. Linked the pages with a navbar and buttons using `<a href="...">`.
5. Added my photo (`photo.jpg`) inside a round box using `border-radius: 50%` and `object-fit: cover`.
6. Made the layout responsive using a `@media (max-width: 700px)` rule.
7. Tested the pages in a browser.

## Project Structure

```
portfolio/
├── index.html
├── about.html
├── style.css
├── photo.jpg
└── README.md
```

## How to Run

1. Download or clone this repository.
2. Keep all files in the same folder.
3. Double-click `index.html` to open it in any web browser.

## Contact

- GitHub: [uzair1101-1](https://github.com/uzair1101-1)
- Location: Pakistan

---
Created by Uzair Khan | ICT Project
