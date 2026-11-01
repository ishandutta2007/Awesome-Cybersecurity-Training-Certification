# Awesome-Cybersecurity-Training-Certification

# Awesome-Cybersecurity-Training-Certification

**Top Cybersecurity Training Certification (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Hands-On Labs, Certification Prep, CTF Platforms & Self-Hosted Training Infrastructure*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cybersecurity Training & Certification**. These tools enable individuals and organizations to build practical security skills through hands-on labs, capture-the-flag exercises, and structured learning paths—from fully managed platforms with certification-aligned curricula to self-hosted CTF infrastructure that gives training teams complete control over their environments and content.



**Examples** include Hack The Box, TryHackMe, OffSec, SANS Institute, Cybrary, INE Security, Pluralsight, Coursera, CompTIA Security+, and CrowdStrike University (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted CTF platforms, vulnerable lab environments, and open training infrastructure. **Critical note**: The open-source landscape is anchored by **CTFd**—the most widely deployed CTF platform, used by DEF CON, Google CTF, and thousands of university competitions . **OWASP Vulnerable Web Applications Directory** catalogs dozens of intentionally vulnerable apps for practice . No open-source project matches Hack The Box's production-grade lab infrastructure or OffSec's certification rigor, but for hands-on training and CTF hosting, the open-source options are battle-tested.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global cybersecurity training and certification market is valued at approximately **$7 billion to $18 billion** (with broad workforce development and security awareness segments projected to exceed $25 billion by 2030 at a ~12–16% CAGR). The sector is **moderately fragmented**: while a handful of dominant leaders and accreditation giants (such as SANS Institute, CompTIA, and enterprise tech vendors like CrowdStrike) capture large portions of corporate and compliance budgets, the market remains contested by high-growth hands-on lab platforms (Hack The Box, TryHackMe, OffSec) and continuous niche innovators addressing fast-shifting cyber threats.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Pricing | Free Tier / Trial Limits | Description & Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[CrowdStrike University](https://www.crowdstrike.com/)** | **~$250B+ valuation** (~$4.8B FY2026 ARR / revenue) | Starts at **$500 per training credit**; exam vouchers at **$250/exam**; annual LMS subscriptions quoted per seat/team | **No free tier for non-customers**; free **Fast Track (100-level)** e-learning modules & product update videos included strictly for active Falcon enterprise subscribers | Product-specific education for the Falcon endpoint security platform. Best for enterprise security teams and SOC analysts operating CrowdStrike Falcon. |
| **[Pluralsight](https://www.pluralsight.com/)** | **~$3.5B private buyout** (recapitalized / $450M+ ARR) | Core Tech starts at **$45/month** or **$449/year**; Complete starts at **$29–$55/month** or **$299/year** billed annually | **10-day free trial** with full course library access (limited to 200 minutes of video streaming; excludes hands-on interactive labs and sandboxes; requires credit card) | Enterprise technology skill-building and cert prep across security, cloud, and IT ops. Best for cross-functional engineering and IT teams. |
| **[Coursera](https://www.coursera.org/)** | **~$1.2B market cap** (~$757M FY2025 revenue) | Coursera Plus at **$59/month** or **$399/year**; individual certificates start at **$49/month** | **Free Audit mode** available indefinitely on most non-degree courses (video lectures and readings only; excludes graded assignments, certificates, and interactive labs); **7-day free trial** for Coursera Plus | Academic and foundational certification paths (e.g., Google Cybersecurity Certificate). Best for beginners wanting structured university/industry lectures. |
| **[SANS Institute](https://www.sans.org/)** | **~$500M–$1B estimated revenue** (Escal Institute) | Single course starts at **$8,900** (SEC504) or **€8,230** (SEC560); GIAC exam attempt adds **$999 / €905**; SANS.edu graduate cert at **$22,800** | **No free trial for full OnDemand courses**; free community tier includes **100+ archived webcasts, security policy templates, cheat sheets, and course preview video demos** with a free SANS account | Premier, intensive cybersecurity training and gold-standard GIAC certifications. Best for enterprise-sponsored practitioners and senior defense/offensive personnel. |
| **[CompTIA Security+](https://www.comptia.org/)** | **~$200M–$280M+ estimated revenue** | Exam voucher starts at **$373.15** ($439 retail); Voucher + Retake Assurance at **$492.15**; CertMaster Learn course starts at **$561** | **No free tier for certification exams**; **60-day evaluation trial** offered selectively for CertMaster Practice/Learn through institutional or partner demo keys (restricted sample lesson subset) | Baseline vendor-neutral cybersecurity certification for DoD 8570/8140 compliance and foundational HR screening. Best for IT professionals starting in info security. |
| **[Hack The Box](https://www.hackthebox.com/)** | **~$250M–$500M valuation** ($55M Series B; ~$30M–$50M ARR) | VIP+ at **$25/month** or **$223/year**; HTB PRO at **$49/month** or **$490/year**; Academy Silver at **$550/year**; Student at **$10/month** | **Free for life tier** with **20 active Machines, 80+ active Challenges**, and a **one-time 2-hour Pwnbox trial** | Gamified offensive and defensive hands-on hacking labs and structured Academy paths. Best for intermediate-to-advanced penetration testers and CTF players. |
| **[OffSec](https://www.offsec.com/)** | **~$50M–$100M+ estimated revenue** (Acquired by Leeds Equity) | Course + Cert Bundle starts at **$1,749** (90-day lab access + 1 exam); CyberCore at **$899**; Learn Fundamentals at **$799/year**; Learn One at **$2,749/year** | **Free tier via OffSec Community Portal** with **3 hours/day access to Proving Grounds Play** (community standalone machines), plus full free access to PEN-103 (Kali Linux Revealed) and Metasploit Unleashed | Industry-standard rigorous hands-on certifications (OSCP, OSWE, OSEP). Best for infosec professionals pursuing recognized practical offensive credentials. |
| **[TryHackMe](https://tryhackme.com/)** | **~$30M–$40M+ ARR** (Bootstrapped) | Premium starts at **$16.99/month** or **$10.50/month ($126/year)** billed annually; MAX plan starts at **$29.11/month** or **$17.99/month** billed annually | **Free for life tier** with access to introductory rooms, foundational learning paths, OpenVPN connection, and **1 hour per day of browser AttackBox** | Hands-on, step-by-step guided security challenges and beginner-to-intermediate learning paths. Best for beginners and aspiring security analysts/pentesters. |
| **[Cybrary](https://www.cybrary.it/)** | **~$30M–$32M ARR** ($52.2M VC funding raised) | Insider Pro starts at **$24.58/month billed annually** ($295/year) or **$39/month** month-to-month | **Free for life tier** with access to baseline introductory skill paths and a daily limit of **10 learning activities/day**; **7-day free trial** for Insider Pro full catalog access | Career-aligned cybersecurity paths, prep for industry certs, and skill assessments. Best for self-paced learners wanting affordable structured guidance. |
| **[INE Security](https://security.ine.com/)** | **~$20M–$50M estimated revenue** (West Street / Goldman Sachs PE) | Fundamentals starts at **$349/year**; Premium starts at **$39/month** ($468/year) or **$799/year** (includes eJPT/eCPPT courseware & exam vouchers) | **No ongoing free tier for full catalog**; historically offered a restricted 'Starter Pass'; currently offers limited sample lessons and occasional **7-day promotional evaluation trials** (video-only previews, no advanced labs) | Practical hands-on training with included certifications (eJPT, eCPPT, eWPT). Best for learners seeking affordable practical offensive certifications. |

## Open-Source GitHub Projects



- **[CTFd](https://github.com/CTFd/CTFd)**

  **The most widely used open-source CTF platform** (Apache-2.0) — **the standard for hosting capture-the-flag competitions**, used by DEF CON, Google CTF, and thousands of university and corporate events . **Features**: **Challenge management** with categories and dynamic scoring; **team and individual modes**; **scoreboard** with real-time updates; **plugin architecture** for custom challenge types; **Docker deployment**; **themes** for branding; **API** for automation . **Tech stack**: Python (Flask), SQLite/MySQL/PostgreSQL. **Deploy**: Self-hosted (Docker, manual) or CTFd Cloud. **Trade-off**: **Competition-focused**—not a structured learning path platform; no built-in guided tutorials or progress tracking. **Best for**: organizations hosting internal CTFs, university competitions, or security awareness events—the de facto standard for CTF infrastructure.



- **[OWASP Vulnerable Web Applications Directory](https://github.com/OWASP/www-project-vulnerable-web-applications-directory)**

  **Curated directory of intentionally vulnerable applications** (license per project) — **the most comprehensive catalog of practice targets** for hands-on security training . **Features**: **Dozens of vulnerable apps** across categories: web applications, APIs, mobile, cloud, and infrastructure; **includes classics** like DVWA (Damn Vulnerable Web Application), OWASP Juice Shop, WebGoat, and Hackazon; **organized by difficulty and technology stack**; **actively maintained** by OWASP community . **Tech stack**: Varies by application. **Deploy**: Each app self-hosted (Docker, manual). **Trade-off**: **Directory, not a platform**—no hosting, no scoring, no progress tracking. You deploy and manage each app individually. **Best for**: learners and trainers wanting a curated list of practice targets—the starting point for building a self-hosted lab environment.



- **[DVWA (Damn Vulnerable Web Application)](https://github.com/digininja/DVWA)**

  **PHP/MySQL vulnerable web app for security practice** (GPL-2.0) — **the classic entry-level practice target**, used in countless university courses and training programs . **Features**: **Deliberately vulnerable** to SQL injection, XSS, CSRF, file inclusion, and more; **adjustable difficulty levels** (low, medium, high, impossible) to progress from basic to secure coding; **guided challenges** with hints; **Docker deployment** . **Tech stack**: PHP, MySQL. **Deploy**: Self-hosted (Docker, XAMPP). **Trade-off**: **Single application**—not a platform; no scoring or progress tracking beyond difficulty levels. **Best for**: beginners learning web application security fundamentals—the canonical starting lab.



- **[OWASP Juice Shop](https://github.com/juice-shop/juice-shop)**

  **Modern vulnerable web application** (MIT) — **the most comprehensive single-app practice target**, with 100+ challenges covering OWASP Top 10 and beyond . **Features**: **100+ challenges** across injection, broken auth, sensitive data exposure, XXE, broken access control, and more; **progress tracking** with score board; **hints system**; **Docker deployment**; **actively maintained** by OWASP . **Tech stack**: Node.js, Express, SQLite. **Deploy**: Self-hosted (Docker, npm). **Trade-off**: **Single application**—web-focused; not infrastructure or network security. **Best for**: developers and security learners wanting a modern, well-maintained practice target with built-in progress tracking.



### Additional Strong Open-Source Options



- **WebGoat (OWASP)** — Deliberately insecure Java web application for security training (GPL-2.0). **Note**: Single application; Java-focused. **Best for**: Java developers learning secure coding.

- **Metasploitable** — Intentionally vulnerable Linux VM for penetration testing practice (BSD-style). **Note**: VM-based; network and infrastructure focused. **Best for**: learning exploitation and post-exploitation techniques.

- **SecDevLabs** — OWASP project with vulnerable apps and guided tutorials (license per repo). **Note**: Tutorial-focused; smaller catalog than Juice Shop. **Best for**: developers wanting structured secure coding lessons.



**Frameworks for building custom systems**: Combine **CTFd** for competition hosting with **OWASP Juice Shop** and **DVWA** as practice targets, and **OWASP Vulnerable Web Applications Directory** as your catalog—creating a complete self-hosted training environment. **None of these match Hack The Box's production lab infrastructure or OffSec's certification rigor**, but for hands-on practice and CTF events, the open-source options are battle-tested.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cybersecurity training platforms handling learner data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.

- **The "hands-on labs" vs. "guided learning paths" vs. "certification prep" vs. "CTF platform" vs. "vulnerable app" distinction is critical.** **Hack The Box and TryHackMe** are **hands-on labs**—they provide realistic environments and challenges . **OffSec and SANS** are **certification-focused**—they prepare for specific credentials with rigorous exams . **Cybrary, Pluralsight, and Coursera** are **video-course platforms**—structured learning with less hands-on depth . **CTFd** is a **CTF platform**—competition hosting, not structured learning . **DVWA and Juice Shop** are **vulnerable apps**—practice targets, not platforms . **Choose based on whether you need realistic labs, certifications, structured courses, or CTF hosting.**

- **Hack The Box Labs and Academy are separate subscriptions.** Labs (VIP+/PRO) covers machines and Pro Labs; Academy covers structured courses. **Budget for both if you need hands-on practice and guided learning.**

- **OffSec's Learn One is $2,749/year** with one course and two exam attempts. **The Course + Cert Bundle at $1,749/once** offers 90 days and one exam attempt—**choose based on your timeline and risk tolerance.**

- **SANS pricing is premium.** SEC504 is **$8,900 + $999 certification**; SEC560 is **€8,230 + €905**. **SANS.edu graduate certificate totals $22,800.** **For employer-sponsored training, this is the gold standard; for self-funded learners, alternatives are more accessible.**

- **CompTIA Security+ voucher is $373.15** (discounted from $439); **Voucher + Retake Assurance is $492.15** with a free retake if needed . **The retake assurance is worth considering for first-time test takers.**

- **CTFd is the de facto standard for CTF hosting.** Used by DEF CON and Google CTF, with Docker deployment and plugin architecture . **The trade-off**: competition-focused, not a learning path platform.

- **OWASP Juice Shop is the best single practice target**—100+ challenges with progress tracking, actively maintained, Docker-deployable . **Pair it with DVWA for classic web vulnerabilities and CTFd for competition hosting.**

- **Pricing opacity varies.** Hack The Box, TryHackMe, OffSec, SANS, Cybrary, INE, Pluralsight, Coursera, CompTIA, and CrowdStrike University publish tiered or exam pricing. TryHackMe Business requires sales contact (min 5 licenses, 12 months). Cybrary Teams/Enterprise requires sales contact. CrowdStrike University requires quote. **Validate with direct vendor conversations against your team size and training goals.**

- Self-hosted open-source solutions require proper infrastructure (Docker for CTFd, Juice Shop, DVWA), network isolation for vulnerable apps, and ongoing maintenance. **Vulnerable applications are intentionally insecure**—ensure your deployment is isolated from production networks and meets your organization's security standards before deploying.



---



**Made for security trainers, CTF organizers, and organizations building transparent cybersecurity training solutions.**

Let's make Cybersecurity Training & Certification more open, data-driven, and hands-on.
