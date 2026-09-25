# ISC2 Certified in Cybersecurity (CC) — Study Checklist
**Stephen · Started Sep 25, 2026 · Exam outline: 2026 revision (effective Sep 1, 2026)**

> The "ICC" decoded: ISC2's **Certified in Cybersecurity (CC)** — the entry-level cert with no experience required. Sits nicely at the start of your roadmap: CC → Security+ → GCFA/CHFI → CGRC/CISA.

## Exam logistics (know before you start)
- **Format:** 100–125 questions, multiple choice + advanced item types
- **Testing style:** CAT — Computerized Adaptive Testing (questions adapt to your performance; you can't go back and change answers)
- **Time:** 2 hours · **Passing score:** 700 out of 1000
- **Where:** Pearson VUE testing centers worldwide
- **Cost:** $199 exam fee · $50/year AMF (Annual Maintenance Fee) after you pass
- **Prerequisites:** none. Basic IT knowledge recommended, no work experience required
- ⚠️ The free "One Million Certified in Cybersecurity" enrollment ended **May 20, 2026** — the exam is paid now. Don't chase blog posts promising free vouchers; they're stale.

---

## 0 · Getting started
- [ ] Read the official 2026 CC exam outline (isc2.org/certifications/cc) — it's the syllabus, everything flows from it
- [ ] Pick study material covering the **2026** outline (not the old 2022 one — domains changed)
- [ ] Set a target exam date and register at Pearson VUE when you're scoring ~80%+ on practice tests
- [ ] Baseline: take one practice exam cold, score it by domain, and let your weak domains set your schedule

**Suggested pacing (6 weeks, heaviest domains first):**
- Week 1–2: Domain 1 (Security Principles) + Domain 4 (Networking & Cloud)
- Week 3: Domain 3 (IAM)
- Week 4: Domain 2 (Security Governance — your future GRC wheelhouse) + Domain 5 (SecOps & IR)
- Week 5: Full practice exams, drill weak areas
- Week 6: Review, cheat-sheet pass, exam day

---

## Free resources mapped by domain ($0 study plan)

**Core kit (all free):**
- Official CC exam outline PDF (isc2.org) — the syllabus
- A free full CC video course on YouTube (search "ISC2 CC free course 2026" — ignore stale free-voucher claims in video descriptions)
- [CertCrush](https://www.certcrush.app) — free CC lessons, practice questions, flashcards, mock exams per domain
- [TryHackMe](https://tryhackme.com) free tier — hands-on labs, no credit card
- Udemy CC practice-exam set (6 tests / 900 questions) — free via coupon code; grab it while the coupon is live

| Domain | Free study | Free hands-on |
|---|---|---|
| D1 Security Principles (24%) | CC video course D1 lessons; CertCrush D1 questions | None needed — vocabulary domain, flashcards are the lab |
| D2 Security Governance (17.3%) | CC video course D2 lessons; NIST Cybersecurity Framework 2.0 (free at nist.gov) — skim it, this is the GRC bible and your future lane | None needed |
| D3 IAM (20%) | CC video course D3 lessons; CertCrush D3 questions | TryHackMe free rooms covering authentication concepts |
| D4 Networking & Cloud (21.3%) | CC video course D4 lessons; Professor Messer's free Network+ series (YouTube) for networking depth; Cisco "Introduction to Cybersecurity" (free, Cisco Skills for All) | TryHackMe **Pre Security** path — networking + Linux from absolute zero, one room a day |
| D5 SecOps & IR (17.3%) | CC video course D5 lessons; MITRE ATT&CK (free at attack.mitre.org) — concept-level, exactly what the exam tests | TryHackMe free intro-to-SOC rooms |

**The $0 path, in order:**
1. TryHackMe Pre Security — networking + Linux basics first (feeds D4 and D5)
2. Free CC video course, domains 1→5, checking boxes on this list as you go
3. CertCrush questions after each domain
4. Full practice exams (Udemy coupon set + CertCrush mocks); study only weak domains until 80%+ everywhere
5. Pay the $199 and schedule Pearson VUE only when the scores say you're ready — the score gate is the plan

---

## 1 · Security Principles — 24% of exam
The foundation. Nail the vocabulary cold.
- [ ] CIA triad: Confidentiality, Integrity, Availability — and what breaks each
- [ ] AAA framework: Authentication, Authorization, Accounting
- [ ] Risk terminology: threat, vulnerability, risk, likelihood, impact
- [ ] Risk appetite vs. risk tolerance
- [ ] Risk management concepts: the risk management lifecycle and processes
- [ ] Governance artifacts and their hierarchy: regulations, laws, policies, standards, procedures, guidelines, frameworks (know mandatory vs. discretionary)
- [ ] Privacy concepts and basic legal/regulatory awareness
- [ ] ISC2 Code of Ethics: the four canons and their priority order
- [ ] Due care and due diligence
- [ ] Foundational AI topics: identify AI assets, recognize automated threats, secure governance of emerging tech
- [ ] Non-repudiation, least privilege (preview), separation of duties (preview), defense in depth

## 2 · Security Governance — 17.3% of exam
*New dedicated domain in the 2026 outline — and basically baby GRC, your long-term lane.*
- [ ] GRC concepts: what Governance, Risk, and Compliance each mean and how they connect
- [ ] Organizational security awareness and building a cybersecurity culture
- [ ] Measuring program effectiveness: metrics, KPIs, KRIs (Key Risk Indicators), dashboards, reports
- [ ] Business continuity & disaster recovery concepts: BCP, DRP, backups
- [ ] RTO (Recovery Time Objective) and RPO (Recovery Point Objective)
- [ ] Redundancy, fault tolerance, high availability
- [ ] Incident response moved to Domain 5 — but know how BC/DR and IR relate

## 3 · Identity and Access Management (IAM) Concepts — 20% of exam
*Formerly "Access Controls" — expanded in 2026 around identity lifecycle.*
- [ ] Least privilege, separation of duties, defense in depth (applied to access)
- [ ] Access control models: DAC, MAC, RBAC, ABAC (and rule-based)
- [ ] Identity lifecycle: provisioning, deprovisioning, periodic account/access reviews
- [ ] Authentication factors: something you know / have / are
- [ ] MFA (multi-factor authentication), biometrics (and their error rates: FAR/FRR), SSO
- [ ] Password policies and credential management
- [ ] Authorization vs. authentication — never mix them up on a question
- [ ] Accounting/auditing: logging who did what
- [ ] IAM frameworks and tools (directory services, PAM, identity providers)

## 4 · Networking and Cloud Security Concepts — 21.3% of exam
- [ ] OSI model (7 layers) and TCP/IP model — what happens at each layer
- [ ] Common ports and protocols: HTTP/S, DNS, DHCP, FTP, SSH, SMTP, Telnet, SNMP, LDAP
- [ ] Network devices: routers, switches, firewalls, IDS vs. IPS, proxies, WAF (Web Application Firewall)
- [ ] Segmentation: VLANs, subnets, DMZ, micro-segmentation
- [ ] Zero trust concepts
- [ ] VPNs and secure remote access
- [ ] Wireless security: WPA2/WPA3, why WEP is broken, rogue access points
- [ ] Cloud characteristics, deployment models (public/private/hybrid/community), service models (IaaS/PaaS/SaaS)
- [ ] Shared responsibility model — who secures what in each service model
- [ ] IoT, embedded systems, and ICS (industrial control systems) security basics

## 5 · Security Operations and Incident Response — 17.3% of exam
*Biggest expansion in the 2026 outline — and this is where your DFIR interest lives.*
- [ ] Data classification and handling; states of data (at rest, in transit, in use)
- [ ] Encryption: symmetric vs. asymmetric, hashing, digital signatures, PKI and certificates, TLS
- [ ] Data masking, data sanitization/destruction (wipe, degauss, destroy)
- [ ] Quantum-resistant cryptography (new topic — know the concept)
- [ ] Logging and monitoring: what to log, SIEM basics, baselines and anomaly detection
- [ ] Threat actors and motivations (script kiddies → nation-states)
- [ ] Cyber threat intelligence: what it is and how it's used
- [ ] Threat frameworks: Cyber Kill Chain, MITRE ATT&CK (concept-level)
- [ ] Security event triage and prioritization
- [ ] Incident response phases: preparation → detection & analysis → containment → eradication → recovery → lessons learned
- [ ] IR planning, playbooks, and tabletop exercises
- [ ] Security readiness testing: vulnerability scanning, penetration testing, red / blue / purple teams
- [ ] Application security testing and threat modeling (concept-level)
- [ ] System hardening, patch management, change management
- [ ] Physical security: locks, mantraps, biometrics, cameras, environmental controls
- [ ] Social engineering: phishing, spear phishing, pretexting, baiting, tailgating — and awareness training as the countermeasure

---

## Exam-day checklist
- [ ] Two forms of ID (check Pearson VUE requirements the week before)
- [ ] Know the CAT (adaptive) rules: answer carefully, no going back
- [ ] Sleep > cramming the night before
- [ ] After passing: complete the application and pay the $50 AMF to activate membership

## Progress
- [ ] Baseline practice exam taken (score: ___)
- [ ] Domain 1 practice scores consistently ≥ 80%
- [ ] Domain 2 practice scores consistently ≥ 80%
- [ ] Domain 3 practice scores consistently ≥ 80%
- [ ] Domain 4 practice scores consistently ≥ 80%
- [ ] Domain 5 practice scores consistently ≥ 80%
- [ ] Registered for exam (date: ___)
- [ ] **PASSED** 🎯

---
*Built by SABLE from the official 2026 CC exam outline. Checkboxes are yours to burn through, Arcanist.*
