<h1 align="center">Hey there! I'm Abu Qamar 👋</h1>
<h3 align="center">Full-Stack Software Engineer · React · Node.js · Next.js · AWS</h3>

<p align="center">
  <a href="https://abuqamar-portfolio.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/abu-qamar-shaikh-a6a72a274/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shaikhqamar7379@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## 🧑‍💻 About Me

I'm a **Full-Stack Software Engineer** at **SkilloVilla**, where I build and ship product features end-to-end — from pixel-perfect UIs to backend systems to production infrastructure. My work directly serves **10,000+ learners** and **2 lakh+ active users** daily.

I don't box myself into "frontend" or "backend." If there's a feature to build, a system to design, an automation to create, or infrastructure to fix — I'll own it and ship it. That's how I ended up building exam platforms, real-time terminal widgets, AI screening pipelines, OTP abuse prevention systems, a consolidated admin portal, and leading a full cloud migration — all within the same role.

Previously, I worked as a **Full Stack Developer Intern** at **LeadTym**, building microservices for payment gateways, wallet systems, and admin workflows.

---

## 🔥 What I've Built

### 🏢 At SkilloVilla (SDE-1 · Nov 2024 – Present)

---

#### 🎯 Online Test-Taking Platform
Built a scalable exam platform from the ground up using **Next.js, React Query, and styled-components**. The platform supports live, time-bound, multi-section exams with **8+ question types** — MCQ, SCQ, Fill-in-the-Blanks, Coding, SQL, Terminal-based, and Match-the-Following. It handles concurrent exam sessions with real-time state management and currently serves **10,000+ learners**.

---

#### 📋 Evaluation Leaderboard
Built a leaderboard with **dual interfaces** — a **student-facing view** (ranks, performance stats) and an **admin-facing view** (granular submission tracking, question-level insights) — solving critical visibility gaps for mentors and reducing evaluation review time by **50%**. Optimized state management using **Zustand with MAP-based O(1) lookups**, reducing redundant API calls by **40%** and improving dashboard responsiveness despite backend polling constraints.

---

#### 🔄 Fault-Tolerant Offline Submission System
Engineered a **client-side queuing system** so users can continue tests seamlessly offline. The system handles **automatic sync on reconnection**, debounced API calls, and a periodic retry mechanism — achieving **zero submission loss** and enhancing overall platform reliability even on unstable networks.

---

#### 🧩 Admin Portal Consolidation
Transformed a fragmented ecosystem of **30+ scattered dashboards** into a **single, secure admin portal** using **Hasura, custom auth middleware, and Cloudscape design system**. This dramatically reduced onboarding time for new team members, minimized operational errors, and enhanced cross-team collaboration by giving everyone a unified view.

---

#### 📄 Template-Driven Landing Page System
Built a scalable, **template-driven landing page system** with **slug-based dynamic routing**, empowering marketing and content teams to launch new course pages instantly **without any developer intervention**. This improved go-to-market speed by **80%** — teams went from waiting days for dev cycles to publishing pages in minutes.

---

#### 💼 Job Board
Built a fully optimized Job Board platform inside SkilloVilla's LMS using **Strapi CMS and React**, empowering **2 lakh+ active users** to discover and apply for jobs with seamless integration into the learning ecosystem. The board features advanced filtering, bookmarking, and search capabilities.

---

#### 📍 Location Tracking & Targeted Ads
Implemented user location tracking by integrating **Google Maps APIs**, managing **100k monthly requests**. This enabled **location-based targeted advertisements**, leading to a **30% increase in lead generation** by serving relevant content to users based on their geography.

---

#### 🤝 Referral Feature
Developed a referral system with **real-time activity tracking** using **Appsmith dashboards** powered by **Hasura GraphQL APIs** with **PostgreSQL and MongoDB** as backing stores. The feature increased user engagement and conversions through an automated referral dashboard giving the ops team full visibility into referral funnels and payouts.

---

#### 💻 Real-Time Terminal Practice Widget
Built a live terminal practice environment using **WebSockets and AWS ECS**, where each user gets an **isolated containerized environment** to practice coding in real-time. Reduced container startup latency from **~30s to 2–3s** by implementing a **warm-pool strategy** — pre-provisioning containers so they're ready before users need them.

