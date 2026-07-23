<!-- PROFILE HEADER -->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,100:111827&height=230&section=header&text=PAWAN%20SEDARA&fontSize=58&fontAlignY=38&fontColor=ffffff&desc=Product%20Engineering%20%E2%80%A2%20Backend%20Systems%20%E2%80%A2%20Privacy%20Infrastructure&descAlignY=59&descSize=17&animation=fadeIn"
    alt="Pawan Sedara"
  />
</p>

<p align="center">
  <a href="https://hexcode.au">
    <img src="https://img.shields.io/badge/Portfolio-hexcode.au-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/HexCodeYT/PlainLink">
    <img src="https://img.shields.io/badge/Featured-PlainLink-111827?style=for-the-badge&logo=github&logoColor=white" alt="PlainLink" />
  </a>
  <a href="https://aussielk.com.au">
    <img src="https://img.shields.io/badge/Production-AussieLK-111827?style=for-the-badge&logo=safari&logoColor=white" alt="AussieLK" />
  </a>
</p>

<br />

## About

I build **privacy-conscious products and reliable backend systems**, from native macOS utilities and Rust command-line tools to production payment infrastructure and self-hosted platforms.

My work sits across product engineering, backend architecture, infrastructure and security. I care less about adding technology for its own sake and more about building systems that are understandable, observable and difficult to break.

```text
Build the product.
Understand the infrastructure.
Own the failure modes.
```

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### [PlainLink](https://github.com/HexCodeYT/PlainLink)

A local-first copied-link cleaner for macOS, built with **Rust** and **Swift/AppKit**.

PlainLink removes tracking parameters directly at the clipboard layer while preserving user control through inspection and restoration workflows.

**Engineering highlights**

* Native macOS menu bar application
* Rust CLI and reusable cleaning engine
* Clipboard monitoring through a user LaunchAgent
* Inspect and restore workflows
* Conservative, fixture-tested rule system
* Reproducible third-party ruleset imports
* Signed and notarized release automation

</td>
<td width="50%" valign="top">

### [AussieLK](https://aussielk.com.au)

A production Australia-to-Sri Lanka sourcing and purchasing platform with a backend designed around payment integrity and operational traceability.

**Engineering highlights**

* Durable Stripe webhook processing
* Idempotent payment workflows
* Reconciliation and incident tracking
* PostgreSQL and Prisma persistence
* Audit logging and administrative tooling
* Consent-aware analytics
* Automated health monitoring
* Production deployment on Vercel

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Privacy Search Infrastructure](https://github.com/HexCodeYT/privacy-search-infra)

A self-hosted public and private search stack built around SearXNG and infrastructure-level privacy controls.

**Architecture**

* Isolated Docker bridge networks
* Caddy reverse proxy
* Unbound recursive DNS
* Firewall-enforced service boundaries
* Automated HTTPS certificates
* Public and private search instances
* Telegram health monitoring

**Live instance:** [search-public.hexcode.au](https://search.hexcode.au)

</td>
<td width="50%" valign="top">

### P.A.T.H.

**Prime Accelerated Throughput Handler**

An experimental segmented prime-analysis engine designed for Apple Silicon using **Metal compute kernels** and **Objective-C++**.

**Research areas**

* GPU-accelerated segmented sieves
* Deterministic compute pipelines
* Parallel Metal dispatch
* Memory and throughput optimisation
* Large-range numerical processing
* Benchmark ranges from 10¹⁰ to 10¹⁵

</td>
</tr>
</table>

## Engineering principles

* **Local-first where practical**
  Keep user data and core functionality on the user’s machine whenever the product allows it.

* **Correctness before cleverness**
  Prefer explicit state transitions, deterministic behaviour and testable boundaries.

* **Design for failure**
  Retries, duplicate events, partial execution and external outages are normal operating conditions.

* **Security through architecture**
  Use isolation, least privilege, auditable state and minimal trust boundaries instead of relying on surface-level controls.

* **Infrastructure should remain understandable**
  Complexity must justify its operational cost.

## Technology

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square\&logo=typescript\&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-111827?style=flat-square\&logo=rust\&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-111827?style=flat-square\&logo=swift\&logoColor=white)
![Objective-C++](https://img.shields.io/badge/Objective--C++-111827?style=flat-square\&logo=apple\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-111827?style=flat-square\&logo=postgresql\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-111827?style=flat-square\&logo=gnubash\&logoColor=white)

### Product and backend

![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square\&logo=nextdotjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-111827?style=flat-square\&logo=nodedotjs\&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-111827?style=flat-square\&logo=prisma\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111827?style=flat-square\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-111827?style=flat-square\&logo=redis\&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-111827?style=flat-square\&logo=stripe\&logoColor=white)

### Systems and infrastructure

![macOS](https://img.shields.io/badge/macOS-111827?style=flat-square\&logo=apple\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-111827?style=flat-square\&logo=linux\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square\&logo=docker\&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-111827?style=flat-square\&logo=caddy\&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-111827?style=flat-square\&logo=wireguard\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-111827?style=flat-square\&logo=githubactions\&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-111827?style=flat-square\&logo=vercel\&logoColor=white)

### Security and reliability

`Idempotency` · `Audit Trails` · `Network Isolation` · `Reconciliation` · `Least Privilege` · `Secrets Management` · `Observability` · `Zero-Trust Design`

## Current focus

```text
01. Shipping PlainLink as a polished macOS product
02. Building reliable production payment systems
03. Designing local-first and privacy-respecting software
04. Deepening Linux, networking and infrastructure knowledge
05. Exploring high-performance compute on Apple Silicon
```

## Selected repositories

* **[PlainLink](https://github.com/HexCodeYT/PlainLink)**
  Local-first macOS URL cleaner built with Rust and Swift/AppKit.

* **[privacy-search-infra](https://github.com/HexCodeYT/privacy-search-infra)**
  Self-hosted privacy search infrastructure with isolated networking and recursive DNS.

* **[HexCodeYT](https://github.com/HexCodeYT/HexCodeYT)**
  Source repository for this GitHub profile.

## Connect

<p>
  <a href="https://hexcode.au">
    <img src="https://img.shields.io/badge/Website-hexcode.au-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Website" />
  </a>
  <a href="https://github.com/HexCodeYT">
    <img src="https://img.shields.io/badge/GitHub-HexCodeYT-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <sub>Based in Melbourne, Australia.</sub>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:050505&height=120&section=footer"
    alt=""
  />
</p>
