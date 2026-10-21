# Aryan Pandey

**B.Tech — Artificial Intelligence & Machine Learning** · Backend & AI/ML engineering · Secure, offline-capable systems.

I build working systems rather than tutorial clones — a post-quantum document distribution platform with blind forensic watermarking, a hardened offline-first study app with an encrypted local vault, a habit-tracker PWA, and a zero-dependency static storefront.

<p align="center">
  <a href="https://github.com/ap371-cloud"><img src="https://img.shields.io/badge/GitHub-ap371--cloud-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://github.com/ap371-cloud?tab=repositories"><img src="https://img.shields.io/badge/Repositories-4_Public-2_Private-181717?style=flat&logo=git&logoColor=white" alt="Repositories"/></a>
  <img src="https://img.shields.io/badge/Location-Indore%2C%20India-181717?style=flat&logo=googlemaps&logoColor=white" alt="Location"/>
  <img src="https://img.shields.io/badge/Focus-AI%2FML%20%2B%20Backend%20%2B%20Security-0F7C59?style=flat&logo=shield&logoColor=white" alt="Focus"/>
</p>

## GitHub Stats

<p align="center">
  <a href="https://github.com/ap371-cloud"><img src="https://github-readme-stats.vercel.app/api?username=ap371-cloud&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" alt="Aryan Pandey GitHub stats" height="165"/></a>
  <a href="https://github.com/ap371-cloud?tab=repositories&sort=language"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ap371-cloud&layout=compact&theme=default&hide_border=true" alt="Top languages" height="165"/></a>
</p>

<p align="center">
  <a href="https://github.com/ap371-cloud"><img src="https://github-readme-streak-stats.herokuapp.com?user=ap371-cloud&theme=default&hide_border=true" alt="GitHub streak" height="165"/></a>
  <a href="https://github.com/ap371-cloud"><img src="https://github-readme-activity-graph.vercel.app/graph?username=ap371-cloud&theme=default&hide_border=true&area=true" alt="Contribution activity graph" height="165"/></a>
</p>

## About

- **Currently:** B.Tech in Artificial Intelligence & Machine Learning, building backend and applied-AI systems.
- **Focus areas:** backend APIs, AI/ML application work, applied security (cryptography, access control, forensic attribution).
- **Working style:** end-to-end — schema, service layer, API, UI, tests, CI — and honest about what a prototype can and cannot enforce.
- **Beyond code:** DSA in C++, Linux CLI fluency, and a habit of writing the README before the demo.

## Featured Projects

### [Sentinel](https://github.com/ap371-cloud/sentinel) — Offline PQC document distribution & leak forensics

Encrypted multi-recipient document distribution where **every decryption produces a unique, invisible forensic watermark**, cryptographically bound to that session and signed by the recipient's own key.

| | |
|---|---|
| **Stack** | FastAPI, SQLAlchemy 2, Postgres/SQLite, `pqcrypto` (ML-KEM-768, ML-DSA-65), AES-256-GCM, PyMuPDF, React 18 + TypeScript + Vite |
| **Key ideas** | Blind watermark extraction (keyed correlation), 3-node offline permissioned ledger with RFC-6962 Merkle proofs and quorum certs, tamper-evident hash-chained audit trail, RBAC + ABAC + need-to-know + clearance, zero-trust re-evaluation per request, device binding, single-use nonces, two-person control, break-glass, session-scoped decryption, offline grant leases, policy versioning with digests, explainable access decisions, rule-based risk scoring, forensic evidence reports |
| **Engineering** | 308 pytest cases with no mocks of the properties under test, plus end-to-end demo and API smoke scripts |
| **Live** | [sentinel-ap-b58a.vercel.app](https://sentinel-ap-b58a.vercel.app) |

### [Aarambh — The System](https://github.com/ap371-cloud/aarambh-web) — Gamified JEE study app

Solo-Leveling-style progression for JEE Main & Advanced: XP, levels, ranks, attribute points, daily quests, subject gates and timed practice — with **all progress encrypted locally**.

| | |
|---|---|
| **Stack** | React 19, TypeScript 5.7, Vite 8, Tailwind CSS v4, WebCrypto (AES-256-GCM + PBKDF2-SHA256), React Router 7 |
| **Hardening** | Strict CSP with `require-trusted-types-for 'script'`, 11 hardened security headers with a CI drift check, `.npmrc` with `ignore-scripts=true`, self-hosted fonts, zero third-party runtime scripts |
| **CI** | GitHub Actions — `npm audit --audit-level=high`, typecheck, lint, header drift check, vault round-trip test, build |

### [Dev Habit Tracker](https://github.com/ap371-cloud/dev-habit-tracker) — Offline-first habit PWA

Mobile-first habit tracker: streaks, one-minute tasks, contribution heatmap and progress analytics that work with no network.

| | |
|---|---|
| **Stack** | React 19, TypeScript, Vite 8, PWA |
| **Live** | [dev-habit-tracker.vercel.app](https://dev-habit-tracker.vercel.app) |

### [Jewellery — Fine Jewellery, Indore](https://github.com/ap371-cloud/jewellery) — Zero-dependency storefront

Static marketing and lead-generation site for a jewellery showroom: no build step, no framework, no runtime dependencies, no CDN calls — opens straight from `file://`.

| | |
|---|---|
| **Stack** | HTML5, CSS3, vanilla ES2015, procedurally generated artwork (Pillow + NumPy), PWA manifest |
| **Details** | BIS hallmarking disclosure, DPDP Act 2023 privacy policy, sitemap + robots + JSON-LD local business schema, `prefers-reduced-motion` respected |

## Tech Stack

**Languages** — Python · TypeScript · JavaScript · C++ · SQL · HTML5 · CSS3

**Backend** — FastAPI · SQLAlchemy 2 · Pydantic · Uvicorn · SQLite · PostgreSQL

**Frontend** — React 18/19 · Vite · TypeScript · Tailwind CSS v4 · Zustand · React Router

**Security & Crypto** — `pqcrypto` (ML-KEM-768, ML-DSA-65) · `cryptography` (AES-256-GCM, HKDF, scrypt) · WebCrypto · HMAC / DCT spread-spectrum watermarking · Merkle trees · hash-chained audit logs · RBAC + ABAC · CSP + Trusted Types

**Infrastructure** — GitHub Actions · Vercel · Netlify · GitHub Pages · pytest · Vitest · ESLint · Dependabot

## Currently Exploring

- Robotics AI and ROS 2 simulation
- Computer vision and applied deep learning
- Distributed and offline-first system design
- Stronger problem-solving fundamentals (DSA, C++)

## GitHub Activity

<details>
<summary><b>Contribution graph</b></summary>

![Activity graph](https://github-readme-activity-graph.vercel.app/graph?username=ap371-cloud&theme=default&hide_border=true&area=true&custom_title=Contributions)

</details>

## Contact

- **GitHub** — [@ap371-cloud](https://github.com/ap371-cloud)
- **Email** — `apandey71563@gmail.com`
- **LinkedIn** — <sub>_add your profile URL here_</sub>
- **Website / Portfolio** — <sub>_add your portfolio URL here_</sub>

## Open Source

Issues and pull requests are welcome on the public repositories. For anything security-sensitive, please use the private channel rather than a public issue.
