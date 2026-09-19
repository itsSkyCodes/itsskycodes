![](https://capsule-render.vercel.app/api?type=waving&color=0:0e75b6,100:0d1117&height=220&section=header&text=Shyam%20Kumar%20Yadav&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Software%20Developer%20%7C%20NestJS%20%C2%B7%20TypeScript%20%C2%B7%20GenAI%20%C2%B7%20PostgreSQL&descAlignY=58&descSize=18&animation=fadeIn)

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=0E75B6&center=true&vCenter=true&random=false&width=750&lines=Hey+there!+I'm+Shyam+Kumar+Yadav+%F0%9F%91%8B;Full-Stack+Software+Developer+%40+Luminoguru+%F0%9F%8F%A2;NestJS+%C2%B7+TypeScript+%C2%B7+PostgreSQL+%E2%9A%A1;Building+Multi-Tenant+SaaS+at+Scale+(20%2B+Tenants)+%F0%9F%9A%80;GenAI+%26+Agentic+Pipelines+(CrewAI+%2B+Pinecone+RAG)+%F0%9F%A4%96;High-Performance+APIs+%C2%B7+Real-Time+Systems+%F0%9F%94%A5)

![](https://komarev.com/ghpvc/?username=itsskycodes&label=Profile+Views&color=0e75b6&style=for-the-badge)![](https://img.shields.io/github/followers/itsskycodes?label=Followers&style=for-the-badge&color=0e75b6&labelColor=0d1117)![](https://img.shields.io/badge/Open%20To-Collaborate-brightgreen?style=for-the-badge&labelColor=0d1117)![](https://img.shields.io/badge/Based%20In-Chandigarh%2C%20India%20🇮🇳-blue?style=for-the-badge&labelColor=0d1117)

---

## 🧠 About Me

Full-stack software engineer with 4+ years of experience shipping production systems end-to-end, from database schema design to deployment and team leadership. I built **MyRelma**, a multi-tenant career-coaching SaaS platform, from zero to production. It now serves 20+ tenant organizations at 99%+ uptime. I also build AI-powered tooling (LLM orchestration, RAG, real-time streaming) and have delivered systems across healthcare diagnostics, inventory/ERP, and fitness booking.

```typescript
const ShyamKumarYadav = {
  location: 'Chandigarh, India',
  role: 'Software Engineer @ Luminoguru Pvt. Ltd., Mohali',
  experience: '4+ years shipping production systems end-to-end',
  education:
    'MCA — Lovely Professional University (2021–2023) | BCA — Panjab University (2017–2020)',
  currentFocus: [
    'Leading architecture of multi-tenant SaaS (MyRelma) — 20+ tenants, 99%+ uptime',
    'Agentic AI workflows & RAG pipelines with CrewAI, OpenAI GPT-4o & Pinecone',
    'High-throughput real-time systems (SSE, WebSockets, BullMQ)',
  ],
  domains: [
    'Multi-Tenant SaaS',
    'Generative AI & LLM Orchestration',
    'Healthcare Diagnostics (FHIR / DICOM)',
    'Inventory & ERP Integration',
    'Social & Real-Time Event Platforms',
  ],
  askMeAbout: [
    'NestJS & TypeScript backend architecture',
    'Database optimization & query performance tuning',
    'RAG pipelines & agentic LLM routing',
    'Distributed rate limiting & system security',
  ],
  contact: 'shyamsky1914@gmail.com',
  portfolio: 'https://its-sky-portfolio.vercel.app',
};
```

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shyam-kumar-yadav-5827431a6)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://its-sky-portfolio.vercel.app)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shyamsky1914@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/itsSkyCodes)

---

## 💼 Work Experience

### **Software Engineer** — [Luminoguru Pvt. Ltd.](https://luminoguru.com/) *(Mohali, India)*
*Jan 2022 – Present*

#### 🚀 **MyRelma — Multi-Tenant Career-Coaching SaaS Platform**
`NestJS` · `TypeScript` · `PostgreSQL` · `TypeORM` · `Redis` · `BullMQ` · `OpenAI GPT-4o` · `CrewAI` · `Pinecone` · `Pusher` · `Cloudflare R2` · `Google APIs` · `LinkedIn API`  
*Jun 2025 – Present*

- **End-to-end SaaS architecture:** Built the platform from zero to production: a 27-module NestJS REST API, PostgreSQL/TypeORM data modeling, and Redis/BullMQ background processing across 10 job queues. It serves **20+ tenant organizations** at **99%+ uptime**, and I lead a 3-person engineering team.
- **Generative AI career assistant:** Engineered a FastAPI + CrewAI + OpenAI GPT-4o + Pinecone RAG microservice with 6 production API endpoints covering multi-format resume parsing (PDF, DOCX, JPEG, PNG), section-by-section rewriting, full resume audits with scoring, SSE-streamed conversational chat (LLM classifier routing across 9 message types), and AI email drafting. Includes structured Pydantic outputs, token-usage tracking, and per-user rate limiting.
- **AI email composition & integrations:** Built an OpenAI-powered assistant that streams context-aware, thread-aware drafts via SSE. Integrated Google Workspace (Gmail sync, Contacts, Calendar, Tasks) and LinkedIn OAuth.
- **Security & reliability:** Implemented Redis-backed distributed rate limiting with Postgres failover, per-email auth throttling against OTP brute-force, Helmet HTTP hardening, TLS/CORS enforcement, and graceful shutdown handling.

---

#### 📦 **IMS Link — Inventory Management System (App + API)**
`Angular` · `TypeScript` · `Hapi.js` · `MySQL` · `node-cron`  
*May 2022 – Jun 2025*

- **Performance:** Reduced API response times by **50–60%** (validated via production latency profiling) by optimizing MySQL queries, eliminating N+1 patterns, and refactoring bottlenecks across inventory, serial-tracking, and work-order modules.
- **Operations modules:** Built item receiving (barcode scanning), warehouse stocking, order picking, serial-number lifecycle tracking, BOM management, and shortage ticketing, with an Angular frontend, Hapi.js REST APIs, and role-based department permissions.
- **ERP integration & automation:** Integrated Intuitive ERP and Juki Fortress through bidirectional XML-to-JSON transforms and scheduled cron sync for automated reconciliation. Added Jaro-Winkler fuzzy search and Nodemailer alerts for shortages and work-order updates.

---

## 🛠️ Featured Projects

#### 🩺 **FlahyRecovery — Oncology Diagnostics Platform**
`AdonisJS v6` · `TypeScript` · `PostgreSQL` · `Objection.js` · `FHIR` · `DICOM` · `Azure Blob Storage` · `Twilio` · `Firebase`  
*Nov 2024 – Feb 2025*
- Engineered a dual-API healthcare backend (main API + DICOM imaging API) for oncology labs, covering lab management, patient records, sample tracking, and diagnostic reports, with multi-role, policy-based authorization (Bouncer). Supports 200+ patient records.
- Implemented FHIR-compliant patient/report synchronization, a DICOM imaging service (`dcmjs`/`dicom-parser`) with Azure Blob Storage and PDF-to-image thumbnailing, Twilio OTP verification, Firebase push alerts, and QR-based sample tracking.

#### 👥 **IChooseIAM — Social Community & Event Platform**
`NestJS` · `TypeScript` · `Prisma` · `MySQL` · `Socket.io` · `Firebase (FCM)` · `Handlebars`  
*Mar 2025 – Apr 2025*
- Built an event-scoped RBAC and delegation system (event admins, co-creators) with isolated access boundaries and real-time chat moderation.
- Designed an "Incognito Mode" privacy architecture using gender-aware pseudo-identities to anonymize presence on public feeds, leaderboards, and discovery while preserving mutual-friend visibility.
- Built a referral and invite-tracking engine (custom member IDs, self-referral prevention, dynamic invites, per-event conversion analytics) with real-time notifications via Socket.io and FCM, Handlebars transactional emails, and Android/iOS deep-linking.

#### 🏋️ **Gym Pilates — Fitness Class Booking Platform**
`NestJS` · `TypeScript` · `Prisma` · `PostgreSQL` · `Socket.io` · `Firebase` · `Google OAuth 2.0` · `i18next`  
*Apr 2025 – Oct 2025*
- Built a class-booking platform (Admin/Member roles, scheduling, subscriptions, cancellation workflows) with real-time availability over a Socket.io gateway and database-level concurrency control to prevent double-bookings.
- Integrated Google OAuth 2.0 login, FCM push notifications, and bilingual (EN/ES) support via i18next. Built admin APIs for user management, class CRUD with cancellation-reason tracking, and subscription-plan lifecycle management.

#### 💳 **WalletApp — Multi-Wallet Expense Tracking API**
`Node.js` · `Express.js` · `MySQL` · `Sequelize ORM` · `JWT` · `Bcrypt` · `Multer` · `Jimp` · `Nodemailer`  
*Mar 2022 – May 2022*
- Built a multi-wallet REST API for cash and debit accounts across 11+ expense categories, with multi-currency handling, real-time monthly budget aggregations, and soft-delete audit trails.
- Implemented JWT auth, Bcrypt hashing, express-validator sanitization, OTP-based password resets, an admin panel with login audit tracking (device fingerprinting), and a secure profile-image pipeline (Multer + Jimp).

---

## 💻 Tech Stack

### Languages
[![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Backend & Frameworks
[![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)](https://nestjs.com/)
[![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Hapi.js](https://img.shields.io/badge/Hapi.js-black?style=for-the-badge&logo=hapi&logoColor=orange)](https://hapi.dev/)
[![AdonisJS](https://img.shields.io/badge/AdonisJS-5A45FF?style=for-the-badge&logo=adonisjs&logoColor=white)](https://adonisjs.com/)

### Frontend
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev/)
[![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

### Databases & ORMs
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/)
[![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)](https://www.prisma.io/)
[![TypeORM](https://img.shields.io/badge/TypeORM-FE0902?style=for-the-badge)](https://typeorm.io/)

### Generative AI & LLMs
[![OpenAI GPT-4o](https://img.shields.io/badge/OpenAI%20GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)](https://platform.openai.com/)
[![CrewAI](https://img.shields.io/badge/CrewAI%20(Agentic)-FF4B4B?style=for-the-badge)](https://crewai.com/)
[![Pinecone](https://img.shields.io/badge/Pinecone%20(Vector%20RAG)-000000?style=for-the-badge)](https://www.pinecone.io/)

### Queues & Real-Time
[![BullMQ](https://img.shields.io/badge/BullMQ-red?style=for-the-badge)](https://docs.bullmq.io/)
[![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)](https://socket.io/)
[![Pusher](https://img.shields.io/badge/Pusher-300D4F?style=for-the-badge&logo=pusher&logoColor=white)](https://pusher.com/)
[![SSE / WebSockets](https://img.shields.io/badge/SSE%20%2F%20WebSockets-0E75B6?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)

### Cloud, Auth & DevOps
[![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![AWS S3](https://img.shields.io/badge/AWS%20S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/s3/)
[![Cloudflare R2](https://img.shields.io/badge/Cloudflare%20R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://www.cloudflare.com/developer-platform/r2/)
[![Azure Blob Storage](https://img.shields.io/badge/Azure%20Blob%20Storage-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![JWT & OAuth 2.0](https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-black?style=for-the-badge&logo=jsonwebtokens)](https://jwt.io/)
[![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge)](https://pm2.keymetrics.io/)

### Third-Party & Healthcare Integrations
[![Google APIs](https://img.shields.io/badge/Google%20APIs-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://console.cloud.google.com/)
[![LinkedIn API](https://img.shields.io/badge/LinkedIn%20API-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://developer.linkedin.com/)
[![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white)](https://www.twilio.com/en-us)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![FHIR](https://img.shields.io/badge/HL7%20FHIR-E31837?style=for-the-badge)](https://hl7.org/fhir/)
[![DICOM](https://img.shields.io/badge/DICOM%20Imaging-005B94?style=for-the-badge)](https://www.dicomstandard.org/)

---

## 🎓 Education

- **Master of Computer Applications (MCA)** — Lovely Professional University (LPU), Punjab | *2021 – 2023*
- **Bachelor of Computer Applications (BCA)** — Panjab University (PU), Chandigarh | *2017 – 2020*

---

## 💡 Dev Philosophy

> _"First, solve the problem. Then, write the code."_ — John Johnson

> _"Clean code is not written by following a set of rules. It's written by someone who cares."_ — Robert C. Martin

---

### 👀 Thanks for visiting — let's build something extraordinary together!

[![Portfolio](https://img.shields.io/badge/🚀%20Visit%20Portfolio-0077B5?style=for-the-badge&logo=vercel&logoColor=white)](https://its-sky-portfolio.vercel.app/)
[![Email](https://img.shields.io/badge/📧%20Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shyamsky1914@gmail.com)
[![LinkedIn](https://img.shields.io/badge/🤝%20Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shyam-kumar-yadav-5827431a6)

![](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:0e75b6&height=130&section=footer)