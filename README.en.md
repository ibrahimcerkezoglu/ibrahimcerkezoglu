# Ibrahim Cerkezoglu

<sup>🇬🇧 English · 🇹🇷 [Türkçe](README.md)</sup>

Full Stack Developer — focused on .NET Core & SQL Server, building AI-integrated web and mobile systems.
B.Sc. in Computer Engineering · Open to remote / hybrid work · Turkish (Native) · English (B1)

<p>
  <a href="https://ibrahimcerkezoglu.dev">
    <img src="https://img.shields.io/badge/🌐_My_Portfolio_Site-Case_Studies_%7C_CV_%7C_Contact-a855f7?style=for-the-badge&logoColor=white" alt="ibrahimcerkezoglu.dev" />
  </a>
</p>

I turn complex business processes (marketplaces, accounting/payment systems, admin panels) into scalable architectures and integrate AI into real products. Most of the projects below are systems I've actively developed for 3+ years with real users — **for detailed case studies (architecture decisions, stats, engineering highlights), check out [ibrahimcerkezoglu.dev](https://ibrahimcerkezoglu.dev).**

---

## Projects

**Social-Commerce Marketplace**
A multi-vendor e-commerce marketplace: live-stream selling, real-time auctions, an influencer program, coupons and a wallet system. Built on 82 controllers, 96 database migrations and 3 SignalR hubs (chat, auction, notifications). Includes an OpenAI-embedding-based product recommendation engine (vector search), ONNX Runtime background removal and 3D/AR product previews.
`ASP.NET Core` `Angular` `SignalR` `OpenAI Embeddings` `ONNX Runtime`

**Accounting & Payment Automation for Social/Game Coin Resellers**
A ~70,000-line accounting and payment reconciliation system for resellers of in-app virtual coins used on TikTok-style platforms. Background workers integrating with 8 different external services (bank receipt scanners, payment providers, e-invoicing), a SignalR hub for real-time receipt notifications, and 67+ incremental migrations proving long-running active development.
`ASP.NET Core` `EF Core` `SignalR` `Background Workers`

**AI-Powered Freelancer Marketplace**
A freelancer marketplace built for a TÜBİTAK 2209-A funded venture. Listing, bidding, order and payment flows; role-based admin panel; real-time messaging via SignalR. Includes an AI listing coach and chat bot powered by a local LLM (Ollama, Qwen Coder). Security and resilience decisions like global CSRF enforcement and transient-fault retry are explicitly documented in code.
`ASP.NET Core` `SignalR` `Local AI / Ollama` `Google OAuth`

**Aria — Local Offline Personal AI Assistant**
A fully offline, privacy-first personal assistant. A router that dispatches between 5 different local LLM models by task type, ChromaDB-based vector memory (RAG), voice interaction (Whisper + Piper TTS), and screenshot analysis. Since it can control the computer by voice, I designed a two-tier security filter that blocks dangerous commands (`rm -rf`, `powershell -enc`, etc.).
`Python` `FastAPI` `Ollama` `ChromaDB` `Whisper`

**CellScope — Cell Signal Geolocation Engine**
A telecom signal analysis engine built as an embedded module for a licensed, closed-source desktop application. Produces a 0-100 location confidence score using RSRP-weighted signal analysis, timing-advance distance rings and sector-angle validation. Backed by real unit and e2e tests.
`Python` `FastAPI` `Polars` `DuckDB` `React` `Leaflet`

**Automated Listing Tracker & Analysis Bot**
A monitoring system that scans second-hand listing sites with stealth browser automation, parses each listing with an LLM (mileage, year, damage record, replaced parts) and filters by user-defined criteria. Fully reconfigurable via Telegram bot commands with no redeploy needed — add a new radar, update criteria, and more.
`Python` `Playwright` `LLM Parsing` `Telegram Bot`

