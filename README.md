# CLAIM PRO — Web Development Internship Documentation

[![Domain](https://img.shields.io/badge/Domain-Web%20Development-purple.svg)](#)
[![Host](https://img.shields.io/badge/Organization-Data%20Alcott%20Systems-blue.svg)](https://www.freeinternships.in/)
[![Status](https://img.shields.io/badge/Status-Completed%20%26%20Verified-success.svg)](#)
[![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS%20%7C%20LocalStorage-orange.svg)](#)
[![Live Demo](https://img.shields.io/badge/Demo-Live%20Application-brightgreen.svg)](https://shresthchauhan14-cpu.github.io/claim-pro/)

This repository serves as the official documentation archive for the **CLAIM PRO – Insurance Claims Management System** web development internship project, completed at **Data Alcott Systems** (affiliated with [FreeInternships.in](https://www.freeinternships.in/)).

---

## 📌 Quick Links

- 🌐 **Live Application Demo:** [https://shresthchauhan14-cpu.github.io/claim-pro/](https://shresthchauhan14-cpu.github.io/claim-pro/)
- 💻 **Source Code Repository:** [https://github.com/shresthchauhan14-cpu/claim-pro](https://github.com/shresthchauhan14-cpu/claim-pro)
- 🎥 **YouTube Walkthrough Video:** [https://www.youtube.com/watch?v=Gdbz637qS1E](https://www.youtube.com/watch?v=Gdbz637qS1E)
- 📜 **Official Certificate Verification:** [Verify Certificate (DAS-COMP-252/2026)](https://www.freeinternships.in/verify_certificate.php?certificate=DAS-COMP-252%2F2026)

---

## 📋 Internship Metadata

| Detail | Specification |
| :--- | :--- |
| **Student Name** | Shreshth Chauhan |
| **University Roll No.** | 2410030045 |
| **Class Section** | 3CSE14 |
| **Degree & Course** | B.Tech Computer Science & Engineering |
| **Department** | School of Computer Science and Engineering |
| **University** | IILM University, Greater Noida, UP |
| **Internship Student Code** | DAS012321 |
| **Internship ID** | 5696 |
| **Portal Task ID** | #5110 |
| **Certificate Number** | DAS-COMP-252/2026 |
| **Host Organization** | Data Alcott Systems / FreeInternships.in |
| **Domain** | Web Development |
| **Mode** | Remote |
| **Internship Duration** | 21 October 2026 – 28 October 2026 |
| **Reporting Manager** | Gokul Rajan |

---

## 📖 Project Overview

**CLAIM PRO** is a responsive, high-performance Single-Page Application (SPA) designed to streamline the complete lifecycle of general and health insurance claims. The application eliminates the friction, delays, and lack of transparency inherent in manual, paper-driven claim operations.

### Key Capabilities & Business Logic:
1. **Executive KPI Dashboard & Telemetry:** 10 dynamically calculated metric KPI cards, real-time activity audit stream, and math-driven inline SVG trend lines and category donut charts.
2. **Guided 4-Step Claim Intake Wizard:** Multi-step claim filing with Indian 10-digit mobile number verification, positive amount checks, future incident date blocking, and drag-and-drop document upload.
3. **Master Claims Directory & Archive:** Searchable, sortable, filterable archive with multi-parameter matching, status badges, and client-side pagination.
4. **Officer Review & Document Verification Queue:** Granular document auditing (hospital bills, police FIRs, identity proofs) with status toggles (`Verified`, `Pending`, `Rejected`) and internal notes.
5. **Mandatory Approval Lockout Gate:** Underwriting safeguard ensuring claims strictly cannot transition to `Approved` if any attached document remains pending or rejected.
6. **Settlement & Payout Management:** Payout ceiling enforcement (cannot exceed approved claim amount), state synchronization (`Settled` only upon `Paid` confirmation), and printable disbursement vouchers.
7. **Actuarial Reports & Data Export:** Category distribution matrices and RFC-compliant CSV data exports with spreadsheet formula injection defense.
8. **Role-Based Access Control (RBAC):** Fast switching between Reviewer (`Sarah Jenkins`) and Claimant (`Rahul Sharma`) profiles to demonstrate authentic data isolation.

> **Architectural Note:** CLAIM PRO is engineered as an offline-capable, client-side web application using browser `LocalStorage` for all state persistence. It is a pure frontend demonstration that does not require a production backend server or external database.

---

## 🛠️ Technology Stack

| Technology | Role & Implementation Details |
| :--- | :--- |
| **HTML5** | Semantic structure (`<header>`, `<nav>`, `<aside>`, `<main>`, `<dialog>`), native modal dialogs with keyboard ESC listeners, ARIA accessibility. |
| **CSS3** | Custom design system tokenized with CSS variables (`--primary: #7C3AED`, `--bg-app: #F8FAFC`), Flexbox/Grid layouts, Dark Mode (`data-theme="dark"`), `@media print` rules. |
| **Vanilla JavaScript (ES6+)** | Object-Oriented Store architecture (`ClaimStore`), dynamic DOM rendering, Blob URL generation (`URL.createObjectURL`), formula injection defense. |
| **Browser LocalStorage** | JSON schema state persistence, pre-seeded realistic demonstration data, and single-click factory data reset. |
| **Inline SVG** | Math-calculated 6-month claim volume trend lines and category donut charts with zero third-party chart libraries. |

---

## 📂 Repository Structure & Verified Documents

```
claim-pro-internship-docs/
│
├── README.md                                  # Repository overview and documentation guide
│
├── 01_Project_Report/
│   └── PROJECT_REPORT_FINAL_COMPRESSED.pdf    # 31-page academic internship project report (PDF, 2.44 MB)
│
├── 02_Project_Presentation/
│   ├── CLAIM_PRO_Internship_Presentation.pptx # 16-slide academic PowerPoint presentation (PPTX, 2.50 MB)
│   └── CLAIM_PRO_Internship_Presentation.pdf  # 16-slide academic vector presentation export (PDF, 1.20 MB)
│
├── 03_Certificates/
│   └── shreshth__certificate.pdf              # Official certificate of internship completion (PDF, 734 KB)
│
└── 04_Internship_Details/
    └── INTERNSHIP_DETAILS.md                  # Comprehensive internship and registration metadata
```

---

## 📥 Downloadable Project Documents

All official internship submission documents are verified, intact, and directly accessible:

- 📄 **[Download Final Project Report (PDF)](./01_Project_Report/PROJECT_REPORT_FINAL_COMPRESSED.pdf)** — Comprehensive 31-page academic report with IILM University formatting, Candidate Declaration, Acknowledgement, Table of Contents, Certificate chapter, 52/52 test matrix, and 17 screenshots.
- 📊 **[Download Presentation Deck (PPTX)](./02_Project_Presentation/CLAIM_PRO_Internship_Presentation.pptx)** — 16-slide academic widescreen PowerPoint presentation with IILM University branding, Roll No 2410030045, Section 3CSE14, verified screenshots, and speaker notes.
- 📑 **[View Presentation (PDF)](./02_Project_Presentation/CLAIM_PRO_Internship_Presentation.pdf)** — Vector PDF export of the complete 16-slide academic presentation.
- 🎓 **[Download Completion Certificate (PDF)](./03_Certificates/shreshth__certificate.pdf)** — Verified certificate issued by Data Alcott Systems (Certificate ID: `DAS-COMP-252/2026`).
- 📝 **[Read Detailed Internship Metadata (MD)](./04_Internship_Details/INTERNSHIP_DETAILS.md)** — Registration numbers, dates, mentors, and deliverables breakdown.

---

## 🧪 Testing & Quality Assurance Summary

- **Syntax & Static Analysis:** JavaScript code verified via Node.js syntax analyzer (`node --check script.js`) with 0 syntax errors or unhandled promises.
- **Automated Node Test Suites (52 Tests Passing):**
  - Brand token integrity, dark mode overrides, and `@media print` rules.
  - CSV formula injection defense sanitizing `=`, `+`, `-`, `@` prefixes.
  - Form validation rules (10-digit mobile, positive amounts, future date blocking).
  - Document verification approval lockout guards.
  - Settlement payout limit enforcement and terminal status synchronization.
- **Headless Chrome Verification:** DOM rendering, dynamic KPI calculation (8 claims, ₹19,18,500 volume), SVG chart plotting, and SPA hash routing verified using real Google Chrome CLI (`--headless --dump-dom`).

---

## 👤 Author & Attribution

- **Student:** Shreshth Chauhan
- **Student Code:** DAS012321
- **Internship ID:** 5696 | **Task ID:** #5110
- **Organization:** Data Alcott Systems / FreeInternships.in
- **Domain:** Web Development (21 October 2026 – 28 October 2026)