---

#### ⚙️ Warm Pool Auto-Scaling via Consul
Implemented **runtime-configurable warm pool scaling** using **Consul** as the configuration store. This enables **traffic-aware container pre-provisioning** — automatically scaling up warm containers on weekends (high traffic) and scaling down on weekdays — optimizing both performance and cost without requiring code deployments.

---

#### 🔐 OTP Orchestration System
Designed a secure OTP delivery system where the **LMS acts as a gateway** to **VPC-isolated backend services**. The architecture supports OTP flows across multiple use cases — user authentication, evaluation access control, and notifications — without exposing any internal APIs publicly.

---

#### 🛡️ Large-Scale OTP Abuse Prevention
Detected and mitigated a massive OTP abuse attack where traffic had spiked to **~500k requests/day**. Integrated **invisible CAPTCHA** using **Cloudflare Turnstile** (with **Google reCAPTCHA** as fallback) and implemented **runtime provider switching via Consul** — allowing the team to swap OTP providers on the fly without deployments. This brought traffic down to **2–3k/day** and prevented vendor blacklisting.

---

#### 🤖 AI-Powered Resume Screening Pipeline
Built an end-to-end automated screening pipeline using **N8N workflows, Gemini Flash 2.0, and Groq (GPT-120B)**. The system processed **7,000+ job applications in under 1 hour**, shortlisted **310 qualified candidates**, and cost just **$0.001 per resume** (~$10 for 10k resumes vs $100+ with other solutions). This replaced what used to take the hiring team **2+ months of manual screening**.

---

#### 🏗️ CI-Driven Evaluation Pipelines
Built automated evaluation pipelines using **Jenkins and GitLab CI** that **dynamically provision AWS ECS tasks** to execute and grade user-submitted assignments in **fully isolated environments**. Each submission runs in its own container, ensuring security and consistency across evaluations.

---

#### 📊 Centralized Error Tracking & Observability
Implemented **global error ID tracking** with centralized logging to **Datadog via FluentBit**, enabling **end-to-end request tracing** across services. Users simply raise tickets with the error ID, and engineers can trace the full request lifecycle instantly — reducing average debugging time from **hours to minutes**.

---

#### 🚨 Real-Time Monitoring & Incident Escalation
Set up production monitoring, health checks, and **automated incident escalation** using **Squadcast and Slack**. Configured escalation policies with automatic routing — **primary → secondary → team lead** — ensuring no incident goes unnoticed regardless of time or day.

---

#### 🧪 End-to-End Quality Ownership
Owned **end-to-end quality assurance** in a completely **QA-less team** — handling test planning, manual and automated testing, production debugging, incident response, and post-mortems. This ensures features ship reliably despite having no dedicated QA resources.

---

#### ☁️ GCP to AWS Infrastructure Migration
Led the **complete infrastructure migration** from Google Cloud Platform to AWS for both **staging and production** environments. The migration enabled **horizontal scaling**, proactive capacity planning, and saved the company **INR 8L+ per month** in infrastructure costs.

---

#### 🔒 Cloudflare ZTNA & CDN Failover
Secured the entire internal infrastructure by implementing **Cloudflare Zero Trust Network Access** following a security breach, **eliminating the need for bastion hosts** and restricting access to private resources. Additionally, designed a **bypass and fast failover strategy** using **Route53 DNS switching and certificate rotation**, enabling recovery from CDN outages in **under 2 minutes**.

---

### 🏢 At LeadTym (Full Stack Intern · Jul – Oct 2024)

---

#### 💳 Payment & Wallet Microservices
Worked in a **microservices-based architecture**, developing both backend and frontend services for the **admin, wallet, ticketing, and payment gateway** modules. Designed **secure inter-service communication** for payment and wallet workflows, ensuring **data consistency and fault isolation** across service boundaries.

---

#### ⚡ High-Throughput Transaction Optimization
Optimized transaction flows to achieve **low-latency performance** and reliable **wallet balance reconciliation** at scale. This involved tuning database queries, implementing efficient transaction handling, and ensuring financial accuracy across concurrent operations.

