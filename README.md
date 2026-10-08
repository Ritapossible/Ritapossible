<h1 align="center">Hi, I'm Rita 👋</h1>

<p align="center">
  <b>Chemical engineer turned software engineer.</b><br>
  I build on frontier chains — usually before the docs exist.
</p>

<p align="center">
  <a href="https://x.com/RitaCryptoTips"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
  <a href="https://medium.com/@ritapossible"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://dev.to/ritapossible"><img src="https://img.shields.io/badge/DEV.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="DEV.to"></a>
  <img src="https://komarev.com/ghpvc/?username=Ritapossible&style=for-the-badge&color=6b46c1" alt="Profile views">
</p>

---

### 🧭 About me

- 🇳🇬 Based in **Nigeria**, building for a global, permissionless internet.
- 🔭 I work at the intersection of **AI agents and smart contracts** — systems where the chain doesn't just hold value, it *verifies things about the real world* before acting.
- ⛓️ Currently shipping on **GenLayer**, **Rialo**, **Aleo**, **BNB Chain**, **Monad**, **Flare**, and **Arc Network**.
- 🎓 **ALX Software Engineering** alum — C, systems, backend, DevOps, the unglamorous foundations.
- ✍️ I write about what I build on [Medium](https://medium.com/@ritapossible) and [DEV](https://dev.to/ritapossible).
- 💼 Open to **software engineering roles** (Python / TypeScript, backend, full-stack, AI agents), plus **open source**, **web3 tooling**, and **DevRel**.
- ⚡ **Fun fact:** I trained as a Chemical Engineer. Turns out process design and distributed systems are the same job — get inputs, transform them safely, and make sure nothing blows up.

---

### 🚀 What I'm building

**Latest work** — shipped Sept–Oct 2026, each with tests and a live deployment or on-chain contract:

| Project | What it does | Stack |
|---|---|---|
| [**Ballast**](https://github.com/Ritapossible/Ballast) | Hold tokenized US stocks through the night without holding the night's risk — overnight decisions settled against what the market actually did. [Live](https://ballast-v1.vercel.app) | Python · CI + nightly pipeline · Vercel |
| [**Egress**](https://github.com/Ritapossible/Egress) | Measures what it costs to *exit* a tokenized stock at your size, crawling every listed instrument every five minutes. [Live](https://egress-v1.vercel.app) | Python · order-book analytics · Vercel |
| [**Stamp**](https://github.com/Ritapossible/Stamp) | A pre-trade gate for tokenized stocks on BSC: issuer, share count, halt state and price checked in fixed code before anything is signed. [Live](https://stamp-iizn.onrender.com) | TypeScript · Vitest · Render |
| [**Docket**](https://github.com/Ritapossible/Docket) | An agent's reputation computed from what a contract actually let it do — every allowed *and* refused action recorded on-chain. | Solidity · TypeScript · viem · Monad |
| [**Clause**](https://github.com/Ritapossible/Clause) | Escrow that pays on the spec you wrote: disputes must cite a clause, and an AI-validator jury rules on that clause alone. | GenLayer · Python · web app |
| [**Remit**](https://github.com/Ritapossible/Remit) | Spending authority for AI agents: arithmetic rules clear in the same transaction, judgment calls go to an AI jury. | GenLayer · Python · pytest |
| [**Credent**](https://github.com/Ritapossible/Credent) | On-chain reputation oracle for agents: collateral priced from reputation, work graded inside consensus. | GenLayer · Python |
| [**Bench**](https://github.com/Ritapossible/Bench) | AI agent marketplace for BNB Chain where agents audition on your real position before you pay. [Live](https://bench-bnb.vercel.app) | TypeScript monorepo · Docker · GenLayer arbiter |
| [**Rowgate**](https://github.com/Ritapossible/Rowgate) | Checks a release branch against a signed API-contract spreadsheet and writes the failing contract test, citing the cell. [Live](https://rowgate.vercel.app) | Python · pytest · IBM Bob |
| [**Constant**](https://github.com/Ritapossible/Constant) | Set-and-forget auto-payments for data, electricity, cable TV and subscriptions in Nigeria, with running-low forecasts. | TypeScript · pnpm monorepo · Android |

**Paying and constraining autonomous agents:**

| Project | What it does |
|---|---|
| [**Scrip**](https://github.com/Ritapossible/Scrip) | Machine-payable FXRP. An agent hits a paid API, gets a `402` priced in USD, signs two offchain messages — and pays holding **no gas token at all**. x402 over Flare, priced at the live FTSO feed. Live on Coston2. |
| [**BONDED**](https://github.com/Ritapossible/Bonded) | A mandate gate for agents trading Binance. Every order that reaches the exchange is reconciled against what BONDED authorised — an order it never approved is detected, attributed, and burns the bond. |

**AI-verified smart contracts** — on [GenLayer](https://genlayer.com), where contracts can reason over real-world data:

| Project | What it does |
|---|---|
| [**Vouch**](https://github.com/Ritapossible/Vouch) | Before an autonomous agent sends money, the chain checks the payee is a real, live, matching entity. |
| [**Recourse**](https://github.com/Ritapossible/Recourse) | Post money behind a public commitment; when the deadline lands, the chain reads the evidence and settles. |
| [**SmartAudit-AI**](https://github.com/Ritapossible/SmartAudit-AI) | AI-powered smart contract auditor built on the GenLayer testnet. |
| [**Mochi-Mind**](https://github.com/Ritapossible/Mochi-Mind-GenLayer-Studio) | GenLayer Studio build — [live demo](https://mochi-mind-gen.vercel.app). |
| [**Dedup Registry**](https://github.com/Ritapossible/GenLayer-Dedup-Registry) | "Have we seen this before?" for free-form text — two deterministic stages run first, so a 10,000-record registry still costs at most 5 LLM calls. |
| [**Mandate Vault**](https://github.com/Ritapossible/GenLayer-Mandate-Vault) | A spending mandate an agent cannot argue with: the code judges the *amount*, the model judges the *purpose*. A cap can't tell a GPU lease from a gift card. |

**Reactive & real-world onchain apps** — on [Rialo](https://rialo.io), the chain that natively speaks HTTPS:

| Project | What it does |
|---|---|
| [**Arkive**](https://github.com/Ritapossible/Arkive) | Crypto inheritance and digital legacy protection. |
| [**RialEstate**](https://github.com/Ritapossible/RialEstate) | Decentralized real estate platform for illiquid, opaque property markets. |
| [**Reactive Transactions**](https://github.com/Ritapossible/rialo-reactive-transactions) | Reference build showing how automated reactive transactions work. |

**Elsewhere:**

| Project | What it does |
|---|---|
| [**Nexusu**](https://github.com/Ritapossible/Nexusu) | AI-powered cooperative banking platform on Arc Network. |
| [**Olex**](https://github.com/Ritapossible/Olex) | Model Context Protocol (MCP) server giving Claude Code, Cursor and other AI assistants direct access to the Aleo privacy blockchain — chain reads, privacy analysis and view-key tools. |
| [**OpenMind-OM1**](https://github.com/Ritapossible/OpenMind-OM1) | Modular AI runtime for robots. |

---

### 🧰 Tech I build with

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & runtime**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Web3 & AI**

![GenLayer](https://img.shields.io/badge/GenLayer-6E56CF?style=flat-square)
![Rialo](https://img.shields.io/badge/Rialo-0EA5E9?style=flat-square)
![Aleo](https://img.shields.io/badge/Aleo-1B1B1B?style=flat-square)
![BNB Chain](https://img.shields.io/badge/BNB%20Chain-F0B90B?style=flat-square&logo=bnbchain&logoColor=black)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents-10A37F?style=flat-square)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 📊 By the numbers

<p align="center">
  <img alt="Public repositories" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FRitapossible&query=%24.public_repos&label=repos&style=for-the-badge&color=6b46c1&logo=github&logoColor=white">
  <img alt="Followers" src="https://img.shields.io/github/followers/Ritapossible?style=for-the-badge&color=6b46c1&logo=github&logoColor=white">
  <img alt="Stars earned" src="https://img.shields.io/github/stars/Ritapossible?affiliations=OWNER&style=for-the-badge&color=6b46c1&logo=github&logoColor=white">
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Ritapossible&theme=dark&hide_border=true&background=00000000&ring=6B46C1&fire=6B46C1&currStreakLabel=6B46C1">
    <img src="https://streak-stats.demolab.com/?user=Ritapossible&hide_border=true&background=00000000&ring=6B46C1&fire=6B46C1&currStreakLabel=6B46C1" alt="Contribution streak">
  </picture>
</p>

---

### 🤝 Let's build something

I'm always up for a good hackathon, an open-source issue, or a conversation about
where AI and blockchains actually meet — beyond the buzzwords.

- 🐦 **X:** [@RitaCryptoTips](https://x.com/RitaCryptoTips)
- ✍️ **Writing:** [Medium](https://medium.com/@ritapossible) · [DEV](https://dev.to/ritapossible)
- 💼 **Open to:** software engineering roles, open-source collaboration, DevRel, and web3 engineering

<p align="center"><i>Build it, ship it, then write about it.</i></p>
