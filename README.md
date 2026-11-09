<!-- ===================== HEADER ===================== --> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e3a8a,100:2563eb&height=210&section=header&text=Shamit%20Reddy&fontSize=58&fontColor=ffffff&fontAlignY=36&desc=Backend%20%26%20Full-Stack%20Developer&descSize=20&descAlignY=58&animation=fadeIn" width="100%" alt="Shamit Reddy — Backend & Full-Stack Developer"/> </p> <p align="center"> <a href="https://github.com/shamit64"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=2563EB&center=true&vCenter=true&width=560&lines=Python+%C2%B7+TypeScript+%C2%B7+PostgreSQL;I+build+backends+and+test+them+properly;Currently+building+RepoRescue;Open+to+SDE+internships" alt="Typing intro"/> </a> </p> <p align="center"> <a href="https://www.linkedin.com/in/shamit-reddy-347438380/"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn"/></a> <a href="mailto:[EMAIL]"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> <a href="https://github.com/shamit64?tab=repositories"><img src="https://img.shields.io/badge/Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Projects"/></a>  </p> <p align="center"> 🎓 B.Tech Information Technology @ <b>[COLLEGE]</b> · Class of <b>[YEAR]</b> &nbsp;|&nbsp; 📍 Hyderabad, India </p> <br/> <!-- ===================== ABOUT ===================== -->
👋 About me

I'm an IT student who likes understanding how systems work underneath, and I build software that's tested as if it were going to production. My biggest project, MangaForEver, is a full-stack platform with a Next.js front end, an Express + PostgreSQL API, scheduled background jobs and 92 integration tests against a real database. On the systems side, I've built everything from a switch simulator that learns where to send each frame to a tool that grades a codebase's health without a single byte leaving your machine.

python
shamit = {
    "focus":      ["Backend", "Full-Stack", "Developer Tools"],
    "building":   "RepoRescue: a zero-dependency repo health CLI",
    "learning":   ["PostgreSQL performance", "API design", "Cloud deployment"],
    "interests":  ["Computer networks", "Cloud systems"],
    "looking_for": "Software engineering internships (backend / full-stack)",
}
<br/> <!-- ===================== TECH ===================== -->
🛠️ Tech stack
<table align="center"> <tr> <td align="right"><b>Languages</b></td> <td><img src="https://skillicons.dev/icons?i=py,ts,js,c,html,css" alt="Python, TypeScript, JavaScript, C, HTML, CSS"/></td> </tr> <tr> <td align="right"><b>Backend</b></td> <td><img src="https://skillicons.dev/icons?i=nodejs,express,flask" alt="Node.js, Express, Flask"/></td> </tr> <tr> <td align="right"><b>Frontend</b></td> <td><img src="https://skillicons.dev/icons?i=nextjs,react,tailwind" alt="Next.js, React, Tailwind CSS"/></td> </tr> <tr> <td align="right"><b>Data</b></td> <td><img src="https://skillicons.dev/icons?i=postgres,prisma" alt="PostgreSQL, Prisma"/></td> </tr> <tr> <td align="right"><b>Tools &amp; DevOps</b></td> <td><img src="https://skillicons.dev/icons?i=docker,githubactions,git,linux,vscode" alt="Docker, GitHub Actions, Git, Linux, VS Code"/></td> </tr> </table> <br/> <!-- ===================== FLAGSHIP PROJECT ===================== -->
🚀 Featured projects
📚 MangaForEver — full-stack discovery & tracking platform
<a href="https://github.com/shamit64/Manga-Platform"> <img src="https://raw.githubusercontent.com/shamit64/Manga-Platform/main/docs/screenshots/home.png" width="100%" alt="MangaForEver home page"/> </a> <p> <img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/> <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/> <img src="https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma"/> <img src="https://img.shields.io/badge/tests-92_passing-2EA043?style=flat-square&logo=vitest&logoColor=white" alt="92 tests"/> </p>

A platform for discovering, tracking and reviewing manga, manhwa and manhua, backed by a real AniList-imported catalog.

🔎 Search that forgives typos: PostgreSQL full-text + pg_trgm trigram matching ("berzerk" still finds Berserk)
🧠 Explainable recommendations that say why each pick is there
⏱️ Background jobs on GitHub Actions sync new chapters every 15 minutes, with Web Push and email digests
🛡️ Production habits: Zod validation, rate limiting, OpenAPI docs and 92 Vitest + Supertest integration tests against real PostgreSQL
<br/> <table> <tr> <td width="50%" valign="top">
🩺 RepoRescue

Local-first repository health checker

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/CLI-4B5563?style=flat-square&logo=gnubash&logoColor=white" alt="CLI"/> <img src="https://img.shields.io/badge/zero-dependencies-2EA043?style=flat-square" alt="Zero dependencies"/>

text
$ reporescue scan .
[docs]  62.5/100
  FAIL  License: No LICENSE file.
[git]   100/100
[code]  100/100
Overall score: 87.5/100  (grade B)
14 checks: docs, git hygiene, tests, secrets, dependency pinning
Text, JSON, Markdown or self-contained HTML reports
--fail-under gate for CI pipelines
</td> <td width="50%" valign="top">
☁️ Cloud File Storage

A small self-hosted Google Drive

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/> <img src="https://img.shields.io/badge/REST_API-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="REST API"/>

Upload, find and retrieve files from one central store.

Flask REST endpoints for upload, list, download, search and delete
Dashboard with drag-and-drop upload and file details
<br/>
🔌 Ethernet Switch Simulator

How a real switch decides where each frame goes

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C"/> <img src="https://img.shields.io/badge/Computer_Networks-0EA5E9?style=flat-square&logo=cisco&logoColor=white" alt="Computer Networks"/>

MAC learning with a live MAC-to-port table
Forwards, floods unknown/broadcast frames, filters same-port traffic
</td> </tr> </table> <!-- Add this back once Job Recruitment Portal has code and a README: ### 💼 [Job Recruitment Portal](https://github.com/shamit64/Job-Recruitment-Portal) A portal where recruiters post jobs and candidates apply and track their applications. - KEY FEATURE - KEY FEATURE --> <br/> <!-- ===================== FOOTER ===================== --> <p align="center"> <b>Hiring for an internship, or want to build something together?</b><br/> <a href="https://www.linkedin.com/in/shamit-reddy-347438380/">Let's connect on LinkedIn →</a> </p> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,50:1e3a8a,100:0f172a&height=110&section=footer" width="100%" alt=""/> </p>