---

#### 📝 Centralized Error Handling & Logging
Implemented **robust input validation, centralized error handling, and structured logging** across all services. Collaborated on improving **observability and production monitoring** for live services, making it easier to trace issues and maintain system reliability.

---

## 🚀 Personal Projects

### 📚 CodeCrafters — Learning Management System
**Tech:** Next.js · TypeScript · Prisma · MySQL (Planetscale) · Clerk · NextAuth · Stripe · RazorPay · Mux · Shadcn UI · UploadThing

A full-stack LMS platform where **students** can browse, purchase, and track courses, while **teachers** can create and manage content.

- **Student experience** — Course browsing, purchasing, progress tracking, and chapter completion workflows that drive engagement and learning outcomes
- **Teacher tools** — Course creation with drag-and-drop chapter reordering, rich-text editor for descriptions, and file/video attachments via UploadThing
- **Payments** — Integrated **Stripe and RazorPay** for secure course purchases with webhook-based order confirmation
- **Video streaming** — Integrated **Mux** for video uploads, processing, and **HLS playback** ensuring smooth streaming across devices
- **Auth & data layer** — Secure authentication using **Clerk and NextAuth**, with **Prisma ORM** and **MySQL (Planetscale)** for a scalable, reliable backend

---

### 💬 ChatterHub — Discord-Inspired Real-Time Collaboration Platform
**Tech:** Next.js · TypeScript · Socket.io · Prisma · MySQL (Planetscale) · Clerk · TanStack Query · UploadThing

A real-time messaging platform inspired by Discord, supporting **1:1 and group communication** across text, audio, and video channels.

- **Real-time messaging** — Message sending, editing, deletion, and file attachments powered by **Socket.io** with **TanStack Query** for optimistic updates and infinite scroll
- **Voice & video calls** — Built voice and video call functionality for direct and group communication
- **Server management** — Full server and member management including roles, permissions, kicking members, and shareable invite links
- **Responsive UI** — Mobile-first design with **light/dark mode** support and file/video uploads via UploadThing
- **Reliability** — Implemented **WebSocket fallback with polling** and alert notifications to ensure communication works reliably across all network conditions

---

## 🛠️ Tech Stack

**Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000?style=flat-square&logo=shadcnui&logoColor=white)
![Material UI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=flat-square&logo=styledcomponents&logoColor=white)
![Cloudscape](https://img.shields.io/badge/Cloudscape-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Appsmith](https://img.shields.io/badge/Appsmith-2A2F3D?style=flat-square&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000?style=flat-square&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Strapi](https://img.shields.io/badge/Strapi-4945FF?style=flat-square&logo=strapi&logoColor=white)
![Hasura](https://img.shields.io/badge/Hasura-1EB4D4?style=flat-square&logo=hasura&logoColor=white)
![NextAuth](https://img.shields.io/badge/NextAuth-000?style=flat-square&logo=nextdotjs&logoColor=white)

**Databases & ORMs**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white)

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Consul](https://img.shields.io/badge/Consul-F24C53?style=flat-square&logo=consul&logoColor=white)

**AI & Automation**
![N8N](https://img.shields.io/badge/N8N-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-000?style=flat-square&logoColor=white)
![ChatGPT](https://img.shields.io/badge/ChatGPT-74AA9C?style=flat-square&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Perplexity](https://img.shields.io/badge/Perplexity-1FB8CD?style=flat-square&logo=perplexity&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000?style=flat-square&logo=ollama&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=flat-square&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-000?style=flat-square&logo=githubcopilot&logoColor=white)

**Testing**
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=flat-square&logo=cypress&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=black)
![Imgix](https://img.shields.io/badge/Imgix-FF2045?style=flat-square&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Squadcast](https://img.shields.io/badge/Squadcast-F24C53?style=flat-square&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AbuQamar7379&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbuQamar7379&theme=github_dark&hide_border=true&layout=compact&langs_count=8" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AbuQamar7379&theme=github-dark-blue&hide_border=true" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AbuQamar7379&style=flat-square&color=blue" alt="Profile views" />
</p>
