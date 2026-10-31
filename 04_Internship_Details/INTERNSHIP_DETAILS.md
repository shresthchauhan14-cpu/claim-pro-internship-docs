# Web Development Internship Details

**Project Title:** CLAIM PRO – Insurance Claims Management System  
**Host Organization:** Data Alcott Systems  
**Affiliated Platform:** [FreeInternships.in](https://www.freeinternships.in/)  
**Domain:** Web Development  
**Internship Mode:** Remote  

---

## 1. Candidate & Registration Metadata

| Attribute | Verified Value |
| :--- | :--- |
| **Student Name** | Shreshth Chauhan |
| **Student Code / Registration No.** | DAS012321 |
| **Internship ID** | 5696 |
| **Portal Task ID** | #5110 |
| **Certificate Number** | DAS-COMP-252/2026 |
| **Certificate Issue Date** | 28 October 2026 |
| **Internship Duration** | 21 October 2026 – 28 October 2026 |
| **Reporting Manager** | Gokul Rajan |
| **HR Representative** | Thirumalai Kumar |
| **Certificate Verification URL** | [Verify Certificate](https://www.freeinternships.in/verify_certificate.php?certificate=DAS-COMP-252%2F2026) |

---

## 2. Project Overview & Deliverables

**CLAIM PRO** is a responsive Single-Page Application (SPA) designed to streamline the complete lifecycle of insurance claims—from intake filing and document validation to officer underwriting review, approval gating, financial settlement disbursement, and actuarial reporting.

### Core Objectives Delivered:
1. **Single-Page Architecture (SPA):** Hash-based routing (`#dashboard`, `#all-claims`, `#claim-review`, `#settlements`, `#documents`, `#reports`, `#settings`) providing an instantaneous, app-like experience with zero page refreshes.
2. **Defensive Form Validation:** 4-step intake wizard enforcing strict validation (10-digit Indian phone formatting, positive numeric amounts, future incident date blocking, and drag-and-drop file ingestion).
3. **Document Verification Compliance Gate:** Core underwriting safeguard that strictly prohibits claim approval if any attached supporting document (bills, FIRs, medical receipts) is missing, unverified, or rejected.
4. **Settlement & Disbursement Tracking:** Enforces payout limits bounded by approved policy benefits, synchronizes terminal status (`Settled` only upon `Paid` confirmation), and generates printable payment vouchers.
5. **Actuarial Business Intelligence:** 10 dynamic KPI metric cards, dynamic inline SVG claim volume trend lines, category donut charts, and secure RFC-compliant CSV data export with formula injection defense.

---

## 3. Technology Implementation Details

- **Markup & Semantics:** HTML5 standards-compliant semantic architecture (`<header>`, `<nav>`, `<aside>`, `<main>`, `<dialog>`).
- **Styling & Layout:** Vanilla CSS3 featuring a custom design system tokenized with CSS custom properties (`--primary: #7C3AED`, `--bg-app: #F8FAFC`). Includes responsive CSS Grid/Flexbox layouts (320px–1440px), high-contrast Dark Mode (`data-theme="dark"`), and dedicated `@media print` rules.
- **Client Scripting & State Management:** Vanilla JavaScript (ES6+), Object-Oriented Store architecture (`ClaimStore`), asynchronous DOM rendering updates, and temporary Blob URL generation for document previews.
- **Persistence Engine:** Browser `window.localStorage` with JSON serialization, pre-seeded realistic demonstration data, and factory data reset.
- **Visuals & Charts:** Pure inline SVG graphics for dynamic 6-month filing volume trend lines and category donut charts with zero third-party chart library dependencies.

> **Note on Architecture:** This project is engineered as an offline-capable, client-side web application using browser LocalStorage for state persistence. It is a frontend demonstration that does not require a production backend server or external database.

---

## 4. Key Links & References

- **Live Demonstration:** [https://shresthchauhan14-cpu.github.io/claim-pro/](https://shresthchauhan14-cpu.github.io/claim-pro/)
- **Source Code Repository:** [https://github.com/shresthchauhan14-cpu/claim-pro](https://github.com/shresthchauhan14-cpu/claim-pro)
- **YouTube Walkthrough Video:** [https://www.youtube.com/watch?v=Gdbz637qS1E](https://www.youtube.com/watch?v=Gdbz637qS1E)
- **Documentation Repository:** [https://github.com/shresthchauhan14-cpu/claim-pro-internship-docs](https://github.com/shresthchauhan14-cpu/claim-pro-internship-docs)
- **Host Organization Website:** [https://www.freeinternships.in/](https://www.freeinternships.in/)
