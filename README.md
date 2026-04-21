<!-- ============================================================
     DANIEL CASTRO PEDRAZA — README PROFILE
     SYSTEM_VER_2026 // FULL STACK DEVELOPER
     ============================================================ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:1a0000,100:0d0d0d&height=200&section=header&text=DANIEL%20CASTRO%20PEDRAZA&fontSize=40&fontColor=ffffff&fontAlignY=40&fontAlign=50&desc=%5B%20FULL_STACK_DEVELOPER%20%2F%2F%20PRODUCT_ENGINEER%20%2F%2F%20BOG_COL%20%5D&descSize=14&descAlignY=62&descAlign=50&descColor=999999&animation=fadeIn" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=16&duration=2000&pause=600&color=CC0000&center=true&vCenter=true&width=700&lines=Product+Engineer+%2F%2F+Full+Stack+Developer;3+Productos+Propios+en+Producción+%2F%2F+Usuarios+Reales;Especialista+en+Next.js+%2F%2F+RAG+Engine+%2F%2F+Fintech)](https://github.com/DanielcoderIA)

</div>

---

<div align="center">

<a href="https://www.linkedin.com/in/daniel-castro-pedraza/"><img src="https://img.shields.io/badge/⚡_LINKEDIN-Conectar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=000000" /></a>
&nbsp;
<a href="https://github.com/DanielcoderIA"><img src="https://img.shields.io/badge/⌘_GITHUB-DanielcoderIA-181717?style=for-the-badge&logo=github&logoColor=ffffff&labelColor=000000" /></a>
&nbsp;
<a href="mailto:danicoder2001@gmail.com"><img src="https://img.shields.io/badge/@_EMAIL-danicoder2001-CC0000?style=for-the-badge&logo=gmail&logoColor=white&labelColor=000000" /></a>
&nbsp;
<a href="https://portafolio-pi-fawn-16.vercel.app"><img src="https://img.shields.io/badge/🌐_PORTFOLIO-Ver_en_vivo-ffffff?style=for-the-badge&logo=vercel&logoColor=000000&labelColor=000000" /></a>
&nbsp;
<a href="https://portafolio-pi-fawn-16.vercel.app/Daniel_Castro_CV_v3.pdf"><img src="https://img.shields.io/badge/📄_CV-Descargar-CC0000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white&labelColor=000000" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=DanielcoderIA&style=for-the-badge&color=CC0000&labelColor=000000&label=PROFILE_VIEWS" />

</div>

---

