# Audiophile Website 

**Live Demo:** [https://audiophile-website-steel.vercel.app/](https://audiophile-website-steel.vercel.app/)

A responsive e-commerce showcase for high-end audio gear, built as an implementation of the Audiophile 

![React](https://img.shields.io/badge/React-19.2-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.2-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-6.2-646CFF?style=flat-square&logo=vite&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

---

## Table of Contents
- [About](#about)
- [Architecture](#architecture)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Run Locally](#run-locally)
- [Project Structure](#project-structure)

---

## About
This project implements the showcase landing page for the Audiophile e-commerce platform. It presents high-fidelity audio equipment including premium headphones, speakers, and earphones through modular visual sections. The project emphasizes component layout, responsive design across mobile and desktop breakpoints, and clean styling with Tailwind CSS v4.

---

## Architecture
The application is structured into isolated, reusable React components rendered sequentially in `App.jsx`. Component separation mirrors the visual hierarchy of the page, dividing the interface into navigation, hero showcase, category cards, promotional product blocks, brand overview, and footer. Styling is handled with Tailwind CSS v4 via `@tailwindcss/vite`.

---

## Features
- **Hero Presentation**: Highlights the flagship XX99 Mark II headphones with direct call-to-action triggers.
- **Product Category Navigation**: Modular category links for Headphones, Speakers, and Earphones collections.
- **Featured Product Sections**: High-impact promotional blocks showcasing the ZX9 speaker, ZX7 speaker, and YX1 wireless earphones.
- **Brand Story Section**: Contextual brand overview highlighting audio craftsmanship and equipment testing.
- **Responsive Layout**: Fluid flex and grid structures adapted for mobile, tablet, and desktop viewports.
- **Custom Cursor**: Interactive SVG crosshair cursor styling across key interactive elements.

---

## Tech Stack
- **Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS v4
- **Language**: JavaScript (ES6+)
- **Deployment**: GitHub Pages

---

## Run Locally

### Prerequisites
- Node.js (version 18 or higher)
- npm

### Installation
Clone the repository:
```bash
git clone https://github.com/omarahmed321/audiophile-website.git
cd audiophile-website
```

Install dependencies:
```bash
npm install
```

Start the development server:
```bash
npm run dev
```

Build for production:
```bash
npm run build
```

---

## Project Structure
```text
audiophile-website/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   └── ... (product images and media assets)
│   ├── components/
│   │   ├── Aitems.jsx
│   │   ├── BeforeFooter.jsx
│   │   ├── Footer.jsx
│   │   ├── Nav.jsx
│   │   ├── Page2.jsx
│   │   └── Secondpage.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```
