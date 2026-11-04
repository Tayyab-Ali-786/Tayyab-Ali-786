<div align="center">

<a href="https://github.com/Tayyab-Ali-786"><img src="assets/svg/hero.svg" width="100%" alt="Tayyab Ali Rashid — engineering real-time AI products"/></a>

<a href="mailto:tayyabalirashid3@gmail.com"><img src="assets/svg/buttons/email.svg" height="44" alt="Hire me"/></a>&nbsp;
<a href="https://www.linkedin.com/in/tayyab-ali-rashid-a471a7309/"><img src="assets/svg/buttons/linkedin.svg" height="44" alt="LinkedIn"/></a>&nbsp;
<a href="https://www.upwork.com/freelancers/~0123585ca8987bac94"><img src="assets/svg/buttons/upwork.svg" height="44" alt="Upwork"/></a>&nbsp;
<a href="https://github.com/Tayyab-Ali-786?tab=repositories"><img src="assets/svg/buttons/github.svg" height="44" alt="All repositories"/></a>

<img src="https://readme-typing-svg.demolab.com?font=Syne&weight=700&size=18&duration=2600&pause=1200&color=FFFFFF&center=true&vCenter=true&width=880&lines=STREAMING+LATENCY%3A+~600MS+%E2%86%92+UNDER+33MS;GO+%C2%B7+PION+%C2%B7+WEBRTC+%C2%B7+GRPC;BUILT+SMOKESCREEN+V2+SOLO+%E2%80%94+LIVE+AI+VIDEO+SAAS;NEXT.JS+%C2%B7+NODE.JS+%C2%B7+SUPABASE+%C2%B7+GPU+INFRA;OPEN+TO+REMOTE+ROLES+%26+FREELANCE" alt="Typing intro"/>

<a href="#projects"><b>PROJECTS</b></a> &nbsp;·&nbsp; <a href="#experience"><b>EXPERIENCE</b></a> &nbsp;·&nbsp; <a href="#about"><b>ABOUT</b></a> &nbsp;·&nbsp; <a href="#stack"><b>STACK</b></a> &nbsp;·&nbsp; <a href="#education"><b>EDUCATION</b></a> &nbsp;·&nbsp; <a href="#activity"><b>ACTIVITY</b></a>

</div>

<a id="projects"></a>
<img src="assets/svg/headings/projects.svg" width="100%" alt="01 What I build"/>

<a href="https://github.com/Tayyab-Ali-786/web_stream"><img src="assets/svg/projects/streaming.svg" width="100%" alt="Low-latency WebRTC stack"/></a>

A Go streaming server on **Pion WebRTC** that ingests H.264 from **GStreamer** over UDP/RTP and broadcasts it to browsers. Its **Frame-Aware Metronome** assembles complete access units before bursting RTP, which took latency from **~600ms to under 33ms**. It also has a packet interceptor and jitter buffer. The Next.js viewer's `useStreamSession` hook owns the whole WebRTC lifecycle: SDP signaling, ICE queuing, adaptive jitter buffering, codec negotiation, freeze detection and auto-reconnect.