## `/// PERFIL_FULL STACK`

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║   ID            →  Daniel Castro Pedraza                                ║
║   ROL           →  Full Stack Developer  //  Product Engineer            ║
║   UBICACIÓN     →  Bogotá, Colombia 🇨🇴   //  UTC-5                      ║
║   DISPONIBILIDAD→  Remoto (global)  //  Presencial LATAM                 ║
║   CONTRATO      →  Full-time  //  Freelance  //  Contract                ║
║                                                                          ║
║   BACKGROUND    →  Sector comercial tech → ingeniería de producto.       ║
║                    Antes de escribir código, aprendí a leer métricas     ║
║                    de negocio y entender fricciones reales de usuario.   ║
║                    Eso cambió radicalmente cómo construyo software.      ║
║                                                                          ║
║   FILOSOFÍA     →  No solo escribo código que funciona.                  ║
║                    Construyo productos que generan retorno medible.      ║
║                                                                          ║
║   PORTFOLIO     →  portafolio-pi-fawn-16.vercel.app                     ║
║   CV            →  Daniel_Castro_CV_v3.pdf  [disponible para descarga]   ║
║                                                                          ║
║   STATUS        →  [ ██████████ ] OPEN_TO_WORK  ✓                       ║
║   SYNC          →  [ ██████████ ] 100%                                   ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```

</div>

---

## `DATA_LOGS [ PROYECTOS EN PRODUCCIÓN ]`

> **Tres productos propios · Código real · Usuarios reales · Problemas reales**
> Cada proyecto nace de un dolor de negocio específico. Cada línea de código tiene un propósito medible.

---

### `[01] ⚡ FREEFLOW CRM — SaaS Freemium "Lead-to-Cash"`

<img src="https://img.shields.io/badge/STATUS-LIVE-CC0000?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/PLAN_PRO-$19%2Fmes-555555?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/STRIPE-Pagos_reales_activos-635BFF?style=flat-square&logo=stripe&logoColor=white&labelColor=000000" /> <img src="https://img.shields.io/badge/NEXT.JS-15-ffffff?style=flat-square&logo=nextdotjs&logoColor=000000&labelColor=000000" />

**Plataforma de gestión financiera integral para agencias y freelancers.**
Automatiza el ciclo comercial completo — desde la captación del lead hasta el cobro final: **Cliente → Propuesta → Proyecto → Factura → Cobro**

**LOGRO CLAVE:** Ciclo de vida del cliente 100% centralizado. Facturación automatizada vía Stripe con monitoreo de KPIs financieros en tiempo real, eliminando la dependencia de herramientas externas costosas.

| MÓDULO | IMPLEMENTACIÓN TÉCNICA |
|---|---|
| 💳 **Monetización real** | Stripe Checkout + Billing Portal · Plan Free / Pro $19/mes · pagos activos en producción |
| 🔄 **Suscripciones recurrentes** | Webhooks `checkout.session.completed` · `customer.subscription.deleted` · manejo de estados de pago |
| 🔐 **Autenticación multitenant SSR** | Row Level Security en Supabase — aislamiento total de datos por tenant, sin exposición cruzada |
| ⚡ **Performance arquitectural** | Server Components + Streaming — hidratación mínima del cliente, cero layout shift |
| 📊 **KPIs en tiempo real** | Dashboard live vía Supabase Realtime — actualizaciones push, sin polling ni dependencia de cron jobs |

```
STACK: Next.js 15 · React 19 · TypeScript 5 · Supabase · PostgreSQL · Stripe · Tailwind CSS 4 · Radix UI
```

🔗 **[→ VER DEMO EN VIVO](https://freeflow-crm.vercel.app/)** &nbsp;|&nbsp; **[→ VER REPOSITORIO](https://github.com/DanielcoderIA/freeflow-crm)**

---

### `[02] 🧠 DOCUMENTE — Motor RAG de Alta Precisión`

<img src="https://img.shields.io/badge/STATUS-LIVE-CC0000?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/MERCADO-Legal_%26_Contable_LATAM-555555?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/EMBEDDINGS-384D_propios-888888?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/NEXT.JS-15-ffffff?style=flat-square&logo=nextdotjs&logoColor=000000&labelColor=000000" />

**Motor de análisis documental con IA especializado en el mercado legal y contable colombiano.**
Procesa PDFs complejos con búsqueda vectorial semántica — permite consultas en lenguaje natural sobre múltiples documentos de forma simultánea, sin depender de APIs externas costosas.

**LOGRO CLAVE:** Pipeline RAG propio con embeddings 384D y búsqueda semántica nativa en PostgreSQL. Estrategia de Recursive Character Splitting + Re-ranking semántico que minimiza alucinaciones en textos legales colombianos, logrando respuestas precisas con latencia de milisegundos.

| MÓDULO | IMPLEMENTACIÓN TÉCNICA |
|---|---|
| 🔍 **Búsqueda semántica nativa** | pgvector en PostgreSQL — búsqueda por similitud coseno en milisegundos, sin servicios externos |
| 🤖 **Pipeline de embeddings propio** | Vectorización 384D sin APIs de terceros — independencia total, costo marginal cercano a cero |
| 📄 **Chunking optimizado para lo legal** | Recursive Character Splitting + Re-ranking semántico calibrado para documentos legales en español colombiano |
| ⚖️ **Orquestación híbrida de LLMs** | Groq (velocidad en consultas simples) ↔ Gemini (análisis profundo y multi-documento) · enrutamiento inteligente por complejidad |
| 🛡️ **Control de alucinaciones** | Retrieval con threshold de similitud ajustado + ventana de contexto optimizada por tipo documental |

```
STACK: Next.js 15 · React 19 · TypeScript · Supabase · PostgreSQL + pgvector · Clerk · LangChain · Groq · Gemini API
```

🔗 **[→ VER DEMO EN VIVO](https://documente.vercel.app/)** &nbsp;|&nbsp; **[→ VER REPOSITORIO](https://github.com/DanielcoderIA/documente)**

---

### `[03] 📊 VISIÓN 360 — Plataforma de Auditoría Financiera con IA`

<img src="https://img.shields.io/badge/STATUS-LIVE-CC0000?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/DATOS-+10.000_registros_reales-555555?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/PERFORMANCE-40%25_menos_carga-888888?style=flat-square&labelColor=000000" /> <img src="https://img.shields.io/badge/NEXT.JS-15-ffffff?style=flat-square&logo=nextdotjs&logoColor=000000&labelColor=000000" />

**Panel financiero en tiempo real para la toma de decisiones estratégicas en LATAM.**
Visualiza y diagnostica más de 10.000 registros financieros reales con análisis automático por IA — diseñado para que directivos tomen decisiones en segundos, no en horas.

**LOGRO CLAVE:** Reducción del 40% en tiempo de carga al migrar a Server Actions y virtualización de datos. Diagnósticos automáticos de flujo de caja mediante Gemini NLP que identifican patrones y anomalías sin intervención humana.

| MÓDULO | IMPLEMENTACIÓN TÉCNICA |
|---|---|
| 🔮 **Diagnósticos automáticos con IA** | Google Gemini NLP — detecta patrones anómalos de flujo de caja y genera alertas interpretables para no técnicos |
| 🌎 **Soporte financiero LATAM** | Normalización y formateo de moneda para estándares colombianos, mexicanos y regionales sin pérdida de precisión |
| ⚡ **Reportes de latencia cero** | Server Actions — eliminación completa de la latencia en operaciones críticas de reporting financiero |
| 📈 **Actualizaciones en tiempo real** | Supabase Realtime con suscripciones WebSocket — datos siempre frescos, sin polling ni refreshes manuales |
| 🚀 **Performance con datos masivos** | Virtualización + lazy loading de +10K puntos de datos sin degradación perceptible de la interfaz |

```
STACK: Next.js 15 · TypeScript · React · Supabase · PostgreSQL · Google Gemini API · Tailwind CSS
```

🔗 **[→ VER DEMO EN VIVO](https://vision-360-mu.vercel.app/)** &nbsp;|&nbsp; **[→ VER REPOSITORIO](https://github.com/DanielcoderIA/vision-360)**

---

## `SYSTEM_MODULES [ STACK TÉCNICO ]`

<div align="center">

### `CORE_01 // LENGUAJES Y FRAMEWORKS`

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=ffffff)
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### `CORE_02 // DISEÑO Y ESTILIZACIÓN`

