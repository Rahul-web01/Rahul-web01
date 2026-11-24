<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=D4AF37&center=true&vCenter=true&width=750&lines=Hi%2C+I'm+Rahul+Singh+%F0%9F%91%8B;Backend+Software+Engineer;Java+%7C+Spring+Boot+%7C+Apache+Kafka;I+build+things+people+actually+use" alt="Hi, I'm Rahul Singh — Backend Software Engineer" />

<h3>Software Engineer &nbsp;·&nbsp; Java Backend Developer &nbsp;·&nbsp; Spring Boot &nbsp;·&nbsp; Microservices</h3>

<p>
  <a href="https://rahul-s-professional-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-D4AF37?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/rahul-singh-cs"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:contact.rahul82@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://komarev.com/ghpvc/?username=Rahul-web01&color=D4AF37&style=flat-square&label=Profile+Views" alt="Profile views" />

</div>

## 👨‍💻 About me

Backend-focused **Software Engineer** who builds and ships complete products with **Java, Spring Boot and Apache Kafka**,
from event-driven microservices to secured, Dockerized web apps and local-AI automation tools.
Completed the **JPMorgan Chase Software Engineering Job Simulation**, building a Kafka-based transaction-processing microservice.

- 🏗️ **Backend architecture**: REST APIs and clean layered Spring applications (Controller → Service → Repository)
- ⚡ **Event-driven systems**: Apache Kafka messaging and microservice communication
- 🔐 **Security & reliability**: Spring Security role-based access, BCrypt, CSRF, validation and global error handling
- 🤖 **Automation & AI**: Playwright browser automation and local LLMs (Ollama) for privacy-first tools
- ✅ HackerRank-certified in **SQL (Advanced)** and **Java**, with a strong foundation in DSA and OOP

🎓 B.Tech in Computer Science & Engineering (2023–2027), Babu Banarasi Das University, Lucknow<br/>
📍 Lucknow, Uttar Pradesh, India · open to Software Engineering roles

---

## ⚡ Tech stack

<table width="100%">
<tr>
<td width="50%" valign="top">

### 💻 Languages
<img src="https://skillicons.dev/icons?i=java,python,js,ts" />

### ⚙️ Backend & frameworks
<img src="https://skillicons.dev/icons?i=spring,maven" />
<br/><sub>Spring Boot • Spring MVC • Spring Security • Spring Data JPA • Hibernate • Thymeleaf</sub>

### 🗄️ Databases
<img src="https://skillicons.dev/icons?i=mysql,sqlite" />
<br/><sub>MySQL • TiDB Cloud • H2 • SQLite (FTS5)</sub>

</td>
<td width="50%" valign="top">

### ☁️ Cloud, DevOps & tools
<img src="https://skillicons.dev/icons?i=docker,git,github,linux,aws,vercel" />
<br/><sub>Docker • Render • Vercel • CI/CD • JUnit 5 • Mockito • Postman • IntelliJ IDEA</sub>

### 🎨 Frontend
<img src="https://skillicons.dev/icons?i=react,tailwind,vite,html,css" />

### 🧠 Architecture & automation
<sub>Apache Kafka • Microservices • Event-driven architecture • REST APIs • Playwright • Ollama (local LLMs)</sub>

</td>
</tr>
</table>

---

## 🚀 Featured Projects

### 🧭 [JobPilot: private AI job-search assistant](https://github.com/Rahul-web01/job-pilot)
*Nov 2026* · [🎬 See demo](https://github.com/Rahul-web01/job-pilot#demo)

- Local-first Spring Boot app that pulls jobs from **Greenhouse, Lever and Remotive** APIs and scores each one **0–100** against the user's titles, skills and locations
- Tailors a resume summary and cover letter per job with a free local LLM (**Ollama**) and renders them as PDFs; experience and projects are copied verbatim so the AI can't invent anything
- Auto-fills real application forms with **Playwright** (never auto-submits), finds published HR emails, and sends outreach through Gmail SMTP with follow-up reminders and a daily limit

**Stack:** `Java 21` `Spring Boot` `H2` `Thymeleaf` `Playwright` `Ollama` `PDFBox`

### 🏦 [Midas Core: Kafka transaction-processing microservice](https://github.com/Rahul-web01/midas-core)
*JPMorgan Chase Software Engineering Job Simulation (Forage) · Jul 2026*

- Spring Boot microservice that consumes and deserializes transaction messages from **Apache Kafka**, tested with an embedded Kafka broker
- Validates transactions and updates balances with **Spring Data JPA** entities on H2
- Calls an external REST incentive API with `RestTemplate` and exposes a JSON balance-query endpoint

**Stack:** `Java` `Spring Boot` `Apache Kafka` `Spring Data JPA` `H2` `JUnit`

### 👔 [Employee Management System](https://github.com/Rahul-web01/Employee-Management-System)
*Oct 2026* · [🌐 Live demo](https://employee-management-system-yuzi.onrender.com/)

- Full-stack CRUD app for employees and departments with a layered Spring Boot architecture, built during a Java Full Stack internship at **Adyapan**
- **Spring Security** login with three roles (Admin, HR, Viewer), BCrypt passwords, CSRF protection and server-side access checks
- Bean validation, duplicate-email protection and a global exception handler; tested with JUnit 5, Mockito and MockMvc
- Deployed as a multi-stage **Docker** image on Render with a MySQL-compatible **TiDB Cloud** database over TLS

**Stack:** `Java 17` `Spring Boot` `Spring Security` `Spring Data JPA` `Thymeleaf` `MySQL` `Docker`

### 📚 [ScholarSpace: free study-material hub](https://github.com/Rahul-web01/Scholarspace-main)
*Aug 2025* · [🌐 Live site](https://scholarspace-main.vercel.app/)

- Notes, previous-year papers and practice sets for university students: **750+ files across 90 subjects**, organised by college, course and year
- **Ask Notes**: a Python serverless search API with an SQLite FTS5 index and BM25 ranking that searches inside every PDF, Word and PowerPoint file, including OCR'd handwritten pages
- Python tools crawl Google Drive and build the catalogue; moderated student uploads, an SGPA calculator, and light/dark mode

**Stack:** `Python` `SQLite FTS5` `JavaScript` `HTML/CSS` `Google Drive` `Vercel`

### 💱 [Live Currency Converter](https://github.com/Rahul-web01/Currency-Exchange-App)
*Jan 2026* · [🌐 Live demo](https://currency-exchange-dackf2w6x-rahuls-projects-98687e81.vercel.app/)

- Converts between **160+ currencies** at live market rates that refresh every 60 seconds
- **30-day trend chart** with percent change, low and high, from ECB data
- Cancels stale requests, retries automatically, and is accessible (labelled inputs, live-region announcements, reduced motion)

**Stack:** `React` `Vite` `Tailwind CSS` `REST APIs`

---

## 📜 Certifications

- SQL (Advanced) · HackerRank
- Java (Basic) · HackerRank
- Communication Skills · TCS iON
- YUVA AI For All · TCS iON × IndiaAI
- AI & Cybersecurity Awareness · MPIT-CoE

## 🏅 Achievements & competitions

- **Zomathon**: data hackathon (Coding Ninjas × Zomato), applying data analytics to a real business case
- **NationBuilding Case Study Competition 2026** (Unstop) and **AINCAT 2026** (Naukri Campus)

---

<div align="center">

**📫 Let's connect. I'm open to Software Engineering opportunities.**

<a href="https://rahul-s-professional-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-D4AF37?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" /></a>
<a href="https://linkedin.com/in/rahul-singh-cs"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:contact.rahul82@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>
