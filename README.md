<div align="center">

<a href="https://www.manuj.online">
  <img src="https://www.manuj.online/about/opengraph-image" width="100%" alt="Manuj Rai — Full-Stack & AI Engineer" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/manuj.online-8B5CF6?style=for-the-badge&logoColor=white)](https://www.manuj.online)
[![AI twin](https://img.shields.io/badge/ask_my_AI_twin-06B6D4?style=for-the-badge&logo=openai&logoColor=white)](https://www.manuj.online/chat)
[![Résumé](https://img.shields.io/badge/résumé-1F2937?style=for-the-badge&logo=readdotcv&logoColor=white)](https://www.manuj.online/Manuj/Manuj_Rai_Resume.pdf)
[![LinkedIn](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manujrai/)
[![Open to work](https://img.shields.io/badge/●_open_to_work-10B981?style=for-the-badge&logoColor=white)](mailto:manuj.services@gmail.com)

</div>

---

## `~/whoami`

```console
$ manuj --describe
Software Engineer @ Fibre2Fashion, Ahmedabad  ·  freelance full-stack by night
Two production AI systems shipped end to end on Python + FastAPI,
on an enterprise ASP.NET Core + SQL Server foundation.
```

I build LLM systems that survive contact with production — token budgets, retries,
structured output, metrics — and wire them into software real teams already use.
Enterprise backend habits applied to AI, and modern product delivery applied to internal tools.

---

## `~/shipped` — production AI systems

Both run daily inside Fibre2Fashion's editorial workflow.

<table>
<tr><td width="50%" valign="top">

### 📰 News Desk
**Human-in-the-loop story-discovery agent**

Harvests **~65 primary** and **~75 secondary** curated source pages across **17 countries**.
An LLM scores, de-dupes and ranks candidates, confirms each against its primary source, then
drafts publish-ready copy — every stage streamed live over SSE. Editors keep selection and review.

`Python` `FastAPI` `OpenAI · Gemini · Claude` `Playwright` `SQL Server` `SSE` `IIS`

> Hardened with an SSRF guard, token budgets, Prometheus metrics, a watchdog and
> interrupted-job recovery — **375 tests across 43 files**.

</td><td width="50%" valign="top">

### 📄 AI Article Gen
**Document-to-publish pipeline**

Turns a raw Word document into a publish-ready package — headline, key takeaways, table of
contents, body, SEO metadata, FAQs — plus the DOCX/PDF/HTM artefacts the public site serves.
Six phases, three JSON-mode LLM calls for a short article.

`Python` `FastAPI` `OpenAI · Claude · Gemini` `SQL Server` `IIS` `Prometheus`

> Editorial rules live as **fail-open SQL rows**, so guidelines change without a code deploy.

</td></tr>
</table>

<div align="right"><sub><a href="https://www.manuj.online/work">→ full case studies</a></sub></div>

---

## `~/projects`

| | Project | Stack | |
|---|---|---|---|
| 🧰 | **Karloo** — 20+ browser-first free online tools | `Next.js 16` `React 19` `TypeScript` `Tailwind v4` `OpenAI` | [live ↗](https://karloo.vercel.app/) |
| 🛍️ | **Trendverse** — D2C ecommerce storefront | `Next.js` `Supabase` `Razorpay` `Stripe` | [live ↗](https://trendverse.netlify.app/) |
| 💇 | **Hair Crezz** — salon booking template | `Next.js` `Supabase` `Postgres RLS` `Twilio` | [live ↗](https://hair-crezz-salon.vercel.app/) |
| 🤝 | **Kat-Katha** — NGO giving platform | `Next.js 15` `Vercel Postgres` `Razorpay` `Resend` | [live ↗](https://kat-katha-web.vercel.app/) |
| 🧠 | **AI Twin** — RAG over my own portfolio content | `Next.js` `Supabase` `pgvector` `HNSW` `OpenAI` | [live ↗](https://www.manuj.online/chat) |

---

## `~/stack`

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

</div>

| | |
|---|---|
| **🤖 AI** | LLM orchestration · RAG & vector search · Agents & agentic workflows · OpenAI · Claude · Gemini · Prompt engineering |
| **⚙️ Backend** | ASP.NET Core · SQL Server · Python / FastAPI · REST APIs · Supabase (DB · Edge · Auth) · Node.js |
| **🎨 Frontend** | Next.js / React · Tailwind · Framer Motion · Three.js / R3F |
| **🔍 Automation** | Playwright · Selenium · Pandas pipelines · Excel → SQL tooling |
| **💳 Product ops** | Razorpay · Stripe · Resend · MSG91 (OTP) · Cloudinary |
| **🚀 Deploy** | Vercel · Netlify · Render · IIS · GitHub Actions |

<details>
<summary><sub>self-rated proficiency, 1–5 — the same levels published on my About page</sub></summary>

<br/>

| Area | 5 / 5 | 4 / 5 | 3 / 5 |
|---|---|---|---|
| **Languages** | C# · TypeScript · JavaScript | Python · SQL | — |
| **AI engineering** | — | LLM orchestration · RAG & vector search · Agents · OpenAI/Claude/Gemini · Prompt engineering | — |
| **Backend** | ASP.NET Core · SQL Server · REST APIs | Supabase · Playwright / Selenium | Node.js |
| **Frontend** | Next.js / React · Tailwind | Framer Motion | Three.js / R3F |
| **Product ops** | Razorpay · Resend | Stripe · MSG91 · Cloudinary · Vercel / Render / Actions | — |

</details>

---

## `~/now`

```diff
+ Production-grade LLM systems — budgets, retries, structured output, observability
+ RAG at scale — chunking strategy, metadata filtering, pgvector + HNSW
+ Agentic workflows with real tool use and human-in-the-loop checkpoints
+ Carrying enterprise .NET + SQL discipline into AI services
- Shipping an LLM feature without metrics and calling it done
```

---

## `~/stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=manuj-rai&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=06B6D4&text_color=C9D1D9" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manuj-rai&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8B5CF6&text_color=C9D1D9" alt="Top languages" />

</div>

---

## `~/philosophy`

```js
while (curiosity) {
  build();
  learn();
  improve();
}
```

> Comments explain **why**, not what. An LLM feature isn't shipped until it has budgets and
> metrics. Own it end to end — empty repo to production.

---

<div align="center">

### `~/contact`

**[manuj.services@gmail.com](mailto:manuj.services@gmail.com)** · [manuj.online](https://www.manuj.online) · [LinkedIn](https://www.linkedin.com/in/manujrai/) · [Instagram](https://instagram.com/manuj_rai_official)

<sub>Open to AI engineering, backend and full-stack roles — plus select freelance builds. I reply within 24 hours.</sub>

<br/><br/>

<sub>🌙 dark mode · ☕ coffee · 🎧 late-night sessions · 🎮 gamer</sub>

![Visitors](https://komarev.com/ghpvc/?username=manuj-rai&color=8B5CF6&style=flat-square&label=visitors)

</div>