[**Server — web_stream ↗︎**](https://github.com/Tayyab-Ali-786/web_stream) &nbsp;·&nbsp; [**Viewer — web ↗︎**](https://github.com/Tayyab-Ali-786/web)

<table>
<tr>
<td width="50%" valign="top">
<a href="https://ajaia-docs-mpvh.onrender.com"><img src="assets/svg/projects/ajaia.svg" width="100%" alt="Ajaia Docs"/></a>
<br/>Create, format, autosave and share docs as viewer or editor. Version numbers on every save give a <b>409 "Reload"</b> instead of silent overwrites, plus full version history with restore, <code>.docx</code>/<code>.md</code> import and Markdown export. Postgres in prod, PGlite (WASM) in tests.
<br/><a href="https://ajaia-docs-mpvh.onrender.com"><b>Live ↗︎</b></a> &nbsp;·&nbsp; <a href="https://github.com/Tayyab-Ali-786/ajaia-docs"><b>Code ↗︎</b></a>
</td>
<td width="50%" valign="top">
<a href="https://chattify-seven.vercel.app"><img src="assets/svg/projects/chattify.svg" width="100%" alt="Chattify"/></a>
<br/>Peer-to-peer chat rooms over WebRTC data channels, end-to-end encrypted with the Web Crypto API. Each peer derives a shared key via <b>ECDH P-256</b> and encrypts messages with <b>AES-GCM</b>, so the server never sees plaintext. Includes a JWT auth server.
<br/><a href="https://chattify-seven.vercel.app"><b>Live ↗︎</b></a> &nbsp;·&nbsp; <a href="https://github.com/Tayyab-Ali-786/Chattify"><b>Code ↗︎</b></a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://gdc-solution.vercel.app"><img src="assets/svg/projects/founderbrain.svg" width="100%" alt="Founder Brain"/></a>
<br/>An AI layer that watches founders' daily decisions and flags "coordination gaps", like sales promising a feature engineering just cut. Gemini checks each new action against Firestore history, and alerts land live via <code>onSnapshot</code>. Placed <b>5th of 17</b> at the Google AI Hackathon.
<br/><a href="https://gdc-solution.vercel.app"><b>Live ↗︎</b></a> &nbsp;·&nbsp; <a href="https://github.com/Tayyab-Ali-786/GDC_Solution"><b>Code ↗︎</b></a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/Tayyab-Ali-786/ShippiFy"><img src="assets/svg/projects/cartx.svg" width="100%" alt="CARTX"/></a>
<br/>A MERN e-commerce store with product categories, auth and password reset, cart management, Cloudinary images and <b>Stripe</b> checkout. React + TypeScript client with Tailwind and React Query.
<br/><a href="https://github.com/Tayyab-Ali-786/ShippiFy"><b>Code ↗︎</b></a>
</td>
</tr>
</table>

**More projects**

| Project | What it is | Built with | Links |
|:--|:--|:--|:--|
| **Prepify** | AI mock interviews with a real-time voice agent | Next.js · OpenAI · Vapi | [Live](https://ai-mock-interview-lake-two.vercel.app) · [Code](https://github.com/Tayyab-Ali-786/Ai_Mock_Interview) |
| **FIFA Match Analytics** | Stats dashboard over 128 World Cup matches with a linear-regression goal predictor | Next.js · Node · Python | [Code](https://github.com/Tayyab-Ali-786/Data_Analyzer) |
| **Smart Campus Graph** | Campus navigation and door-access system on weighted graphs | C++ | [Code](https://github.com/Tayyab-Ali-786/SmartCampusGraphSystem) |
| **Brick Buster** | Breakout clone written in x86 Assembly | Assembly | [Code](https://github.com/Tayyab-Ali-786/Brick-Buster) |

<a id="experience"></a>
<img src="assets/svg/headings/experience.svg" width="100%" alt="02 Where I ship"/>

<img src="assets/svg/projects/huvio.svg" width="100%" alt="Huvio AI"/>

**Full-Stack & Streaming Engineer · Huvio AI.** I took over a gRPC-based WebRTC pipeline that had been broken for over a month. It had no reconnect logic, hardcoded TURN credentials, drip-fed packets and zero observability. I redesigned the pacing, fixed 7 production bugs (IDR detection, buffer depth, auth middleware, auto-reconnect and more), and added a gRPC simulator for testing against production frames.

<img src="assets/svg/projects/smokescreen.svg" width="100%" alt="SmokeScreen V2"/>

**Lead Full-Stack Developer · JayTech Elite Firm.** I built **SmokeScreen V2** end to end on my own: frontend, backend and database, with voice cloning, photo-to-video, AI photo editing and a low-latency face-swap pipeline. I also shipped the Electron desktop app, migrated V1 users to a new Supabase database, and integrated Flutterwave, Squadco and crypto payments. It's at **~25,000 users** and growing.

<a id="about"></a>
<img src="assets/svg/headings/about.svg" width="100%" alt="03 Who I am"/>

### I build the parts of a product where milliseconds matter — live video, AI pipelines, and the SaaS around them.

I'm a **Full-Stack Developer and Real-Time Video Streaming Engineer**. One side of my work is **WebRTC, gRPC and Go** pipelines. The other is **Next.js, Node.js and Supabase** products, plus the payments, GPU infra and production debugging it takes to ship them.

📍 Lahore / Faisalabad, Pakistan &nbsp;·&nbsp; 🎓 BSCS @ FAST-NUCES &nbsp;·&nbsp; ⚡ Top Rated on Upwork &nbsp;·&nbsp; 🌍 Open to remote roles

<img src="assets/svg/strengths.svg" width="100%" alt="What I do best"/>

<a id="stack"></a>
<img src="assets/svg/headings/stack.svg" width="100%" alt="04 My stack"/>

<img src="assets/svg/stack/streaming.svg" width="100%" alt="Real-time and media"/>

<p>
<img src="assets/svg/stack/languages.svg" width="49%" alt="Languages"/>
<img src="assets/svg/stack/ai.svg" width="49%" alt="AI and voice"/>
</p>
<p>
<img src="assets/svg/stack/frontend.svg" width="49%" alt="Frontend"/>
<img src="assets/svg/stack/backend.svg" width="49%" alt="Backend and data"/>
</p>
<p>
<img src="assets/svg/stack/payments.svg" width="49%" alt="Payments"/>
<img src="assets/svg/stack/infra.svg" width="49%" alt="Infra and DevOps"/>
</p>

<a id="education"></a>
<img src="assets/svg/headings/education.svg" width="100%" alt="05 How I learn"/>

### 🎓 BS Computer Science — FAST-NUCES, Chiniot-Faisalabad Campus
`Batch Fall-2024`

| Program | Issuer |
|:--|:--|
| **Generative AI Training — Cohort 3** | Pak Angels |
| **Technical Internship — January 2026 Batch** | CodeAlpha |
| **Google AI Hackathon — 5th of 17 teams** | FAST-NUCES CFD |

<a id="activity"></a>
<img src="assets/svg/headings/activity.svg" width="100%" alt="06 On GitHub"/>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Tayyab-Ali-786&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&border_radius=18&bg_color=000000&title_color=FFFFFF&icon_color=A3A3A3&text_color=D4D4D4&ring_color=FFFFFF" height="170" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Tayyab-Ali-786&layout=compact&hide_border=true&border_radius=18&bg_color=000000&title_color=FFFFFF&text_color=D4D4D4&langs_count=8" height="170" alt="Top languages"/>
</p>
<p align="center">
<img src="https://streak-stats.demolab.com/?user=Tayyab-Ali-786&hide_border=true&border_radius=18&background=000000&ring=FFFFFF&fire=FFFFFF&currStreakLabel=FFFFFF&currStreakNum=FFFFFF&sideNums=FFFFFF&sideLabels=A3A3A3&dates=737373&stroke=262626" width="80%" alt="GitHub streak"/>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Tayyab-Ali-786/Tayyab-Ali-786/output/snake-dark.svg"/>
  <img src="https://raw.githubusercontent.com/Tayyab-Ali-786/Tayyab-Ali-786/output/snake-light.svg" width="100%" alt="Snake eating my contribution graph"/>
</picture>

<a href="mailto:tayyabalirashid3@gmail.com"><img src="assets/svg/contact.svg" width="100%" alt="Contact: tayyabalirashid3@gmail.com"/></a>

<p align="center"><img src="https://komarev.com/ghpvc/?username=Tayyab-Ali-786&color=000000&style=flat-square&label=PROFILE+VIEWS" alt="Profile views"/></p>
