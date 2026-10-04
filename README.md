<div align="center">

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
    <img src="assets/banner-dark.svg" alt="M. Ilmi Alfaridzi Header Banner" width="100%">
  </picture>

  <br />

  <p align="center">
    <a href="https://linkedin.com/in/ilmialfa" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;
    <a href="mailto:alfaridziilmi@gmail.com">
      <img src="https://img.shields.io/badge/Email-0F172A?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    &nbsp;
    <a href="https://instagram.com/ilmialfaridzi" target="_blank">
      <img src="https://img.shields.io/badge/Instagram-0F172A?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" />
    </a>
    &nbsp;
    <a href="https://wa.me/6282248001571" target="_blank">
      <img src="https://img.shields.io/badge/WhatsApp-0F172A?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" />
    </a>
    &nbsp;
    <a href="https://omniconvert-mu.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Live_App-0284C7?style=flat-square&logo=vercel&logoColor=white" alt="Live App" />
    </a>
  </p>

</div>

---

### Overview

I am an Informatics Engineering student at **Universitas Muhammadiyah Riau (UMRI)** and a full-stack web developer based in Pekanbaru, Indonesia. 

My engineering focus centers on **local-first web architectures**, **client-side sandboxing**, and **resilient full-stack backbones**. I primarily architect applications using **Laravel 12**, **Next.js**, **TypeScript**, and **WebAssembly (WASM)**, prioritizing user data privacy, sub-second response times, and clean domain boundaries over boilerplate complexity.

Beyond software development, I frequently moderate technical discussions and university events, having served as the Master of Ceremony for the 28th UMRI Graduation, committee lead for the national NIFC 4.0 event, and coordinator for campus web development study circles.

---

### Flagship Engineering Work

#### ⚡ [OmniConvert](https://github.com/Ilmialfa/OmniConvert)
*Browser-First File Conversion Suite with Zero Server Footprint*

- **Problem**: Mainstream cloud file converters require users to upload confidential documents and media to remote servers, causing privacy exposure and high cloud compute expenses.
- **Architecture**: Eliminates remote upload infrastructure entirely by embedding **WebAssembly (FFmpeg.wasm & Tesseract OCR)** inside browser memory. Heavy transcoding runs concurrently in dedicated Web Workers to ensure a 60 FPS UI thread.
- **Capabilities**: Converts **56+ formats** across documents, audio, video, OCR text extraction, and batch queues with direct ZIP compilation.
- **Stack**: `Next.js 15` &bull; `TypeScript` &bull; `WebAssembly (WASM)` &bull; `Web Workers` &bull; `Tailwind CSS` &bull; `PWA`
- **Links**: [Live Application ↗](https://omniconvert-mu.vercel.app) &bull; [Source Code ↗](https://github.com/Ilmialfa/OmniConvert)

---

#### 🧠 [FinSight AI](https://github.com/Ilmialfa/finsight-ai)
*Financial Intelligence & Predictive Analytics Dashboard*

- **Problem**: Personal and small-business budgeting tools typically force repetitive manual classification and provide static, backward-looking summaries without predictive forecasting.
- **Architecture**: Leverages **OpenAI Structured Outputs** (strict JSON schemas) to parse unstructured transactions into financial taxonomies, coupled with client-side run-rate projections rendered via **Recharts**.
- **Capabilities**: Automated expense categorization, dynamic cashflow trajectory modeling, and conversational budget health assessment.
- **Stack**: `Next.js 16 (Turbopack)` &bull; `React 19` &bull; `TypeScript` &bull; `OpenAI API` &bull; `Recharts` &bull; `Tailwind CSS`
- **Links**: [Live Application ↗](https://finsight-ai-vert.vercel.app) &bull; [Source Code ↗](https://github.com/Ilmialfa/finsight-ai)

---

#### 🏛️ [Website Batik KKN](https://github.com/Ilmialfa/website-batik-kkn)
*Cultural Heritage Digitization & UMKM E-Commerce Platform*

- **Problem**: Traditional batik artisans in Riau faced limited market reach and had no structured digital repository to preserve and communicate the historical narratives of indigenous motifs.
- **Architecture**: Engineered for the Universitas Muhammadiyah Riau community empowerment initiative. Uses **Laravel 12** with **Inertia.js React** for single-page performance without API glue overhead, paired with a customized **Filament PHP** backoffice for non-technical artisans.
- **Capabilities**: Interactive motif encyclopedia, artisan catalog showcase, and streamlined direct-inquiry order flows.
- **Stack**: `Laravel 12` &bull; `PHP 8.3+` &bull; `Inertia.js React` &bull; `Filament PHP` &bull; `Tailwind CSS` &bull; `MySQL`
- **Links**: [Source Code ↗](https://github.com/Ilmialfa/website-batik-kkn)

---

#### 🏪 [Toko Putera Kembar](https://github.com/Ilmialfa/toko-putera-kembar)
*Point of Sale (POS) & Real-Time Retail Inventory Management*

- **Problem**: Retail operations often experience inventory drift, cashier checkout latency, and lack of role-segmented auditing.
- **Architecture**: Full-stack retail management built with **Laravel 12** and **Inertia.js React**, featuring multi-tier Role-Based Access Control (**Spatie RBAC**) separating store owners, cashiers, and warehouse supervisors.
- **Capabilities**: Real-time stock decrement, anomaly alerts for low reserves, thermal receipt formatting, and automated database snapshot routines.
- **Stack**: `Laravel 12` &bull; `PHP 8.3+` &bull; `Inertia.js React` &bull; `TypeScript` &bull; `Spatie Permissions` &bull; `MySQL`
- **Links**: [Source Code ↗](https://github.com/Ilmialfa/toko-putera-kembar)

---

### Technical Capabilities

| Domain | Core Technologies &amp; Standards |
| :--- | :--- |
| **Frontend &amp; UI** | Next.js (App Router), React 19, TypeScript, JavaScript (ESNext), Tailwind CSS, Framer Motion, Recharts |
| **Backend &amp; Services** | Laravel 11/12, PHP 8.3+, Inertia.js, Filament PHP, RESTful APIs, Spatie Permissions |
| **Compute &amp; Runtimes** | WebAssembly (FFmpeg / Tesseract WASM), Web Workers, Service Workers (PWA) |
| **Databases &amp; State** | MySQL, PostgreSQL, SQLite, IndexedDB, Client-Side Caching |
| **Tooling &amp; Workflow** | Git, GitHub Actions, Vite, Vitest, Postman, Composer, pnpm / npm, Vercel |

---

### Leadership &amp; Honors

- 🎓 **Undergraduate in Informatics Engineering** &mdash; Universitas Muhammadiyah Riau (UMRI)
- 🎙️ **Official Master of Ceremony** &mdash; Wisuda ke-28 Universitas Muhammadiyah Riau
- 🏛️ **Steering &amp; Committee Lead** &mdash; NIFC 4.0 National Event (2025)
- 👨‍🏫 **Lead Coordinator** &mdash; UMRI Web Design &amp; Development Study Club
- 🏆 **40+ Regional &amp; National Accolades** across competitive programming, public speaking, debates, and academic writing

---

### Contribution Timeline

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ilmialfa/Ilmialfa/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ilmialfa/Ilmialfa/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/Ilmialfa/Ilmialfa/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</div>

---

<div align="center">
  <sub>M. Ilmi Alfaridzi &bull; Pekanbaru, Indonesia &bull; Built with precision, performance, and craft</sub>
</div>
