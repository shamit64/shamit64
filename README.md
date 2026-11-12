<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:2563eb&height=200&section=header&text=Shamit%20Reddy&fontSize=56&fontColor=ffffff&fontAlignY=35&desc=Backend%20%26%20Full-Stack%20Developer%20%C2%B7%20Hyderabad&descSize=18&descAlignY=57&animation=fadeIn" width="100%" alt="Shamit Reddy — Backend & Full-Stack Developer, Hyderabad"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=2563EB&center=true&vCenter=true&width=600&lines=I+build+backends+and+test+them+properly;Python+%C2%B7+TypeScript+%C2%B7+PostgreSQL;Currently+building+RepoRescue;Open+to+SDE+internships" alt="I build backends and test them properly"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shamit-reddy-347438380/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge" alt="LinkedIn"/></a>
  <a href="mailto:reddyshamit@gmail.com"><img src="https://img.shields.io/badge/Email-reddyshamit%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/shamit64?tab=repositories"><img src="https://img.shields.io/badge/All_projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="All projects"/></a>
</p>

<br/>

<!-- ============================== ABOUT ============================== -->

## 👋 Hi, I'm Shamit

I'm a B.Tech Information Technology student at **Mahatma Gandhi Institute of Technology**, Hyderabad (class of **2027**). I like knowing how a system works under the hood, and I write software as if it were going to production: validated input, real database constraints, and tests that run against a real database rather than mocks.

- 🔭 **Building:** [RepoRescue](https://github.com/shamit64/RepoRescue), a zero-dependency CLI that grades a repository's health
- 🌱 **Learning:** PostgreSQL performance, API design and cloud deployment
- 🧩 **Interested in:** computer networks and cloud systems
- 💼 **Looking for:** software engineering internships (backend / full-stack)

<br/>

<!-- ============================== FLAGSHIP ============================== -->

## 🚀 Featured projects

### 📚 [MangaForEver](https://github.com/shamit64/Manga-Platform-MangaForEver)

**A full-stack platform for discovering, tracking and reviewing manga, manhwa and manhua, backed by a real catalog imported from AniList.**

<a href="https://github.com/shamit64/Manga-Platform-MangaForEver">
  <img src="https://raw.githubusercontent.com/shamit64/Manga-Platform-MangaForEver/main/docs/screenshots/home.png" width="100%" alt="MangaForEver home page"/>
</a>

<p>
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16"/>
  <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React 19"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white" alt="Express 5"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Prisma_7-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma 7"/>
  <img src="https://img.shields.io/badge/tests-92-2EA043?style=flat-square&logo=vitest&logoColor=white" alt="92 tests"/>
</p>

| | |
|---|---|
| 🔎 **Search that forgives typos** | PostgreSQL full-text ranking plus `pg_trgm` trigram matching on GIN indexes, so "berzerk" still finds *Berserk* |
| 🧠 **Explainable recommendations** | Content-based scoring with diversity re-ranking; every pick says why it's there ("Because you read…") |
| ⏱️ **Catalog that keeps itself current** | Scheduled jobs on GitHub Actions pick up new chapters every 15 minutes, with a live updates feed, Web Push and email digests |
| 🛡️ **Production habits** | Zod validation, Helmet, rate limiting, OpenAPI 3.1 docs, database-level integrity constraints and an admin audit log |
| 🧪 **Tested for real** | 92 Vitest + Supertest integration and unit tests running against a real PostgreSQL database |

<details>
<summary><b>How it fits together</b></summary>
<br/>

```mermaid
flowchart LR
  U[Browser] --> W[Next.js 16 web app]
  W --> A[Express 5 API]
  A --> D[(PostgreSQL + pg_trgm)]
  J[GitHub Actions jobs] --> A
  A --> AL[AniList API]
  A --> MD[MangaDex API]
  A --> N[Web Push / email digests]
```

</details>

<br/>

### 🩺 [RepoRescue](https://github.com/shamit64/RepoRescue)

**A local-first health check for your repositories: no network requests, no account, no runtime dependencies.**

<p>
  <img src="https://img.shields.io/badge/Python_3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.10+"/>
  <img src="https://img.shields.io/badge/CLI-4B5563?style=flat-square&logo=gnubash&logoColor=white" alt="CLI"/>
  <img src="https://img.shields.io/badge/runtime_dependencies-0-2EA043?style=flat-square" alt="Zero runtime dependencies"/>
  <img src="https://img.shields.io/badge/works-offline-0EA5E9?style=flat-square" alt="Works offline"/>
</p>

```text
$ reporescue scan .
[docs]  62.5/100
  FAIL  License: No LICENSE file. Others cannot legally reuse the code.
[git]   100/100
[code]  100/100
[deps]  not scored

Overall score: 87.5/100  (grade B)
Top fixes:
   1. [FAIL] License: Add a LICENSE file (choosealicense.com helps pick one)
```

- **14 checks** across docs, git hygiene, code (tests, large files, committed secrets) and dependency pinning
- Every warning or failure comes with a **suggested fix**, ranked so the most useful ones come first
- Reports as **text, JSON, Markdown or a single-file HTML** page with no scripts or external assets
- `--fail-under` turns it into a **CI gate** that fails the build when repo health drops

<br/>

### 🧰 More projects

<table>
<tr>
<td width="50%" valign="top">

#### ☁️ [Cloud File Storage](https://github.com/shamit64/CloudFileStorage)

*A small self-hosted file store with a web dashboard*

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="REST API"/>

- Flask REST endpoints to upload, list, download, search and delete files
- Dashboard with drag-and-drop upload, file sizes and upload times

</td>
<td width="50%" valign="top">

#### 🔌 [Ethernet Switch Simulator](https://github.com/shamit64/Basic-Ethernet-Switch-Simulator)

*How a real switch decides where each frame goes*

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C"/>
<img src="https://img.shields.io/badge/Computer_Networks-0EA5E9?style=flat-square&logo=cisco&logoColor=white" alt="Computer Networks"/>

- Learns which MAC address lives on which of its 4 ports
- Forwards known frames, floods unknown and broadcast ones, drops same-port traffic
- Interactive CLI to send frames and inspect the MAC table

</td>
</tr>
</table>

<!-- Add this back once Job Recruitment Portal has code and a README:

#### 💼 [Job Recruitment Portal](https://github.com/shamit64/Job-Recruitment-Portal)

A portal where recruiters post jobs and candidates apply and track their applications.

- KEY FEATURE
- KEY FEATURE

-->

<br/>

<!-- ============================== TECH ============================== -->

## 🛠️ Tech stack

<table align="center">
  <tr>
    <td align="right"><b>Languages</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,ts,js,c,html,css" alt="Python, TypeScript, JavaScript, C, HTML, CSS"/></td>
  </tr>
  <tr>
    <td align="right"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,express,flask" alt="Node.js, Express, Flask"/></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=nextjs,react,tailwind" alt="Next.js, React, Tailwind CSS"/></td>
  </tr>
  <tr>
    <td align="right"><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,prisma" alt="PostgreSQL, Prisma"/></td>
  </tr>
  <tr>
    <td align="right"><b>Tools &amp; DevOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,linux,vscode" alt="Docker, GitHub Actions, Git, Linux, VS Code"/></td>
  </tr>
</table>

<br/>

<!-- ============================== FOOTER ============================== -->

<p align="center">
  <b>Hiring for an internship, or want to build something together?</b><br/>
  <a href="https://www.linkedin.com/in/shamit-reddy-347438380/">Message me on LinkedIn</a> or <a href="mailto:reddyshamit@gmail.com">send me an email</a>.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" alt=""/>
</p>