![Tailwind](https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-333333?style=for-the-badge&logo=radix-ui&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS_Modules-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### `CORE_03 // INFRAESTRUCTURA Y BASE DE DATOS`

![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=ffffff)

### `CORE_04 // IA Y LLMs`

![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-CC0000?style=for-the-badge&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-333333?style=for-the-badge&logo=langchain&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### `CORE_05 // HERRAMIENTAS Y DEVOPS`

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=ffffff)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

</div>

---

## `SYNC_STATS [ ACTIVIDAD EN GITHUB ]`

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=DanielcoderIA&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=000000&title_color=CC0000&icon_color=CC0000&text_color=cccccc" />
&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DanielcoderIA&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=000000&title_color=CC0000&text_color=cccccc" />

<br/>

[![GitHub Streak](https://streak-stats.demolab.com?user=DanielcoderIA&theme=github-dark-blue&hide_border=true&background=000000&stroke=CC0000&ring=CC0000&fire=CC0000&currStreakLabel=ffffff&sideLabels=cccccc&dates=888888)](https://github.com/DanielcoderIA)

</div>

---

## `COMM_LINK [ HANDSHAKE ]`

<div align="center">

> **Listo para unirme a un equipo de alto rendimiento.**
> Si buscas un desarrollador que entienda el equilibrio entre código limpio y necesidades de negocio,
> que construya con criterio de producto y que mida su trabajo en resultados — **hablemos.**

<br/>

| CANAL | DIRECCIÓN | ENLACE |
|:---:|:---:|:---:|
| ✉ **EMAIL** | danicoder2001@gmail.com | [→ Enviar correo](mailto:danicoder2001@gmail.com) |
| ⚡ **LINKEDIN** | daniel-castro-pedraza | [→ Conectar](https://www.linkedin.com/in/daniel-castro-pedraza/) |
| ⌘ **GITHUB** | DanielcoderIA | [→ Ver repositorios](https://github.com/DanielcoderIA) |
| 🌐 **PORTFOLIO** | portafolio-pi-fawn-16.vercel.app | [→ Ver portfolio](https://portafolio-pi-fawn-16.vercel.app) |
| 📄 **CV** | Daniel_Castro_CV_v3.pdf | [→ Descargar CV](https://portafolio-pi-fawn-16.vercel.app/Daniel_Castro_CV_v3.pdf) |

</div>

---

<div align="center">

```
SYSTEM_VER_2026 // FINAL_BUILD
© 2026 DANIEL CASTRO PEDRAZA — BOGOTÁ, COLOMBIA
"El mejor código es el que resuelve un problema real
 — y lo hace de forma que el usuario ni lo note."
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0000,50:0d0d0d,100:000000&height=100&section=footer&animation=fadeIn" />

</div>
