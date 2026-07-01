<!-- ================= HEADER ================= -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=1F6FEB&center=true&vCenter=true&width=750&lines=Hi,+I'm+Rahul+Singh+👋;Software+Engineer;Java+%7C+Spring+Boot+%7C+Kafka;Building+Scalable+Backend+Systems" alt="Typing SVG" />
</div>

<br/>

<h1 align="center">Rahul Singh</h1>
<h3 align="center">Software Engineer | Java Backend Developer | Spring Boot | Microservices</h3>

<div align="center">
  <a href="mailto:contact.rahul82@gmail.com"><img src="https://img.shields.io/badge/Email-contact.rahul82%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://linkedin.com/in/rahul-singh-cs" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

---

## 👨‍💻 Engineering Profile

Results-driven **Software Engineer** specializing in Object-Oriented Programming (OOP), Data Structures & Algorithms, and Distributed Systems. I build structured, scalable, and production-ready server-side applications using **Java, Spring Boot, and Apache Kafka**.

**My Core Focus:**
- 🏗️ **Backend Architecture:** Designing robust RESTful APIs and clean MVC architectures.
- ⚡ **Event-Driven Systems:** Implementing messaging queues (Kafka) and microservices.
- 🗄️ **Database Optimization:** Schema design (3NF), indexing, and performance tuning (SQL).
- 🔐 **Security & Reliability:** Role-Based Access Control (RBAC), data integrity, and fault-tolerant API communication.

🎓 *Currently a Final-Year B.Tech Computer Science student eager to tackle real-world engineering challenges.*

---

## 🛠️ Tech Stack & Tools

<div align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <br/>
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</div>

---

## 🚀 Featured Projects

### 🏦 [Midas Core — Transaction Processing System](https://github.com/Rahul-web01/midas-core)
*JPMorgan Chase Software Engineering Virtual Experience (Forage)*
- Integrated **Apache Kafka** into a Spring Boot microservice to consume and deserialize high-volume financial transaction messages.
- Implemented transaction validation and atomic persistence logic using **Spring Data JPA** and an H2 SQL database.
- Processed dynamic incentive workflows by connecting to an external REST API using `RestTemplate`.

### 📚 [ScholarSpace – Academic Resource Platform](https://github.com/Rahul-web01/Scholarspace-main)
*Java | Spring Boot | MySQL | REST API*
- Designed a scalable backend architecture and RESTful API handling **500+ concurrent users**.
- Implemented a normalized (3NF) MySQL database schema and **optimized high-frequency SQL queries by 40%+** using strategic indexing.
- Built a secure authentication module with Role-Based Access Control (RBAC).

### 💱 [Real-Time Currency Exchange API](https://github.com/Rahul-web01/Currency-Exchange-App)
*Java | JSON Parsing | REST APIs*
- Developed a backend application integrating third-party exchange rate APIs for real-time multi-currency conversion.
- Built robust JSON parsing, exception handling, and retry logic to ensure fault-tolerant communication.

---

## ⚙️ Microservice Architecture Flow

```text
Client Request
      ↓
REST API Controller (Validation)
      ↓
Service Layer (Business Logic) ↔ Apache Kafka (Event Streaming / Messaging)
      ↓
Spring Data JPA / Hibernate (ORM)
      ↓
MySQL / H2 Database
