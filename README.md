# Awesome-Employee-Engagement-Pulse-Surveys

## Top Employee Engagement & Pulse Surveys Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Continuous Listening, eNPS Tracking & Manager Action Planning*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Engagement & Pulse Surveys**. These tools help organizations measure how their people feel about work—covering everything from lightweight weekly pulse checks to enterprise-grade listening platforms with validated survey science, driver analysis, and manager action workflows.

**Examples** include Culture Amp, Qualtrics EmployeeXM, Workday Peakon, Lattice, 15Five, Workleap Officevibe, TINYpulse, Glint (Microsoft Viva), and open-source alternatives like Check-Ins and Formbricks (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted pulse surveys, open-source engagement platforms, and community-driven employee feedback—ideal for organizations seeking data sovereignty and avoiding per-employee pricing that compounds across headcount. The open-source landscape is genuinely thin for **dedicated engagement suites**, but functional for **pulse survey infrastructure**: **Check-Ins** provides a complete team engagement platform with pulse surveys and mentor management [citation:7], and **Formbricks** offers a versatile open-source survey platform that explicitly supports employee feedback collection [citation:2].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global employee engagement software market is estimated at approximately **$1.1B–$1.25B in 2025** and growing to **$1.4B in 2026** (with the broader Employee Experience Platform / EXP market valued at ~$3.4B to $4.65B, expanding at ~14–17% CAGR). The sector is **moderately fragmented**—while enterprise HCM platforms and specialized suites (such as Microsoft, Qualtrics, and Workday) capture ~25–30% of total revenue, dozens of point solutions and startups compete on specialized pulse check-ins, recognition, and analytics, driving gradual consolidation toward unified listening and performance suites.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Starting Pricing | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|------------------|--------------------------|
| **[Glint (Microsoft Viva)](https://www.microsoft.com/en-us/microsoft-viva/glint)** | **~$4.0T Market Cap** / ~$346B ARR (Microsoft parent) | **Engagement inside the Microsoft ecosystem.** Excellent at theme detection, sentiment trending, and driver analysis—at or above Culture Amp on raw NLP quality for open-comment clustering. Requires qualifying Microsoft 365 licensing. | **$2.00/user/month** (annual commitment, add-on to M365) | No free tier; 90-day trial capped at 50 licenses via enterprise sales |
| **[Workday Peakon](https://www.workday.com/)** | **~$47B Market Cap** / ~$10.1B ARR (Workday parent) | **Continuous listening within the Workday ecosystem.** Pioneered continuous adaptive pulses with real-time dashboards and attrition-risk signals integrated directly into enterprise HCM records. | **~$49/employee/year** (~$4.08/emp/month, sliding down to ~£14–£28 for large enterprises; min contract ~$20,000/yr) | No free tier; sales-guided demo environment only (no self-serve free trial) |
| **[Qualtrics EmployeeXM](https://www.qualtrics.com/)** | **$12.5B Valuation** (take-private) / ~$1.5B ARR | **Enterprise listening at full depth.** Brings survey research rigor to employees: lifecycle surveys (onboarding, exit), always-on listening, text analytics on open comments, and driver modeling. | **~$25,000/year platform minimum** (custom per-employee quote based on headcount) | No free tier; sales-guided demo sandbox only (self-serve trial only covers basic non-EX surveys) |
| **[Lattice](https://lattice.com/)** | **$3.0B Valuation** (peak venture) / ~$130M ARR | **Engagement connected to performance.** Engagement module (surveys, pulses, eNPS) shares a system with reviews, goals, and one-on-ones, allowing weak engagement drivers to convert directly to manager 1:1 agendas. | **$4/seat/month** for Engagement (or $13/seat/month Foundations bundle; subject to $4,000/yr annual floor) | No free tier; customized demo sandbox only (no self-serve free trial) |
| **[Culture Amp](https://www.cultureamp.com/)** | **$1.5B Valuation** / ~$177M ARR | **The measurement standard for engagement.** Validated survey instruments, benchmark database across thousands of companies, and driver analysis that isolates which levers impact engagement. | **~$5.00–$9.00/employee/month** (billed annually; minimum spend starts at ~$4,500/year) | No free tier; guided demo via sales (no self-serve free trial) |
| **[Workleap Officevibe](https://workleap.com/officevibe/)** | **$125M CAD Growth Round** / ~$100M+ CAD ARR (Workleap/GSoft parent) | **Lightweight pulses for SMBs & mid-market.** Simple continuous pulses, anonymous feedback channels, and manager-friendly dashboards. Fast to adopt with low administrative friction. | **$5.00/user/month** billed annually ($6.25/mo billed monthly; 10-user minimum / $50/mo floor) | 14-day free trial (full feature access, no credit card required; perpetual free tier phased out) |
| **[15Five](https://www.15five.com/)** | **~$94M Total Funding** / ~$95M ARR | **Engagement through manager behavior.** Connects weekly check-ins and blockers with company-wide pulse surveys to diagnose sentiment gaps and pair findings with manager coaching workflows. | **$4.00/user/month** (Engage plan, billed annually; Perform is $11/mo, Total Platform $16/mo) | 14-day free trial available via sales/demo request (no permanent free tier) |
| **[TINYpulse](https://www.tinypulse.com/)** | **$75M Parent Acquisition** (Limeade by WebMD / $9M TINYpulse buyout) / ~$6.5M ARR | **Focused pulse surveying & recognition.** Employee surveying and feedback platform with Cheers for Peers recognition, pulse trending, and manager coaching modules. | **~$5.00/user/month** (entry tier; custom annual contract based on headcount and modules) | No permanent free tier; sales-assisted demo and trial evaluation upon request |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Check-Ins (Object Computing)](https://github.com/objectcomputing/check-ins)** | [![Stars](https://img.shields.io/github/stars/objectcomputing/check-ins?style=social&color=white)](https://github.com/objectcomputing/check-ins/stargazers) | **The most complete open-source team engagement platform.** Apache 2.0 with Commons Clause (check license for commercial use). Built on Micronaut and React, deployable on-premises or Google Cloud Platform. Features: **pulse surveys** to gauge how your team feels about work, **feedback management** for employee growth, **mentor program management** for touch points, employee profiles with skills/certifications, performance reviews, **public Kudos** (posts to Slack), and birthday/anniversary celebrations. Actively used at Object Computing [citation:7]. **Best for teams wanting an integrated engagement and development platform** rather than a standalone survey tool. |
| **[Formbricks](https://github.com/formbricks/formbricks)** | [![Stars](https://img.shields.io/github/stars/formbricks/formbricks?style=social&color=white)](https://github.com/formbricks/formbricks/stargazers) | **The most versatile open-source survey platform for employee feedback.** Open-source experience management suite: **Ask** with link, website, and in-app surveys; **Analyze** with unified feedback store and dashboards; **Act** with automated workflows. Explicitly designed for collecting feedback from **customers, users, and employees**. Self-hostable with APIs and SDKs. The most mature open-source alternative to commercial survey platforms [citation:2]. **Best for organizations wanting a proven, self-hosted survey engine** that can handle both employee and customer feedback. |
| **[employee-pulse-survey-enps-engine](https://github.com/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63)** | [![Stars](https://img.shields.io/github/stars/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63?style=social&color=white)](https://github.com/ejajmahmud/employee-pulse-survey-enps-engine-fastapi-cve-patch-bot-v2026-b63/stargazers) | **Automated pulse surveying platform for weekly sentiment feedback.** MIT licensed. Python 3.12 / FastAPI / LangChain. Core functionality: collecting weekly sentiment feedback, **calculating Employee Net Promoter Scores (eNPS)**, and **identifying burnout trends**. Docker included for container orchestration. Enterprise configuration management and structured diagnostics logging [citation:3][citation:8]. **Best for teams wanting a focused eNPS and burnout-tracking backend** with modern Python stack. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Sum (ETH Belgrade)](https://github.com/pzprado/eth-belgrade)** | [![Stars](https://img.shields.io/github/stars/pzprado/eth-belgrade?style=social&color=white)](https://github.com/pzprado/eth-belgrade/stargazers) | **Decentralized anonymous pulse surveys using confidential computing.** Hackathon project (MVP status—integrations in progress). Leverages iExec for confidential data processing, Civic for authentication, Chainlink Functions, and OriginTrail for aggregated reports. Next.js/Tailwind frontend. **Employee UI** submits encrypted survey responses (11 rating questions, 1 text); **Admin UI** views anonymized reports. **Best for exploring privacy-preserving survey architectures**—not production-ready [citation:13]. |

**Frameworks for building custom systems**: Choose **Check-Ins** for an integrated engagement platform with pulse surveys and mentor management , **Formbricks** for a mature survey engine that handles both employee and customer feedback , or **employee-pulse-survey-enps-engine** for a focused eNPS and burnout-tracking backend —all without per-employee pricing that scales with headcount.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Employee engagement platforms handle sensitive sentiment data and anonymous feedback; enforce strict anonymity guarantees, access controls, and compliance with applicable employment and data protection regulations. **A breach of survey anonymity destroys trust permanently.**
- **Pricing varies dramatically and is often opaque.** **Culture Amp, Qualtrics, and Workday Peakon are quote-only** [citation:1]. **Glint requires a Microsoft 365 license** at $2.00/user/month on top of the base subscription [citation:10]. **Workday Peakon's UK public sector framework** shows a sliding per-head rate (£50.10 at 600 headcount down to £28.68 at 5,000) plus deployment packages of £12,000–£55,000—but no US list price exists [citation:10]. **15Five publishes transparent rates** ($4–$16/user/month) [citation:12], and **Officevibe offers a genuine free tier** with paid plans from ~$3.50/person/month [citation:1][citation:14]. **Open-source engagement suites are thin**: Check-Ins is the most complete but carries a Commons Clause restriction , Formbricks is a survey engine rather than a dedicated engagement platform , and the eNPS engine is a backend component . **Validate anonymity guarantees, action-planning workflows, and total cost against your actual headcount** before committing.

---

**Made for HR leaders, people operations teams, and developers building employee listening infrastructure.**  
Let's make employee engagement and pulse surveys more open, anonymous, and action-oriented.
