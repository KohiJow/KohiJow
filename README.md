## Hello! 👋

I'm **João Mateus** — call me **Jow**. ☕
*Kohi* means coffee in Japanese, and I like both coffee and shipping software that works.

**QA Engineer** with 3+ years testing web, mobile and API applications — currently focused on
**API and backend testing**, test automation and CI/CD. ISTQB CTFL certified.

---

### 🧪 What I do

I turn requirements into test scenarios that cover the main flow *and* the edges, automate them,
and run them in pipelines. I report defects with reproducible steps and evidence, and I work
close to developers and product in Agile teams.

| | |
|---|---|
| **API & backend** | REST, HTTP semantics, request/response validation, end-to-end flows |
| **Automation** | Playwright · Cypress · Robot Framework · Appium |
| **Languages** | Python · JavaScript/TypeScript · Java · SQL |
| **CI/CD** | GitHub Actions · pipelines · Git · Docker |
| **Practices** | Agile/Scrum · BDD · shift-left · AI-assisted test generation |

---

### 📊 Live project — a production system I run and test

This isn't a course exercise. It's a real platform with two game server instances sharing one
port, an operations bot, a status API and a backup routine — covered by a **quality suite that
runs by itself every day** and publishes its report.

<p align="center">
  <img src="https://raw.githubusercontent.com/KohiJow/minecraft-infra-qa/main/reports/painel.svg"
       alt="Live platform status, regenerated daily" width="100%">
</p>

**61 automated checks across three layers**, one source of logic:

- **API contract** — Playwright `APIRequestContext` + pytest: field types, cross-field coherence,
  cache headers, error paths, and a check that no personal data leaks through a public port.
- **Infrastructure & regression** — `unittest`, zero dependencies: systemd units, mutual exclusion
  between services, HTTP `Range` support, AST analysis of the bot, backup integrity.
- **Business readable** — Robot Framework over the *same* helpers, no duplicated logic.

Every check exists because **something actually broke**. The root cause of each one is written up
in [`docs/incidents.md`](https://github.com/KohiJow/minecraft-infra-qa/blob/main/docs/incidents.md) —
including a server killed by its watchdog, a test that passed while production failed, and a false
positive in my own security check.

➡️ **[KohiJow/minecraft-infra-qa](https://github.com/KohiJow/minecraft-infra-qa)**

---

### 🎓 Background

**QA Analyst** at Pacto Soluções · **QA Test Technician** at SiDi · **QA Tester** at Stefanini
Full stack volunteer work on an e-commerce platform.
B.Sc. Information Systems in progress · two technical degrees at Senac São Paulo.

---

### 📫 Reach me

<p>
  <a href="https://www.linkedin.com/in/jo%C3%A3o-mateus-firmino-rodrigues-ab8622232/?locale=en_US">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:contatojmfr@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://www.instagram.com/firmino.jm">
    <img src="https://img.shields.io/badge/-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://www.twitch.tv/jowbarista">
    <img src="https://img.shields.io/badge/Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white" alt="Twitch"></a>
</p>

<img src="https://github-readme-stats.vercel.app/api?username=KohiJow&show_icons=true&theme=github_dark&hide_border=true" alt="GitHub stats" height="150">
