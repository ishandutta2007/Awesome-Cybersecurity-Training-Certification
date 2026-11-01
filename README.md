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

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Hack The Box](https://www.hackthebox.com/)**

  **Hands-on cybersecurity training platform** with labs, Academy, and certifications. **Pricing**: **Free plan** with **20 active Machines, 80+ active Challenges, 2-hour Pwnbox trial**; **VIP+ $25/month or $223/year** (all retired Machines, unlimited Pwnbox, CPE credits); **HTB PRO $49/month or $490/year** (10 flagship Pro Labs, full VIP+ access); **Academy Silver Annual $550/year**, **Gold $1,400/year**, **Platinum $2,000/year**; **Student $10/month** . **Free tier**: Yes, 20 active machines. **Best for**: practitioners wanting realistic offensive labs and structured Academy paths—**trade-off**: Labs and Academy are separate subscriptions.



- **[TryHackMe](https://tryhackme.com/)**

  **Gamified cybersecurity training** with guided rooms and learning paths. **Pricing**: **Free rooms** available; **Premium** subscription (monthly/annual); **EDU license $30/license/month** for educational institutions; **Business** requires sales contact (minimum 5 licenses, 12-month term, bulk discounts from 50) . **Free tier**: Yes, limited free rooms. **Best for**: beginners wanting guided, gamified learning paths—**trade-off**: business pricing opaque; minimum commitment.



- **[OffSec](https://www.offsec.com/)**

  **Hands-on training and certification** (OSCP, OSWE, etc.). **Pricing**: **Learn Fundamentals $799/year** (fundamental content); **Learn One $2,749/year** (one 200/300-level course, labs, two exam attempts); **Course + Cert Bundle $1,749/once** (90 days access, one exam attempt); **CyberCore $899/once** (one 100-level course, two exam attempts); **OSCP+ Standalone Exam $1,699/once**; **Annual Membership $299/yr** (quarterly CPE-eligible labs) . **Free tier**: None. **Best for**: professionals pursuing industry-recognized offensive certifications—**trade-off**: premium pricing; exam attempts limited.



- **[SANS Institute](https://www.sans.org/)**

  **Intensive cybersecurity training and GIAC certification**. **Pricing**: **SEC560 Enterprise Penetration Testing €8,230** (course) + **€905** (certification); **SEC504 Hacker Tools $8,900** (course) + **$999** (certification); **SANS.edu Graduate Certificate total program $22,800** . **Free tier**: None. **Best for**: enterprises and professionals wanting deep, instructor-led training with GIAC credentials—**trade-off**: premium pricing; course + certification sold separately.



- **[Cybrary](https://www.cybrary.it/)**

  **Cybersecurity training platform** with career paths and cert prep. **Pricing**: **Free Access** (limited career/skill paths, 10 activities/day); **Insider Pro $24.58/month billed annually** (full catalog, unlimited activities); **Teams** and **Enterprise** require sales contact . **Free tier**: Yes, limited catalog and 10 activities/day. **Best for**: individuals wanting affordable access to broad cybersecurity content—**trade-off**: free tier severely limited; Teams/Enterprise pricing opaque.



- **[INE Security](https://security.ine.com/)**

  **Cybersecurity training with certifications** (eJPT, eCPPT). **Pricing**: **Premium $39/month** includes PTP course and eCPPT exam; plan for **6–12 months of subscription** to complete PTP . **Free tier**: Not specified. **Best for**: learners wanting affordable access to offensive certifications—**trade-off**: subscription duration determines total cost.



- **[Pluralsight](https://www.pluralsight.com/)**

  **Technology skills platform** with security content. **Pricing**: **Security+ plan** and **Complete plan**; free trial available (excludes labs/sandboxes); promotional 50% discounts periodically . **Free tier**: Trial only. **Best for**: teams wanting broad tech training including security—**trade-off**: security is one domain; not specialized CTF/lab focus.



- **[Coursera](https://www.coursera.org/)**

  **Online learning platform** with cybersecurity courses and certificates. **Pricing**: **Foundations of Cybersecurity** (Google) available via **$59/month or $399/year** Coursera Plus subscription . **Free tier**: Audit access to some courses. **Best for**: beginners wanting structured video courses with certificates—**trade-off**: limited hands-on labs compared to CTF platforms.



- **[CompTIA Security+](https://www.comptia.org/)**

  **Entry-level cybersecurity certification**. **Pricing**: **Official voucher $373.15** (discounted from $439); **Voucher + Retake Assurance $492.15** (includes free retake if needed) . **Free tier**: N/A (certification exam). **Best for**: professionals needing the baseline certification for DoD 8570 compliance and HR filters—**trade-off**: exam fee only; training not included.



- **[CrowdStrike University](https://www.crowdstrike.com/)**

  **Product-specific training** for Falcon platform. **Pricing**: **12-month annual LMS subscription** via CDW; price requires quote request—no public pricing . **Free tier**: None. **Best for**: CrowdStrike customers needing Falcon platform training—**trade-off**: product-specific; not general cybersecurity education.



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
