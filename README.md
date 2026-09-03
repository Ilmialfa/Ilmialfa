<div align="center">

  <img src="assets/banner.svg" alt="M. Ilmi Alfaridzi" width="100%" />

  <br /><br />

  <p align="center">
    <a href="https://www.linkedin.com/in/m-ilmi-alfaridzi-7a5a02293" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;
    <a href="mailto:alfaridziilmi@gmail.com">
      <img src="https://img.shields.io/badge/Email-0F172A?style=flat&logo=gmail&logoColor=white" alt="Email" />
    </a>
    &nbsp;
    <a href="https://www.instagram.com/ilmialfaridzi" target="_blank">
      <img src="https://img.shields.io/badge/Instagram-0F172A?style=flat&logo=instagram&logoColor=white" alt="Instagram" />
    </a>
    &nbsp;
    <a href="https://wa.me/6282248001571" target="_blank">
      <img src="https://img.shields.io/badge/WhatsApp-0F172A?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp" />
    </a>
    &nbsp;
    <a href="https://github.com/Ilmialfa/Portofolio-M-Ilmi-Alfaridzi" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-0F172A?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio" />
    </a>
  </p>

</div>

---

## About

I am an Informatics undergraduate at **Universitas Muhammadiyah Riau (UMRI)** and a full-stack web developer. My core work revolves around building responsive web applications using **Laravel**, **Next.js**, and **TypeScript**, with an emphasis on local-first processing, client-side performance, and practical UI design.

Outside of writing code, I actively organize technology and campus events. I have led study clubs on web design, served as the Master of Ceremonies for major university ceremonies (including the 28th UMRI Graduation), and earned more than 40 regional and national accolades across competitive programming, public speaking, and community programs.

---

## Tech Stack

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=laravel,php,nextjs,react,ts,js,tailwind,html,css&theme=light" alt="Frontend and Backend Stack" />
  </a>
  <br />
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mysql,sqlite,git,github,postman,vite,vitest,figma,vercel&theme=light" alt="Database and Developer Tooling" />
  </a>
</div>

<br />

- **Languages &amp; Runtimes**: PHP 8.3+, TypeScript, JavaScript (ESNext), HTML5, CSS3, SQL
- **Frameworks &amp; Libraries**: Laravel 11/12, Next.js (App Router), React 19, Inertia.js, Filament PHP, Tailwind CSS, Framer Motion
- **Tooling &amp; Storage**: MySQL, SQLite, WebAssembly (WASM), Git, Vite, Vitest, Postman, pnpm, Vercel

---

## Featured Projects

### [OmniConvert](https://github.com/Ilmialfa/OmniConvert)
> **Browser-first file conversion toolkit with 100% client-side privacy**

- Converts 56+ formats across images, documents, audio, video, and structured data.
- Built with **Next.js**, **Tailwind CSS**, and **WebAssembly (FFmpeg &amp; Tesseract OCR)**.
- Operates entirely within the browser memory sandbox — zero files are uploaded to any server.
- Supports batch conversion queues, duplicate detection, and ZIP package export.

