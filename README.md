# Hi, I'm Uzochukwu Benneth (Algomachine) 👋

Senior Fullstack & Backend Engineer with 8 years of experience across fintech, IoT/telematics, and AI agent architecture. Based in Abuja, Nigeria.

I build production systems end-to-end — from React/Next.js front-ends to backend architecture, database design, and increasingly, AI agent tooling built on the Model Context Protocol (MCP).

---

## 🔧 What I work on

- **AI Agent Infrastructure & MCP Tooling** — I author and maintain MCP packages used in production developer tools.
- **Fullstack Web Development** — Next.js, React, Node.js/NestJS, GraphQL, REST APIs.
- **Backend Systems** — transactional integrity (ACID-compliant financial systems), database design (Postgres/Drizzle, DynamoDB), and API architecture.
- **IoT & Telematics** — GPS/CAN-bus hardware integration, real-time protocol parsing, live location and sensor pipelines.
- **Fintech & Payments** — wallet systems, Stripe integrations, reconciliation logic.

---

## 🚚 Featured Project: FuelSense

**FuelSense** is a fleet fuel-monitoring and theft-detection SaaS built for Nigerian commercial fleets, where fuel theft commonly runs at an estimated 15–30% of total fuel spend. Founder and sole engineer — built end-to-end from live hardware ingestion to the driver- and manager-facing product.

- Live TCP server parsing raw **Teltonika Codec 8 Extended** GPS/telematics packets from a **Teltonika FMC150** tracker wired into a vehicle's CAN bus / OBD-II port
- Real-time trip detection, idle-cost tracking, geofencing, and consumption-anomaly detection derived entirely from GPS telemetry
- Driver-facing fuel-receipt capture with **OCR extraction** (merchant, litres, cost), reconciled against tracker-modelled fuel levels
- Anomaly-investigation dashboard: GPS-synced evidence timelines with ignition/speed/fuel correlation and confidence-scored flags, framed as "investigation assist, not a final accusation"
- Deployed on **AWS EC2** with a Caddy reverse proxy, **Postgres/Neon** for data, feature-flag–gated rollout, and CSV/Excel export for fleet accounting
- Live pilot running with a real fleet operator (TRT, Abuja)

**Tech stack:** `Node.js` · `TypeScript` · `Next.js` · `PostgreSQL (Neon)` · `AWS EC2` · `Caddy` · `Teltonika Codec 8 Extended` · `OCR.space` · `Upstash Redis`

 
### 🎥 Demo Video

[![Watch the demo](https://cdn.loom.com/sessions/thumbnails/9dcd7efe4f494ccc81e3a80b525b28f1-00001.jpg)](https://www.loom.com/share/9dcd7efe4f494ccc81e3a80b525b28f1)

## 📦 Featured Case Study: SearchAtlas MCP Server

**[SearchAtlas MCP Server](https://github.com/Search-Atlas-Group/searchatlas-mcp-server)** ([npm](https://www.npmjs.com/package/searchatlas-mcp-server)) — an MCP bridge connecting AI clients (Claude Code, Cursor, Claude Desktop, VS Code, Windsurf, Zed) to the hosted SearchAtlas v2 platform, exposing 500+ tools across SEO, PPC, content generation, local SEO, link building, digital PR, and LLM visibility.

- Built as a stdio-to-Streamable-HTTP bridge so clients without native remote-MCP support can still connect
- Ships a CLI (`searchatlas login`, `searchatlas check`) that auto-detects paths and generates ready-to-paste config for every major MCP client
- Tools are discovered dynamically from the live server, so the client always sees the current catalogue without needing a package update
- MIT licensed, listed on the official MCP Registry

*(Add: your specific role/contribution if this is a team repo — e.g. "Designed and built the CLI auth flow and multi-client config generation.")*

## 🚀 Selected Projects

- **[algo-stores](https://github.com/amaben2020/algo-stores)** — E-commerce platform built with Next.js, Tailwind, Stripe, Firebase Auth/Firestore, Airtable-backed inventory management, and analytics/segment tracking.
- **[Mechalink](https://github.com/amaben2020/Mechalink)** — Platform connecting mechanics with cars in distress (roadside assistance marketplace).
- **[mechalink-backend](https://github.com/amaben2020/mechalink-backend)** — Backend service powering Mechalink: <!-- add one line, e.g. "REST/GraphQL API handling job matching and dispatch" -->
- **[diaspora-backend](https://github.com/amaben2020/diaspora-backend)** — <!-- add one line describing what this does -->
- **[advanced-cart-system-zustand](https://github.com/amaben2020/advanced-cart-system-zustand)** — Cart system flow built with Zustand for state management.
- **[sstv3-stripe-dynamo](https://github.com/amaben2020/sstv3-stripe-dynamo)** — <!-- add one line, e.g. "Stripe payments integration backed by DynamoDB" -->

## 🛠️ Tech Stack

`TypeScript` · `Next.js` · `React` · `Node.js` · `NestJS` · `GraphQL` · `REST` · `PostgreSQL` · `DynamoDB` · `Stripe` · `Firebase` · `MCP` · `AWS EC2` · `IoT/Telematics`

## 📫 Get in touch

<!-- Add: LinkedIn link, email, or portfolio site -->

---

⭐ *Currently open to fullstack/backend roles and contract work involving Next.js, backend architecture, or AI/MCP tooling.*
