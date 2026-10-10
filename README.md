<div align="center">

# Areesha Khan

**Software Engineer** &nbsp;·&nbsp; Full-stack, applied ML and automation

Final-year BS Software Engineering at COMSATS University Islamabad, Wah Campus.
I build things that run in production, not just in a demo folder — and I write the
tests and the docs that prove they work.

<a href="https://dataseed.169.58.151.43.sslip.io"><img src="https://img.shields.io/badge/Live_demo-DataSeed-6E56CF?style=for-the-badge" alt="DataSeed live demo"></a>
<a href="https://cuischeduler.vercel.app"><img src="https://img.shields.io/badge/Live_demo-CUIScheduler-2EA043?style=for-the-badge" alt="CUIScheduler live demo"></a>

</div>

---

## What I work on

I move between three areas, and the projects below are the evidence for each.

**Applied ML & data engineering** — statistical modelling that has to hold up under
measurement. My main project generates privacy-safe synthetic data using Gaussian
copulas, then grades its own output: train-on-synthetic/test-on-real utility scoring,
Kolmogorov–Smirnov fidelity tests, and a membership-inference attack to check nothing
leaked. If the integrity gate fails, the export refuses to run.

**Full-stack product work** — FastAPI and Laravel on the back, React and Next.js on the
front, Postgres and SQLite underneath. Dockerised, CI on every push, deployed somewhere
you can actually click.

**Mobile** — Flutter and Dart, with Firebase and Stripe wired in for real payment and
auth flows rather than mocked ones.

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [DataSeed](https://github.com/AreeshaKhan25/DataSeed)

Realistic tabular, relational and document data generated on demand — with a
**Trust Report** that proves the output is usable and leak-free.

Gaussian copula per table, foreign keys that resolve, parent totals recomputed
from real children, and nine kinds of inferred business rules. Scores itself on
integrity, fidelity, utility, privacy and detection.

`Python 3.12` `FastAPI` `React 18` `scikit-learn` `Docker`

**317 tests passing · no GPU required**

[Live demo](https://dataseed.169.58.151.43.sslip.io) · [Architecture](https://github.com/AreeshaKhan25/DataSeed/blob/main/docs/01-ARCHITECTURE.md)

</td>
<td width="50%" valign="top">

### [CUIScheduler](https://github.com/AreeshaKhan25/cuischeduler)

Campus resource scheduling for COMSATS Wah that implements OS theory as working
code rather than a simulation.

FCFS, SJF, Round Robin and Priority schedulers; deadlock detection via resource
allocation graph; Banker's algorithm for avoidance; semaphores and mutexes guarding
real booking contention; a bitmap memory map with fragmentation reporting.

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `WebSockets`

[Live demo](https://cuischeduler.vercel.app) · [Developer guide](https://github.com/AreeshaKhan25/cuischeduler/blob/master/docs/DEVELOPER_GUIDE.md)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AeroTAXI](https://github.com/AreeshaKhan25/AeroTAXI)

Airport transfer booking app covering twelve UK airports — quote, vehicle choice,
extras, Stripe payment and confirmation.

Built three times over as a study in portability: once in Flutter, once in Laravel,
once in dependency-free classical PHP with a hand-rolled router and PDO.

`Flutter` `Dart` `Firebase` `Stripe` `Laravel` `PHP 8`

[Flutter app](https://github.com/AreeshaKhan25/AeroTAXI) · [Laravel web](https://github.com/AreeshaKhan25/aerotaxi_WEB) · [Classical PHP](https://github.com/AreeshaKhan25/aerotaxi-php)

</td>
<td width="50%" valign="top">

### [Web Technologies Portfolio](https://github.com/AreeshaKhan25/web-assignments)

Eight responsive pages written in plain HTML5 and hand-written CSS3 — no framework,
no utility classes, no build step.

Included because knowing what the framework does for you matters. Every layout here
is flexbox and grid written by hand.

`HTML5` `CSS3` `GitHub Pages`

[Live site](https://areeshakhan25.github.io/web-assignments/)

</td>
</tr>
</table>

Also here: [**user_manager**](https://github.com/AreeshaKhan25/user_manager) — Flutter CRUD
app with SQLite persistence and live search ·
[**chatbot-python**](https://github.com/AreeshaKhan25/chatbot-python) — rule-based FAQ
chatbot with keyword intent mapping

---

## Tech

**Languages** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)

**Data & ML** &nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Platform** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## How I build

- **Deterministic before clever.** Seeded runs reproduce byte for byte; the AI layer in
  DataSeed is optional and every job falls back to a heuristic when the key is missing.
- **Claims are tests.** If a README says parent totals reconcile, there is a test named
  for it.
- **Ship it somewhere clickable.** Three of the projects above have a live URL.

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AreeshaKhan25&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=github_dark&hide_title=true" height="150" alt="GitHub stats">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AreeshaKhan25&layout=compact&hide_border=true&theme=github_dark&langs_count=8" height="150" alt="Top languages">

</div>
