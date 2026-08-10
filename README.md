<h1 align="center">Hi 👋, I'm Mrinal Anand</h1>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=AI+Product+Engineer;Full-Stack+Developer+%7C+React+%C2%B7+Node+%C2%B7+Python;I+ship+production+LLM+features+end+to+end&font=Fira%20Code&center=true&width=520&height=45&color=0e75b6&vCenter=true&size=22" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/mrinalanand2001"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@mrinalanand"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="mailto:mrinalanandiem@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=mrinalcom&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="views"/>
</p>

---

### 🚀 About Me

- 🤖 **AI Product Engineer** — I build and ship production **LLM features end to end** using the Claude API, LangChain, LangGraph, and AI agents.
- 🔭 Currently a **Software Engineer at AMI**, building an in-house enterprise chatbot and predictive server-monitoring models.
- ⚡ **Founding-engineer background** — led full-stack development of a React Native / Node.js app to **1,000+ early adopters** as the first engineer.
- 🛠️ Comfortable across the whole stack: **React / React Native, Node.js, Python, PostgreSQL, Redis, AWS, Docker, CI/CD**.
- 🧠 Strong fundamentals — **1,000+ DSA problems solved** and an active competitive-programming habit.
- 📝 I write about engineering on [Medium](https://medium.com/@mrinalanand).

---

### 🧩 Featured Projects

**[HIS](https://github.com/MrinalCom/HIS) — Full-Stack + AI Hospital Information System**
`Next.js` · `Node.js/TypeScript` · `PostgreSQL` · `Redis` · `Socket.io` · `Claude API` · `LangGraph` · `FastAPI/scikit-learn` · `Docker`

- End-to-end hospital platform across 9 modules — scheduling, EHR, pharmacy, lab, billing, HR, bed/ward management, ambulance dispatch, and 1:1 WebRTC telemedicine — as 8 role-scoped dashboards (patient, doctor, nurse, pharmacist, lab tech, receptionist, billing clerk, admin).
- **Four AI features**, each with a deterministic fallback so the frontend never has two code paths: an AI triage chatbot with a keyword red-flag safety net that overrides the model, a LangGraph booking concierge, AI-drafted SOAP notes that are never auto-signed, and a real scikit-learn no-show classifier served by a FastAPI microservice.
- Models a HIPAA-conscious security posture: capability-based RBAC, live-checked MFA enrollment gating sensitive writes, append-only audit logging enforced at the Postgres privilege level (WORM), and encrypted-at-rest staff bank details.

**[RestroHub](https://github.com/MrinalCom/RestroHub) — Restaurant Management & AI Ordering Platform**
`Next.js` · `Node.js/TypeScript` · `PostgreSQL` · `Redis` · `Socket.io` · `Claude API` · `Docker`

- Real-time order flow: customer ordering, a live kitchen queue over **Socket.io**, and an owner dashboard for menu, pricing, and inventory — orchestrated with **Docker Compose**.
- A **mood-based dish recommender**: LLM structured extraction into a 5-dimension taste vector, cosine-similarity matching, and hybrid ranking on popularity + stock signals.
- Cached the LLM extraction layer in **Redis** to cut cost and latency, and logged recommendation-to-conversion data to train a future learned ranker.

**[Research Crew](https://github.com/MrinalCom/research-crew) — Multi-Agent LangGraph Research/Coding Crew**
`LangGraph` · `FastAPI` · `React` · `PostgreSQL` · `Claude API` · `Docker`

- Supervisor-led agent crew (planner → researcher + analyst running **concurrently** → coder → reviewer) with a **provably-bounded self-correction loop** and durable **human-in-the-loop approval** built on LangGraph's `interrupt()`.
- Postgres/SQLite checkpointing with full **time-travel replay** from any past checkpoint, streamed live to the frontend over Server-Sent Events.
- React frontend visualizing the live graph topology, per-node agent activity, and the approval flow in real time.

**[QR File Transfer](https://github.com/MrinalCom/QR-FileTransfer) — Peer-to-Peer File Sharing over WebRTC**
`TypeScript` · `Vite` · `WebRTC` · `Node.js` · `WebSocket`

- Device-to-device file transfer with no account or app install: the sender gets an invite QR, the receiver scans it and shows a pairing QR back, and the sender confirms it in-app — a lightweight, login-free proof that a human controls both screens.
- File bytes flow **directly over a WebRTC data channel**; the Node/`ws` signaling server only relays connection setup messages and never touches the file itself.
- In-memory, single-use sessions with automatic TTL expiry — no database, minimal server-side state to secure or clean up.

---

### 💼 Experience Highlights

- **AMI** — *Software Engineer* · Launched an enterprise AI chatbot adopted by 25 support reps in its first month; building predictive models that flag server bottlenecks before they hit latency.
- **Neurolaw AI** — *AI Intern* · Shipped production AI features across three products (legal chatbot, document translation, True Copy) and automated a large-scale data pipeline with Python + Selenium, cutting manual effort by **90%**.
- **Strength** — *Founding Engineer* · Built the React Native / Node.js app from scratch to **1,000+ users**; cut query latency **30%** with Redis caching and automated the Docker CI/CD pipeline.

---

### 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**AI / LLM**

![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-6E56CF?style=flat&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat&logoColor=white)
![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socketdotio&logoColor=white)

**Data & Cloud**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 🏆 Achievements & Certifications

- 🥉 **3rd Place, Hackfest 2023 (IIT Dhanbad)** — top 3 of 50+ teams in the ABIT track.
- 📈 **Top 2.5%, TATA Imagination Challenge** — ranked 6,415 of 263,654 nationally.
- 💻 **1,000+ DSA problems** solved · 500-day GeeksforGeeks streak.
- 📜 **AWS Cloud Practitioner** · **Google Cloud Associate** · **IBM DevOps** · **HackerRank REST API**.

---

### 📊 GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=mrinalcom&show_icons=true&theme=tokyonight&hide_border=true" alt="stats" />
  <img width="41%" src="https://github-readme-stats.vercel.app/api/top-langs?username=mrinalcom&layout=compact&theme=tokyonight&hide_border=true" alt="top langs" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mrinalcom&theme=tokyonight&hide_border=true" alt="streak" />
</p>

---

### 🔗 Competitive Programming

<p align="left">
  <a href="https://leetcode.com/mrinalanand9155674769"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://codeforces.com/profile/mrinalanand"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat&logo=codeforces&logoColor=white" alt="Codeforces"/></a>
  <a href="https://www.codechef.com/users/mrinal_01"><img src="https://img.shields.io/badge/CodeChef-5B4638?style=flat&logo=codechef&logoColor=white" alt="CodeChef"/></a>
</p>
