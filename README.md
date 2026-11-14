# Awesome-Employee-Engagement-Pulse-Surveys

# Top Employee Engagement & Pulse Surveys Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Continuous Listening, eNPS Tracking & Manager Action Planning*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Engagement & Pulse Surveys**. These tools help organizations measure how their people feel about work—covering everything from lightweight weekly pulse checks to enterprise-grade listening platforms with validated survey science, driver analysis, and manager action workflows.

**Examples** include Culture Amp, Qualtrics EmployeeXM, Workday Peakon, Lattice, 15Five, Workleap Officevibe, TINYpulse, Glint (Microsoft Viva), and open-source alternatives like Check-Ins and Formbricks (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted pulse surveys, open-source engagement platforms, and community-driven employee feedback—ideal for organizations seeking data sovereignty and avoiding per-employee pricing that compounds across headcount. The open-source landscape is genuinely thin for **dedicated engagement suites**, but functional for **pulse survey infrastructure**: **Check-Ins** provides a complete team engagement platform with pulse surveys and mentor management [citation:7], and **Formbricks** offers a versatile open-source survey platform that explicitly supports employee feedback collection [citation:2].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Culture Amp](https://www.cultureamp.com/)** | **The measurement standard for engagement.** Validated survey instruments, benchmarks from thousands of companies, and driver analysis that tells you which factors actually move engagement in your data. Best for companies of 200+ wanting rigorous measurement and peer benchmarks [citation:1]. | Quote-only (no public pricing) [citation:1] | No free tier; demo via sales |
| **[Qualtrics EmployeeXM](https://www.qualtrics.com/)** | **Enterprise listening at full depth.** Brings survey research rigor to employees: lifecycle surveys (onboarding, exit), always-on listening, text analytics on open-ended responses, and statistical tooling beyond anything else in the category. Correspondingly enterprise in price and implementation weight [citation:1]. | Quote-only [citation:1] | No free tier; demo via sales |
| **[Workday Peakon](https://www.workday.com/)** | **Continuous listening within the Workday ecosystem.** Pioneered the continuous model: short, intelligent pulses whose cadence adapts per employee, with real-time dashboards and attrition-risk signals. Inside Workday, engagement data sits next to the HCM record—exactly where enterprise HR wants it [citation:1]. | Quote-only (no published US price; UK public sector framework shows sliding per-head rates from ~£50/employee/year at 600 headcount down to ~£28.68 at 5,000) [citation:10] | No free tier; demo via sales |
| **[Lattice](https://lattice.com/)** | **Engagement connected to performance.** The engagement module (surveys, pulses, eNPS) shares a system with reviews, goals, and one-on-ones, so a weak engagement driver can become a manager conversation topic the same week. Measurement depth trails Culture Amp; workflow connection is the draw [citation:1]. | From **~$11/person/month** [citation:1] | No free tier; demo via sales |
| **[15Five](https://www.15five.com/)** | **Engagement through manager behavior.** Treats engagement as an output of weekly manager practice: check-ins surface blockers and sentiment continuously, and engagement surveys diagnose what the cadence misses. Pair with its manager-training product and it is a behavior-change program wearing software [citation:1]. | Engage: **$4/user/month**; Perform: $11; Total Platform: $16 [citation:12] | No free tier; trial available |
| **[Workleap Officevibe](https://workleap.com/officevibe/)** | **Lightweight pulses for SMBs.** Simple weekly pulses, anonymous feedback channels, and manager-friendly dashboards. Deliberately light: fast to adopt, easy to outgrow. G2 users report a 9.2/10 ease-of-use rating [citation:1][citation:12]. | **Free tier** available; paid from **~$3.50/person/month** [citation:1][citation:14] | **Free tier**: basic pulse surveys; **14-day trial** for paid features [citation:14] |
| **[TINYpulse](https://www.tinypulse.com/)** | Employee surveying and feedback tool with recognition, coaching, and performance tracking. Uses custom pricing as of November 2026—contact directly for a personalized quote [citation:9]. | Custom pricing (no public rates) [citation:9] | Free tier mentioned in some listings; verify with vendor [citation:9] |
| **[Glint (Microsoft Viva)](https://www.microsoft.com/en-us/microsoft-viva/glint)** | **Engagement inside the Microsoft ecosystem.** Excellent at theme detection, sentiment trending, and driver analysis—at or above Culture Amp on raw NLP quality for open-comment clustering. Requires a qualifying Microsoft 365 license [citation:5][citation:10]. | **$2.00/user/month** (annual, on top of M365 license) [citation:10] | No free tier; requires M365 subscription |

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
