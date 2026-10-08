## Hello! 👋

I'm João Mateus, but you can call me **Jow**. ☕
*Kohi* means coffee in Japanese, and I'm into both.

**QA Engineer** with 3+ years testing web, mobile and API applications. These days my focus is
API and backend testing, automation and CI/CD. ISTQB CTFL certified.

### What I work with

| | |
|---|---|
| **API & backend** | REST, HTTP methods and status codes, request/response validation, E2E flows |
| **Automation** | Playwright, Cypress, Robot Framework, Appium |
| **Languages** | Python, JavaScript/TypeScript, Java, SQL |
| **CI/CD** | GitHub Actions, pipelines, Git, Docker |
| **Practices** | Agile/Scrum, BDD, shift-left, AI-assisted test generation |

### Current project

A platform I run and test: two game server instances sharing one port, an operations bot,
a status API and a backup routine. It has a quality suite that runs on its own every day
and publishes the report.

<p align="center">
  <img src="https://raw.githubusercontent.com/KohiJow/minecraft-infra-qa/main/reports/painel.svg"
       alt="Platform status, regenerated daily" width="100%">
</p>

61 automated checks in three layers, sharing one set of helpers:

- **API contract** with Playwright and pytest: field types, coherence between fields, cache
  headers, error paths, and a check that nothing personal leaks through a public port.
- **Infrastructure and regression** with `unittest` and no dependencies: systemd units, mutual
  exclusion between services, HTTP `Range` support, static analysis of the bot, backup integrity.
- **Readable scenarios** in Robot Framework, on top of the same library.

Every check came from something that actually broke. I wrote up the root cause of each one in
[docs/incidents.md](https://github.com/KohiJow/minecraft-infra-qa/blob/main/docs/incidents.md):
a server killed by its own watchdog, a test that passed while production failed, and a false
positive in my own security check.

**[KohiJow/minecraft-infra-qa](https://github.com/KohiJow/minecraft-infra-qa)**

### Where I've been

QA Analyst at Pacto Soluções, QA Test Technician at SiDi, QA Tester at Stefanini, plus volunteer
full stack work on an e-commerce platform. B.Sc. in Information Systems in progress, and two
technical degrees at Senac São Paulo.

### Talk to me

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