**AI-Powered Lead & Proposal Bot**
An automation bot that tracks job opportunities on freelance platforms, drafts proposals with GPT, and manages client conversations. It includes a decision mechanism that detects when it's "stuck" (price negotiation, technical question, cancellation) and hands the conversation back to me automatically; successful conversations are saved to memory as examples for future proposals.
`Python` `Playwright` `OpenAI API` `Telegram Bot`

**Gym Mobile — Fitness Club Management App**
A React Native app with workout tracking, diet plans, measurement history, payments, and QR-code turnstile check-in/out — production-ready on both iOS and Android with push notifications (OneSignal).
`React Native` `Redux` `OneSignal`

**CRM & WooCommerce Sync Platform**
A back-office CRM built for an e-commerce brand: order, stock, RMA, POS and invoicing management. Bidirectional order/stock sync with WooCommerce, shipping-provider webhook integration and an e-invoicing API. Includes a scheduled job that auto-generates blog content with a Groq LLM twice a day and publishes it to WordPress. 71 migrations deep and still actively developed.
`ASP.NET Core` `EF Core` `Hangfire` `WooCommerce API` `Groq LLM`

**B2B License & Supply Management for Curtain Retailers**
A B2B system managing multiple stores, warehouses and suppliers under one roof. Per-store license tracking with a scheduled service sending automatic expiry-warning emails 30/7 days out; a supplier price-change approval workflow; QR/barcode-based price and stock lookup.
`ASP.NET Core` `EF Core` `Hangfire` `QRCoder`

**Restaurant Ordering & Reservation System**
A restaurant platform built with Angular (SSR) + ASP.NET Core, with menu management, online ordering (PayPal + cash-on-delivery), cart/checkout and table reservations.
`Angular (SSR)` `ASP.NET Core` `PayPal`

**SMS / WhatsApp Bulk Messaging Gateway**
A gateway with an admin panel for corporate bulk SMS and WhatsApp messaging. The ASP.NET Core management panel works in coordination with a separate Node.js bridge service running over the WhatsApp Web protocol.
`ASP.NET Core` `Node.js` `WhatsApp Bridge`

This is just the highlights — **[ibrahimcerkezoglu.dev/#projects](https://ibrahimcerkezoglu.dev/#projects)** has all 28 projects, filterable by category, each with its own case study page.

---

## Experience & Other Work

- **Koresan.com / smart.koresan.com** — I manage the multi-channel e-commerce infrastructure: built and maintain API integrations syncing products, stock and orders across Trendyol, Hepsiburada and WooCommerce/WordPress.
- **Large-scale manufacturing/supply facility (IT Internship)** — Built a rate-limited bulk SMS/WhatsApp system delivering messages to 1000+ employees within 20 minutes, plus a certificate-tracking system for the HSE department; supported domain-migration operations for 650+ devices.
- **Freelance** — Custom CRM/admin panel systems for curtain retail, restaurant and electrical-service businesses; sped up a brand's WooCommerce infrastructure with Cloudflare + cache optimization.
- **Corporate consulting firm (PMO Internship)** — Research and presentation on enterprise GenAI/Copilot use cases.

I've also completed other projects such as a 3D model marketplace and a certified training/compliance platform.

For detailed work history and references, feel free to check my [LinkedIn profile](https://www.linkedin.com/in/ibrahimcerkezoglu/).

---

## Tech Stack

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress_/_WooCommerce-21759B?style=flat&logo=wordpress&logoColor=white)
![Ollama](https://img.shields.io/badge/Local_AI_/_Ollama-000000?style=flat&logo=ollama&logoColor=white)

---

## Contact

[![Website](https://img.shields.io/badge/Website-ibrahimcerkezoglu.dev-a855f7?style=flat&logo=googlechrome&logoColor=white)](https://ibrahimcerkezoglu.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahimcerkezoglu/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:cerkezogluibrahim@gmail.com)
[![CV](https://img.shields.io/badge/Download_CV-06b6d4?style=flat&logo=readdotcv&logoColor=white)](https://ibrahimcerkezoglu.dev/cv/ibrahim-cerkezoglu-cv-en.pdf)
