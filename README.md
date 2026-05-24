<!--
  Dr. Prashant Sharma — physician-developer building healthcare software in India.
  Pensieve Labs · Pensieve HMS · ABDM · HL7v2 · FHIR · hospital interoperability · clinical informatics.
-->

<p align="center">
  <a href="https://prashant.pensievelabs.org">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=2F81F7&center=true&vCenter=true&width=720&lines=Dr.+Prashant+Sharma+%E2%80%94+physician-developer;Building+Pensieve+%E2%80%94+software+for+hospitals;Healthcare+interoperability+%E2%80%A2+HL7v2+%E2%80%A2+FHIR+%E2%80%A2+ABDM;Hexagonal+TypeScript+%E2%80%A2+schema-first+%E2%80%A2+no+orphans" alt="Headline" />
  </a>
</p>

### 👋 About

I'm a physician building software for hospitals. Founder of **[Pensieve Labs](https://www.pensievelabs.org)** — clinical workflow, hospital management, and healthcare interoperability tooling for the Indian healthcare ecosystem.

My work sits at the intersection of **clinical informatics**, **hospital management systems (HMS)**, and **healthcare interoperability** — the messy plumbing that connects HIS, EMR/EHR, LIS, RIS-PACS, PIS, billing, and custom hospital APIs into a coherent record. I care about software that respects how doctors and nurses actually work, and about open standards: HL7v2, FHIR, ABDM, DICOM, MLLP.

### 🏥 What I'm building — Pensieve

**Pensieve** is a web-based hospital platform for clinical and administrative staff, with an on-prem bridge agent that integrates with whatever the hospital already runs.

- 🧠 **Pensieve kernel** — TypeScript + Fastify backend on Firebase, Zod schema-first, `Result<T, E>` error model, strict hexagonal architecture.
- 💻 **Pensieve shell** — React + Vite frontend for doctors, nurses, lab techs, and hospital management.
- 🌉 **Orophin** — single-binary Node.js on-prem bridge agent. Listens to MLLP / ASTM / CSV / DICOM, ships events over mTLS WebSocket to the kernel. SQLite outbox, offline-tolerant.
- 🔐 **ABDM-ready** — Ayushman Bharat Digital Mission consent + linking flows.

> Stack tradeoffs are documented openly. I'd rather have correct boundaries than clever code.

### 📦 Open source

| Project | What it is |
|---|---|
| 🩺 **[hl7v2-dart](https://github.com/prashantbsr/hl7v2-dart)** | Comprehensive **HL7v2** library for Dart & Flutter — parser, generator, typed segments, **MLLP** transport. Zero dependencies. |
| 🔐 **[abdm-fidelius-dart](https://github.com/prashantbsr/abdm-fidelius-dart)** | Dart implementation of **ABDM Fidelius** encryption — ECDH + HKDF + AES-256-GCM. For Ayushman Bharat Digital Mission integrations. |
| 🌌 **[emlinteractive](https://github.com/prashantbsr/emlinteractive)** | Interactive playground for the EML operator (Odrzywolek 2024). Astrophysics, just for fun. |

### 🛠️ Stack I work in

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![HL7](https://img.shields.io/badge/HL7v2-E10000?style=flat-square)
![FHIR](https://img.shields.io/badge/FHIR-AA0000?style=flat-square)
![DICOM](https://img.shields.io/badge/DICOM-0E76A8?style=flat-square)
![ABDM](https://img.shields.io/badge/ABDM-138808?style=flat-square)

### 🧭 Principles I write code by

- **Hexagonal architecture, always.** Ports and adapters, never the other way around.
- **Schema-first.** Zod at every boundary, single source of truth, codegen for the wire.
- **`Result<T, E>` everywhere.** Errors are values, not exceptions.
- **No stubs, no orphans.** Every line traces to a real user-facing capability.
- **Machine-checked invariants.** If a rule isn't enforced by a tool, it isn't a rule.

### 📊 GitHub

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=prashantbsr&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent" height="160" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prashantbsr&layout=compact&hide_border=true&theme=transparent&langs_count=8" height="160" alt="Top languages" />
</p>

### 🔗 Connect

- 🌐 Company — [pensievelabs.org](https://www.pensievelabs.org)
- ✍️ Blog — [prashant.pensievelabs.org](https://prashant.pensievelabs.org)
- 📍 Manipal, India

<sub>📌 Keywords: hospital management software India · healthcare interoperability · HL7v2 parser · FHIR · ABDM Fidelius · clinical informatics · DICOM · MLLP · LIS RIS-PACS HIS EMR EHR integration · TypeScript Node.js React Fastify · physician developer · clinician engineer.</sub>