[Live Application ↗](https://omniconvert-mu.vercel.app) &bull; [Source Code ↗](https://github.com/Ilmialfa/OmniConvert)

---

### [Website Batik KKN](https://github.com/Ilmialfa/website-batik-kkn)
> **Cultural heritage digitization &amp; e-commerce platform for local UMKM artisans**

- Built for the community empowerment program at Universitas Muhammadiyah Riau.
- Powered by **Laravel 12**, **Inertia.js React**, and **Filament PHP Admin**.
- Features an interactive digital motif encyclopedia, artisan narrative showcase, and direct buyer inquiry flows.
- Clean separation of customer catalog and operational admin dashboard.

[Source Code ↗](https://github.com/Ilmialfa/website-batik-kkn)

---

### [FinSight AI](https://github.com/Ilmialfa/finsight-ai)
> **Financial intelligence dashboard with automated AI transaction categorization**

- Engineered with **Next.js 16 (Turbopack)**, **React 19**, and **OpenAI Structured Outputs**.
- Analyzes spending trends and visualizes cash flow predictions through **Recharts**.
- Provides a conversational personal advisor to help evaluate monthly budget health.

[Source Code ↗](https://github.com/Ilmialfa/finsight-ai)

---

### [Toko Putera Kembar](https://github.com/Ilmialfa/toko-putera-kembar)
> **Point of Sale (POS), real-time inventory tracking, and retail management system**

- Developed with **Laravel 12**, **Inertia.js React**, and **TypeScript**.
- Incorporates **Spatie Role-Based Access Control** (Cashier, Warehouse Staff, Store Owner).
- Includes automated database backup routines, stock anomaly warnings, and receipt printing.

[Source Code ↗](https://github.com/Ilmialfa/toko-putera-kembar)

---

## Interactive Terminal

Simulate a local session in the browser. Click any command below to execute:

```bash
ilmi@workstation:~$ ./cli.sh --interactive
```

<details>
  <summary><code>$ ilmi status --verbose</code> &mdash; View current focus and active projects</summary>
  <br />
  <pre>
[STATUS REPORT]
Date       : 2026-09-03
Location   : Pekanbaru, Indonesia
University : Universitas Muhammadiyah Riau (UMRI)
Major      : Informatics Engineering
Status     : Active Development &bull; Available for select engineering roles
Primary    : Laravel 12 &bull; Next.js 16 &bull; TypeScript &bull; WebAssembly
  </pre>
</details>

<details>
  <summary><code>$ ilmi debug --puzzle</code> &mdash; Mini Game: Resolve the concurrency deadlock</summary>
  <br />
  <p><strong>Scenario:</strong> You are dispatching 12 parallel video conversions in OmniConvert using WebAssembly. The browser tab memory spikes. Which architecture resolves this cleanly?</p>
  <ul>
    <li>Option A: Increase the Node.js memory limit.</li>
    <li>Option B: Spin up a pooled Web Worker queue with bounded concurrency (e.g. <code>navigator.hardwareConcurrency - 1</code>) and revoke Object URLs upon completion.</li>
    <li>Option C: Store all intermediate frames in <code>localStorage</code>.</li>
  </ul>
  <details>
    <summary><em>Click to verify solution</em></summary>
    <pre>
✓ Correct: Option B
Explanation: Web Workers prevent the UI thread from blocking, bounded concurrency
prevents Out-Of-Memory (OOM) browser crashes, and URL.revokeObjectURL() frees up heap space immediately.
    </pre>
  </details>
</details>

<details>
  <summary><code>$ ilmi achievements --list</code> &mdash; View extracurricular &amp; competition highlights</summary>
  <br />
  <pre>
[HONORS & LEADERSHIP HIGHLIGHTS]
- Master of Ceremony &bull; Wisuda ke-28 Universitas Muhammadiyah Riau (UMRI)
- Committee Lead &bull; NIFC 4.0 National Event 2025
- Lead Coordinator &bull; UMRI Web Development &amp; Design Study Club
- 40+ Awards &bull; Regional &amp; National competitions in Technology, Public Speaking, and Debate
  </pre>
</details>

---

## GitHub Statistics

<div align="center">
  <table border="0">
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/Ilmialfa">
          <img src="https://github-readme-stats.vercel.app/api?username=Ilmialfa&show_icons=true&theme=clean-white&hide_border=false&border_color=e2e8f0&title_color=0f172a&text_color=334155&icon_color=2563eb&bg_color=ffffff&border_radius=8" alt="GitHub Stats" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/Ilmialfa">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ilmialfa&layout=compact&theme=clean-white&hide_border=false&border_color=e2e8f0&title_color=0f172a&text_color=334155&bg_color=ffffff&border_radius=8" alt="Top Languages" />
        </a>
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <a href="https://github.com/Ilmialfa">
          <img src="https://streak-stats.demolab.com?user=Ilmialfa&theme=clean-white&border_radius=8&border=e2e8f0&background=ffffff&stroke=2563eb&ring=2563eb&fire=f59e0b&currStreakNum=0f172a&sideNums=334155&currStreakLabel=2563eb&sideLabels=64748b&dates=94a3b8" alt="GitHub Streak" />
        </a>
      </td>
    </tr>
  </table>
</div>

---

## Contribution Graph

<div align="center">
  <img src="https://raw.githubusercontent.com/Ilmialfa/Ilmialfa/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" width="100%" />
</div>

---

<div align="center">
  <p>
    <sub>Designed with focus on simplicity, readability, and performance &bull; &copy; 2026 M. Ilmi Alfaridzi</sub>
  </p>
</div>
