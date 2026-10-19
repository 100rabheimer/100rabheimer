# Hi there, I'm Saurabh Pandey 👋

## About Me

I am a **Backend-GenAI Full Stack Developer** and B.Tech Information Technology student (Class of 2028) at KIET Group of Institutions.

I enjoy working close to the backend — designing clean APIs, managing data flows, containerizing services, and making systems behave reliably under load.

---

## Tech Stack I Use

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Frontend & Backend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### AI / GenAI
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### Tools
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Projects

### 💳 [MeterForge](https://github.com/100rabheimer/MeterForge) — Usage Metering & Billing Engine
*FlyRankAI internship capstone*

- Multi-tenant metering backend for API calls and AI tokens
- **Exactly-once metering** using idempotency keys (`ON CONFLICT DO NOTHING RETURNING`)
- Monthly quota enforcement with clear `429` / `402` responses
- Integer milli-cent cost calculation to avoid floating-point billing errors
- Stripe Checkout + signature-verified, deduplicated webhooks
- Dockerized PostgreSQL setup

`Node.js` `Express` `PostgreSQL` `Docker` `Stripe`

---

### ✍️ [InkAPI](https://github.com/100rabheimer/inkapi) — Blog Backend with Redis Caching
**[Live Demo](https://inkapi-nkj1.onrender.com/)**

- JWT access + refresh-token authentication with bcrypt password hashing
- Posts, comments and likes with author-based authorization
- Redis cache-aside strategy with invalidation on writes (`X-Cache: HIT/MISS`)
- Pagination, request validation, rate limiting and Helmet
- PostgreSQL (Neon) with foreign keys, cascading deletes and unique-like constraints
- **15 automated API tests** with Jest + Supertest

`Node.js` `Express` `PostgreSQL` `Redis` `JWT` `Jest`

---

### 🧾 [InvoiceIQ](https://github.com/100rabheimer/InvoiceIQ) — AI-Powered Invoice Processing
- End-to-end pipeline: Tesseract OCR → LayoutLM → rule-based validation
- Extracts company, date, address and total from invoice images
- FastAPI ML service + Express.js/MongoDB backend + React analytics dashboard
- JWT authentication, search, filter and pagination

`React` `Node.js` `FastAPI` `MongoDB` `LayoutLM`

---

### 🍃 [VaayuAI](https://github.com/100rabheimer/vaayu-ai) — Delhi-NCR Air Quality Sentinel
**[Live Demo](https://delhi-aqi-sentinel.vercel.app/)**

- Dual-sided platform for citizens and policymakers
- Cleanest-commute route planner balancing travel time against pollution exposure
- GRAP policy simulation sandbox with a heuristic recommender and weighted AQI forecasting
- Offline-capable PWA

`React` `Vite` `Node.js` `Recharts` `Vercel`

---

### 📚 [Polite Scraper](https://github.com/100rabheimer/polite-scraper) — Cache-First Scraping Pipeline
- Discovers and scrapes 60 book pages across 3 catalogue pages
- Caches HTML, de-duplicates URLs and survives individual page failures
- Normalizes data and validates every record with Zod
- Separates valid and invalid records and generates a report per run

`Node.js` `Cheerio` `Zod`

---

## 🏆 Problem Solving

[![LeetCode](https://img.shields.io/badge/LeetCode-100rabheimer-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/100rabheimer/)

![LeetCode Stats](https://leetcard.jacoblin.cool/100rabheimer?theme=dark&font=baloo&ext=heatmap)

## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=100rabheimer&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=100rabheimer&theme=tokyonight&hide_border=true" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=100rabheimer&layout=compact&theme=tokyonight&hide_border=true" height="160"/>
</p>

---

## 📬 Contact

<p align="center">
  <a href="https://github.com/100rabheimer">
    <img src="https://img.shields.io/badge/GitHub-100rabheimer-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/saurabh-pandey-46532032b/">
    <img src="https://img.shields.io/badge/LinkedIn-Saurabh%20Pandey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://leetcode.com/u/100rabheimer/">
    <img src="https://img.shields.io/badge/LeetCode-100rabheimer-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  &nbsp;
  <a href="mailto:shaurabhipandey@gmail.com">
    <img src="https://img.shields.io/badge/Email-shaurabhipandey%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
