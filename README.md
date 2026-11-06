<div align="center">

# Pranav Malap

**Full-Stack Developer · M.Sc. Web Engineering student at TU Chemnitz, Germany**

I build web applications end to end, from REST APIs and data pipelines to React front ends,<br>
and I am increasingly bringing AI into them.

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--prav.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-prav.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pranavmalap-0A66C2?style=flat-square)](https://www.linkedin.com/in/pranavmalap)
[![Email](https://img.shields.io/badge/Email-pranavmalap.de%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:pranavmalap.de@gmail.com)

</div>

---

## About me

- Master's student in **Web Engineering** at **TU Chemnitz**, based in Chemnitz, Germany
- **Web developer internship** at Ace 360 Degree, Mumbai: shipped features in Laravel, CodeIgniter and React / Next.js
- Recent work: an **AI resume analyzer** (FastAPI + OpenAI), an **open-data ETL pipeline and REST API**, and a team **company website** for a university startup simulation
- Open to **Werkstudent and internship** roles in Germany
- Languages: English, German (B1, still learning), Hindi and Marathi

## Tech stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Backend**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?style=flat-square&logo=codeigniter&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

**Data & AI**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**DevOps & tools**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

## Featured projects

### [TalentLens](https://github.com/pranavmalap/talentlens) · AI resume analyzer

Upload a resume (PDF) and a job description to get an ATS-style match score, missing skills and concrete suggestions. Every analysis is saved and can be reopened.

- OpenAI prompt with JSON-mode output and a validation step, so malformed AI output never reaches the database
- FastAPI REST API with clear error handling, PDF text extraction (pdfplumber), PostgreSQL with Alembic migrations
- pytest suite (mocked OpenAI, in-memory SQLite), GitHub Actions CI, the full app runs with Docker Compose

`React` `FastAPI` `PostgreSQL` `OpenAI API` `Docker` `pytest` `GitHub Actions`

### [UnfallHub](https://github.com/pranavmalap/unfallhub) · German road-accident data API

Course project for *Datenbanken und Web-Techniken* at TU Chemnitz: five official German open-data sources on road accidents, integrated into one queryable API.

- ETL script that loads Unfallatlas (2021 to 2023), Regionalstatistik and Destatis data into a normalized PostgreSQL schema
- Node.js / Express REST API, documented with OpenAPI 3.0 and Swagger UI
- Browser query explorer with Chart.js charts and Leaflet maps

`Node.js` `Express` `PostgreSQL` `ETL` `OpenAPI` `Chart.js` `Leaflet`

### [ReportWise](https://github.com/pranavmalap/reportwise) · Offline report summarizer

Turns PDF, Word and text reports into short summaries using a local Hugging Face model: no API key, no per-call cost, and no data leaves the machine.

- Text extraction and cleanup for PDF / DOCX, sentence-aware chunking to fit the model's input limit
- Adjustable summary length, bullet view, word-reduction stats and download as `.txt`

`Python` `Hugging Face Transformers` `Streamlit` `pypdf` `python-docx`

### More projects

- **[Portfolio](https://github.com/pranavmalap/portfolio)**: my personal website, live at [portfolio-prav.vercel.app](https://portfolio-prav.vercel.app/) · `Next.js` `React` `Tailwind CSS` `GSAP`
- **[Innosteelix](https://github.com/pranavmalap/innosteelix)**: business website built during my web developer internship · `Laravel` `MySQL`
- **[FoodieConnect](https://github.com/pranavmalap/foodieconnect)**: recipe-sharing platform with accounts, likes, comments and an admin view · `React` `Node.js` `Express` `MongoDB`

## Team projects

Repositories owned by other people or teams, where I contributed as a team member.

### [DenkByte website](https://github.com/snrahman01/denkbyte-website) · contributor

Company website of **DenkByte**, a 9-person student startup in the *Planspiel Web Engineering* course at TU Chemnitz. Live at [denkbyte.netlify.app](https://denkbyte.netlify.app/). Repository owned by [@snrahman01](https://github.com/snrahman01).

My contributions ([#3](https://github.com/snrahman01/denkbyte-website/pull/3), [#4](https://github.com/snrahman01/denkbyte-website/pull/4)):

- Moved the styling to **Tailwind CSS v4** with shared UI components, and split the one-page site into **React Router** pages
- Built the **GSAP** intro loader, a scroll-driven intro and an animated mobile menu, plus a mobile-first pass over every page
- Added the 404 page, the Imprint and GDPR privacy pages, and a patch-notes page for company updates

`React` `TypeScript` `Vite` `Tailwind CSS` `React Router` `GSAP` `Netlify`

## Currently learning

- Cloud and web application architecture: Docker Compose, message queues, CI/CD
- ETL pipelines and working with open data
- Agentic AI tooling
- German, working towards B2

## Experience

**Web Developer Intern** · Ace 360 Degree, Mumbai · Dec 2024 to Aug 2025

- Shipped features on a sales CRM in CodeIgniter 3 and migrated a legacy project to Laravel
- Built SEO-optimized landing pages and business websites (Laravel / MySQL, Next.js / Redux)
- Learned React and Next.js on the job and used them in production

## Education

- **M.Sc. Web Engineering**, TU Chemnitz, Germany · in progress
- **B.Sc. Information Technology**, University of Mumbai · CGPA 9.58 / 10
- **Java Full Stack Development** certificate, DVOC Institute

## GitHub stats

<div align="center">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=pranavmalap&theme=github_dark" alt="Contribution graph and profile summary" />
</div>

<div align="center">
  <img height="165" src="https://github-stats-extended.vercel.app/api?username=pranavmalap&show_icons=true&theme=github_dark&hide_border=true&count_private=true&hide_rank=true&hide=stars" alt="Pranav's GitHub stats" />
  <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=pranavmalap&layout=compact&theme=github_dark&hide_border=true&hide=blade" alt="Most used languages" />
</div>

<div align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=pranavmalap&theme=github-dark-blue&hide_border=true&background=0D1117" alt="Contribution streak" />
</div>
