<div align="center">

# Saidu Bundu-Kamara

### Payments & commerce infrastructure for West Africa

Mobile money, escrow, offline-first, and AI — built and shipped from Freetown.

📍 Freetown, Sierra Leone (GMT) | 💼 Software Engineer @ Christex Foundation

[![Email](https://img.shields.io/badge/Email-bundukamarasaidu%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:bundukamarasaidu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-saidubundukamara-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/saidubundukamara)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B232%2078%20077%20127-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/23278077127)

bundukamarasaidu@gmail.com · +232 78 077 127

</div>

---

## 👨‍💻 About Me

I build **payment and commerce infrastructure for West African markets**. I've shipped fintech wallets, crowdfunding, a ride-hailing platform, a live commerce platform with **mobile-money escrow**, and a law-enforcement digital public good built for officers working offline. I'm strongest in **backend architecture, payment integrations, and real-time systems**, and I'm comfortable dropping into Flutter, Next.js, or SvelteKit when a build needs it. Today I run **24 microservices on Kafka in production** and use **Claude** to turn a shop owner's plain description into a working online store. I also mentor new developers and run cohorts that bring beginners into tech.

## 💼 Experience

**Software Engineer** — Christex Foundation *(Mar 2024 – Present)*<br>
Build internal tools and government-facing products across fintech and public-sector systems. Lead Learn2Earn (a UNICEF & MoCTI bounty platform), helped build Pipeline (an open source platform for Digital Public Goods), built Byn2 and its Solana layer along with Mocha's WhatsApp stablecoin on/off-ramp, and run developer cohorts that onboard beginners into tech.

**Web Developer** — EasyBet *(Feb 2023 – Feb 2024)*<br>
Cut API response times on high-traffic betting platforms, led third-party integrations and infrastructure audits, and set coding standards for the team.

**Web Developer** — MediaOne Centre (Star TV) *(Aug 2019 – Jan 2023)*<br>
Built and maintained the company website and the backend behind live event streaming, keeping real-time streams stable during broadcasts.

## 🚀 What I'm Currently Working On

- 🛒 Building **EzStaw**, a commerce platform that turns a plain description into a live online store in under 60 seconds, with mobile-money escrow
- 🚗 Shipping **Marto**, a ride-hailing and car rental platform for Sierra Leone
- 🏗️ Leading **Learn2Earn**, a UNICEF & MoCTI bounty platform connecting Sierra Leonean freelancers with paid work
- 🔀 Running 24 microservices on Kafka in production
- 🤖 Wiring LLMs into developer tools and financial products
- 👨‍🏫 Running developer cohorts and mentoring beginners into tech

## 💼 Featured Projects

### 🛒 [EzStaw](https://ezstaw.com) - Commerce Platform & Mobile-Money Escrow
"Shopify for Sierra Leone" — AI builds a live online store from a plain description in under 60 seconds
- Architected a **24-service NestJS platform** on **Kafka**, with five **Next.js 16** apps: merchant dashboard, storefronts, marketplace, platform admin, and marketing
- Built **mobile-money escrow** on Orange Money and Afrimoney through Monime — a **double-entry ledger** holds funds until the buyer confirms delivery, with payouts, refunds, and reconciliation
- Wired **Claude** into store generation, product copy, and catalog import, and shipped **WhatsApp commerce** on the Meta Business Platform so merchants sell in the channel they already use
- **Technologies:** NestJS, Next.js 16, React 19, TypeScript, Kafka, PostgreSQL, Prisma, Redis/BullMQ, Meilisearch, Tailwind v4, Docker, AWS (EC2/RDS), Cloudflare (R2/Workers), Caddy, OpenTelemetry/Grafana, Claude API, Monime, WhatsApp Business

### 🚗 [Marto](https://getmarto.com) - Ride-Hailing & Car Rental
Ride-hailing and car rental platform for Sierra Leone
- Built the **NestJS** backend, **Next.js** admin panel, and a **Flutter** app for riders and drivers, handling both rides and multi-day rentals
- Implemented real-time driver matching with **Redis geospatial queries**, live tracking over **Socket.IO**, surge pricing, and Monime wallet/cash payments
- Provisioned **AWS with Terraform** (EC2, VPC, Secrets Manager) and automated deploys with GitHub Actions and PM2
- **Technologies:** NestJS, Flutter, Next.js, PostgreSQL, Prisma, Redis, Socket.IO, BullMQ, AWS, Terraform, Monime, Google Maps

### 🏥 [IB4ME](https://ib4me.org) - Crowdfunding Platform
General-purpose crowdfunding for Sierra Leone — education, community, health, and emergencies
- Built a full-stack platform where individuals and organizations create campaigns and publish instantly, with verification badges and admin moderation
- Integrated **Monime** for mobile money and card payments with webhook verification and a double-entry ledger, plus WhatsApp, SMS, and email notifications
- **Technologies:** Next.js 15, React 19, TypeScript, MongoDB, Monime, Cloudinary, Sentry, Vercel

### 🎓 [Learn2Earn](https://learn2earn.christex.foundation) - UNICEF & MoCTI Bounty Platform
A marketplace connecting Sierra Leonean freelancers with paid work
- Lead development of a platform where companies post bounties and freelancers deliver paid work, built to prepare them for global platforms like Upwork
- Built a **multi-tenant setup** (public platform plus subdomain admin panel) with email-verified auth, a skills taxonomy, and Monime payments
- **Technologies:** SvelteKit 2, Svelte 5, TypeScript, Prisma, PostgreSQL, Better Auth, Monime, Vercel

### ⚖️ OpenJustice - Law Enforcement DPG
Pan-African digital public good for law enforcement, built for Sierra Leone — private repo, happy to walk through the architecture
- Architected an **offline-first PWA** with IndexedDB and background sync for officers in low-connectivity areas
- Built **RBAC** (6 levels), **AES-256-GCM** encryption, and **SHA-256** audit chains for sensitive records
- Added **USSD** (Africa's Talking) and **WhatsApp** (Whapi) interfaces, GeoCrime analytics with crime heatmaps, and inter-agency sharing with API keys and webhooks
- **Technologies:** NestJS, Next.js 16, TypeScript, PostgreSQL, Prisma, Redis/BullMQ, AWS S3, Service Workers, IndexedDB

### 🌍 [Pipeline](https://launch.publicgood.dev) - Open Source DPG Platform
Supporting Digital Public Goods (DPGs) in Sierra Leone
- Helped build the platform in **Svelte** with Vercel serverless functions, adding AI-powered scoring to assess DPG compliance automatically
- Strengthened API security with middleware auth and rate limiting, and improved CI/CD
- **Technologies:** Svelte, Vercel, Node.js

### 💸 Byn2 & Mocha - Fintech & Stablecoin On/Off-Ramp
Free money transfers with a blockchain layer and a WhatsApp stablecoin on/off-ramp — private repo, happy to walk through the architecture
- Built **Byn2** to send and receive money for free across mobile, web, and a B2B dashboard, then added a **Solana Web3** settlement layer
- Used that layer to power **Mocha**, a WhatsApp chatbot where users on/off-ramp stablecoins in chat, with KYC checks and transaction logging
- **Technologies:** Express.js, Solana Web3.js, Node.js, WhatsApp Business API

## 🛠️ Tech Stack

### Languages & Runtime
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE422B?style=flat&logo=rust&logoColor=white)
![Solana & Anchor](https://img.shields.io/badge/Solana_%26_Anchor-9945FF?style=flat&logo=solana&logoColor=white)

### Backend, Frontend & Mobile
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white)

### Data, Messaging & Search
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Meilisearch](https://img.shields.io/badge/Meilisearch-FF5CAA?style=flat&logo=meilisearch&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

### Cloud, Infra & Observability
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat&logo=nginx&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=claude&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🎓 Education & Certifications

**BSc Information Technology** *(Mar 2021 – Dec 2024)*<br>
*Limkokwing University of Creative Technology*

**Certifications:**
- ✅ AI Fluency: Framework & Foundations - [Verify](https://verify.skilljar.com/c/bb6jvua79k5b)
- ✅ AI Fluency for Educators - [Verify](https://verify.skilljar.com/c/3vc6t857kxt8)
- 🔄 AWS Certified Cloud Practitioner (In Progress)

## 🏆 Awards & Recognition

- 🏅 **Tan Sri Limkokwing Award for Creativity and Innovation** - Limkokwing University of Creative Technology
- 🥇 **Winner**, Hackathon by Project 323 & Christex Foundation
- 🥉 **Top 3**, World Bank Hackathon - Sierra Leone

## 📊 GitHub Activity

<div align="center">

![GitHub contribution streak — 5,000+ total contributions since March 2024](https://streak-stats.demolab.com/?user=saidubundukamara&background=transparent&hide_border=true&ring=FB8C00&fire=FB8C00&currStreakNum=58A6FF&sideNums=58A6FF&currStreakLabel=FB8C00&sideLabels=7D8590&dates=7D8590)

</div>

---

<div align="center">

### 💡 Hiring, funding a DPG, or building payments in West Africa? Email me — I reply within a day.

[![Email](https://img.shields.io/badge/Email-bundukamarasaidu%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bundukamarasaidu@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-saidubundukamara-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/saidubundukamara)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B232%2078%20077%20127-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/23278077127)

*Based in Freetown (GMT) — full overlap with Europe, mornings with US East.*<br>
*Languages: English, Krio | Mentor to junior developers and bootcamp students | Speaker at tech meetups and engineering workshops*

</div>
