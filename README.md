<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=200&section=header&text=Kha%20Van&fontSize=60&fontAlignY=35&animation=twinkling&fontColor=ffffff" width="100%" />

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=0072ff&center=true&vCenter=true&width=600&lines=Backend+Developer;Software+Engineer;Information+Systems+Student;Passionate+about+Clean+Code" alt="Typing SVG" />
  </a>

  <p><i>Building reliable backend foundations, RESTful APIs, and scalable databases.</i></p>

  <p>
    <a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="[LINK_LINKEDIN]"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  </p>
</div>

---

## 🧠 System Architecture Mindset

```mermaid
graph TD;
    Client([Client / Frontend]) -->|HTTPS / REST| API_GW[API Gateway / Nginx]
    API_GW -->|Routing| AppServer[Node.js / Express Backend]
    AppServer -->|Cache Hit| Redis[(Redis Cache)]
    AppServer -->|Query| DB[(MySQL / PostgreSQL)]
    AppServer -->|External Integrations| ExtAPI[LLM / External APIs]
    
    classDef primary fill:#0072ff,stroke:#000,stroke-width:2px,color:#fff;
    classDef database fill:#4EA94B,stroke:#000,stroke-width:2px,color:#fff;
    classDef cache fill:#DC382D,stroke:#000,stroke-width:2px,color:#fff;
    
    class AppServer primary;
    class DB database;
    class Redis cache;
```

---

## ⚙️ Core Technical Proficiency

<div align="center">
  <h3>💻 Backend & Database</h3>
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,express,postgres,mongodb,redis" alt="Backend" />
  <br><br>

  <h3>🌐 Frontend Support</h3>
  <img src="https://skillicons.dev/icons?i=react,vite,bootstrap,html,css" alt="Frontend" />
  <br><br>

  <h3>☁️ DevOps, Cloud & Tools</h3>
  <img src="https://skillicons.dev/icons?i=docker,aws,git,github,vercel,vitest,postman,vscode,linux" alt="DevOps and Tools" />
</div>

---

## 🚀 Featured Infrastructure

### 🛠️ SmartQuery - AI-Powered Database Assistant
A robust backend service engineered to safely translate natural language into structured SQL queries.
- **Architecture:** Strict separation of text-processing logic from direct database operations.
- **Database Management:** Optimized connection pooling and relational schema design with `MySQL`.
- **Infrastructure:** Fully containerized using `Docker` to ensure parity across environments.

<p><a href="[LINK_TO_SMARTQUERY_REPO]"><strong>🌐 View System Source Code</strong></a></p>

---

## 📈 Current Focus & Roadmap
- 📚 **Infrastructure:** Deep diving into Docker, AWS, and Linux deployment workflows.
- 🎯 **Algorithms:** Continuously solving data structure problems on LeetCode.
- 🗣️ **Communication:** Honing technical English to consume advanced engineering documentation.
