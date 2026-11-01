<!---
aebibtech/aebibtech is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
# Hi there, I'm Paul Abib Camano 👋
### Founder & Systems Architect at StewardAxis LLC & Aebibtech

I design and build resilient, high-throughput digital systems and lightweight SaaS applications. My engineering philosophy is rooted in first-principles execution: maximizing compute efficiency, zeroing out memory bloat, and treating software as an appreciating asset rather than a cost center.

I operate both as an independent SaaS founder and a technical consultant for businesses that value high-leverage systems over architectural theater.

---

### ⚡ Proven Production Benchmarks & Open Source

- **[FastIngest (.NET)](https://github.com/aebibtech/fastingest):** Modular, high-throughput data ingestion pipeline utilizing PostgreSQL wire binary `COPY` protocol (`COPY FROM STDIN (FORMAT BINARY)`).
  - **15,710 items/sec** database ingestion throughput on PostgreSQL 17 (a **5.4x speedup** over traditional ORM batch loops).
  - Scaled 1,000-record import latency from **343.6 ms down to 63.7 ms** with **0 KB** GC thread allocations.
  - Organic adoption of **1,600+ NuGet downloads** across 9 packages in its first 48 hours.
- **[keysetengine-drizzle (NPM)](https://www.npmjs.com/package/keysetengine-drizzle):** Database-agnostic, zero-allocation keyset (cursor) pagination and multi-column search engine for **Drizzle ORM** on Node.js and Bun.
  - True O(1) indexed boundary pagination with bidirectional navigation.
  - Enterprise token defense: Authenticated **AES-256-GCM** encryption and **HKDF purpose isolation** to prevent cursor tampering and schema scraping.

---

### 🚀 Active Ventures & Products

- **[StewardAxis LLC](https://stewardaxis.com):** Independent US software venture studio engineering lightweight, multi-tenant B2B SaaS platforms.
- **[Team Chords](https://teamchords.com):** Live performance and worship band management platform featuring real-time setlist synchronization, ChordPro parsing, and cross-platform mobile apps.
  - *Stack:* ASP.NET Core 9, PostgreSQL 17, FastIngest, SignalR, Redis 7, React Native / Expo.
- **[Tindahan Natin](https://tindahannatin.aebibtech.com):** Grassroots inventory tracking and ledger mobile app actively used by neighborhood micro-retailers (*sari-sari* stores) and novelty shops across the Philippines.
  - *Stack:* Android, Offline-First SQLite/PostgreSQL, ASP.NET Core 9, Lightweight sync architecture.

---

### 🧰 Production Engineering Toolkit


```

Languages & Runtimes   : C# (.NET 9), TypeScript, Node.js (18+), Bun
Backend & APIs         : ASP.NET Core Minimal APIs, Elysia (Eden Treaty), Drizzle ORM, EF Core
Data, Queues & Cache   : PostgreSQL 17, Npgsql Binary COPY, Redis 7, SQLite
Frontend & Mobile      : React Native (Expo), Astro, Tailwind CSS, PWA
Real-Time & Storage    : SignalR, WebSockets, Cloudflare R2
Infrastructure & Cloud : Google Cloud Platform (Cloud Run), Cloudflare (Pages/Workers), Pulumi, Docker

```

---

### 🛠️ Strategic Advisory & Performance Sprints

I partner asynchronously with founders, CTOs, and early-stage ventures to stabilize systems, unblock scaling walls, and cut cloud costs:

- **Database Performance & Ingestion Audits:** Diagnosing ORM query bloat, lock contention, and replacing slow SQL `OFFSET` pagination with cryptographically protected keyset boundaries.
- **Micro-SaaS & Modular Architecture:** Designing clean, multi-tenant monoliths in Elysia/Bun or .NET without over-engineered mediator bloat.
- **API Throughput & Latency Optimization:** Profiling memory allocations, zero-copy streams, and sub-millisecond network pipelines.

---

### 📬 Connect

- 🌐 **Portfolio & Studio:** [aebibtech.com](https://aebibtech.com)
- 💼 **Engagements:** Fractional Architecture Advisory & Fixed-Scope Performance Audits.
- 💬 **Get in Touch:** Reach out via GitHub Discussions, my website, or LinkedIn.
