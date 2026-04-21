<div align="center">

<!-- HERO BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,50:1a1a2e,100:16213e&height=200&section=header&text=Daniel%20Castro%20Pedraza&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Full%20Stack%20Developer%20%C2%B7%20Product%20Engineer&descSize=18&descAlignY=58&descColor=64b5f6&animation=fadeIn" />

<!-- BADGES DE ESTADO -->
<a href="mailto:danielcastro.dev@gmail.com">
  <img src="https://img.shields.io/badge/Available%20for%20Work-✓-00c853?style=for-the-badge&labelColor=0d0d0d" />
</a>
<a href="https://linkedin.com/in/daniel-castro-pedraza">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d0d0d" />
</a>
<a href="https://portafolio-pi-fawn-16.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-Live-FF6B6B?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d0d0d" />
</a>
<img src="https://komarev.com/ghpvc/?username=daniel-castro-pedraza&style=for-the-badge&color=1565c0&labelColor=0d0d0d&label=Profile+Views" />

<br/><br/>

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=64B5F6&center=true&vCenter=true&width=700&lines=3+productos+propios+en+producción+%F0%9F%9A%80;Full+Stack+%7C+Next.js+%7C+TypeScript+%7C+Supabase;RAG+engines+%7C+Stripe+%7C+pgvector;Del+sector+comercial+al+código+que+vende)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```typescript
const daniel = {
  role:       "Full Stack Developer & Product Engineer",
  location:   "Bogotá, Colombia 🇨🇴  |  UTC-5",
  available:  ["Remote", "On-site LATAM"],
  contract:   ["Full-time", "Freelance", "Contract"],

  background: "Vengo del sector comercial tech — antes de escribir código,",
              "aprendí a leer métricas de negocio y entender fricciones reales",
              "de usuario. Eso cambió cómo construyo software.",

  building:   [
    "FreeFlow CRM  →  SaaS freemium con pagos reales (Stripe)",
    "DocuMente     →  Motor RAG para mercado legal/contable LATAM",
    "Visión 360    →  Auditoría financiera con IA en tiempo real",
  ],

  philosophy: "No solo escribo código que funciona.",
              "Construyo productos que generan retorno medible.",
};
```

---

## 🚀 Proyectos en Producción

> Tres productos propios. Código real. Usuarios reales. Problemas reales.

---

### ⚡ FreeFlow CRM — SaaS Freemium "Lead-to-Cash"

<img src="https://img.shields.io/badge/STATUS-LIVE-00c853?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/PLAN%20PRO-$19%2Fmes-FF6B6B?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/STACK-Next.js%2015%20·%20Stripe%20·%20Supabase-64b5f6?style=flat-square&labelColor=0d0d0d" />

CRM para freelancers que **automatiza el ciclo completo**: Cliente → Propuesta → Proyecto → Factura → Cobro

| Feature | Implementación |
|---|---|
| 💳 Monetización real | Stripe Checkout + Billing Portal — plan Free / Pro $19/mes |
| 🔄 Suscripciones recurrentes | Webhooks `checkout.session.completed` · `customer.subscription.deleted` |
| 🔐 Auth multitenant SSR | Row Level Security — cada usuario accede **solo** a sus datos |
| ⚡ Performance | Server Components + Streaming para carga instantánea |

```
Stack: Next.js 15 · React 19 · TypeScript 5 · Supabase · Stripe · Tailwind 4 · Radix UI
```

---

### 🧠 DocuMente — Motor RAG de Alta Precisión

<img src="https://img.shields.io/badge/STATUS-LIVE-00c853?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/MERCADO-Legal%20%26%20Contable%20LATAM-a78bfa?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/LATENCIA-ms-00e676?style=flat-square&labelColor=0d0d0d" />

Análisis documental con IA diseñado para el **mercado contable y legal colombiano**

| Feature | Implementación |
|---|---|
| 🔍 Búsqueda semántica | pgvector nativo en PostgreSQL — latencia en milisegundos |
| 🤖 Embeddings sin costo | Pipeline propio de vectorización 384D — sin APIs externas costosas |
| ⚖️ Orquestación híbrida | Groq (velocidad) + Gemini (análisis profundo) — según contexto |
| 📄 Precisión documental | Chunking + re-ranking optimizado para documentos legales en español |

```
Stack: Next.js 15 · React 19 · TypeScript · Supabase · PostgreSQL pgvector · Groq · Gemini API
```

---

### 📊 Visión 360 — Plataforma de Auditoría Financiera con IA

<img src="https://img.shields.io/badge/STATUS-LIVE-00c853?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/DATOS-+10.000%20registros-ffb300?style=flat-square&labelColor=0d0d0d" /> <img src="https://img.shields.io/badge/IA-Google%20Gemini-4285F4?style=flat-square&labelColor=0d0d0d" />

Dashboard financiero en tiempo real para empresas — procesando **+10.000 registros reales**

| Feature | Implementación |
|---|---|
| 🔮 Diagnósticos automáticos | Google Gemini (NLP) — identifica patrones y anomalías de flujo de caja |
| 🌎 Soporte LATAM | Normalización de moneda para formatos colombianos y regionales |
| ⚡ Reportes atómicos | Server Actions — elimina latencia en operaciones críticas |
| 📈 Tiempo real | Dashboard live sin polling — actualizaciones push vía Supabase Realtime |

```
Stack: Next.js 14 · TypeScript · React · Supabase · PostgreSQL · Google Gemini API · Tailwind
```

---

## 🛠️ Stack Técnico

<div align="center">

### Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=for-the-badge&logo=radix-ui&logoColor=white)

### Backend & Base de Datos
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-626CD9?style=for-the-badge&logo=Stripe&logoColor=white)

### IA & LLMs
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Herramientas & DevOps
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

</div>

---

## 📈 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO_GITHUB&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=64b5f6&icon_color=64b5f6&text_color=c9d1d9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO_GITHUB&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=64b5f6&text_color=c9d1d9"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=TU_USUARIO_GITHUB&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=64B5F6&ring=64B5F6&fire=FF6B6B&currStreakLabel=64B5F6)](https://git.io/streak-stats)

</div>

---

## 🤝 Hablemos

> Busco equipos que construyan productos con impacto real — no solo features.

<div align="center">

| Canal | Link |
|---|---|
| 📧 Email | [danielcastro.dev@gmail.com](mailto:danielcastro.dev@gmail.com) |
| 💼 LinkedIn | [daniel-castro-pedraza](https://linkedin.com/in/daniel-castro-pedraza) |
| 🌐 Portfolio | [Ver proyectos en vivo →](https://portafolio-pi-fawn-16.vercel.app) |
| 💬 WhatsApp | [+57 311 518 4218](https://wa.me/573115184218) *(LATAM)* |

</div>

---

<div align="center">

*"El mejor código es el que resuelve un problema real — y lo hace de forma que el usuario ni lo note."*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0f0f0f&height=100&section=footer&animation=fadeIn" />

</div>
