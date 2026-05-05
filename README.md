# Lord Fernandez

Paralegal and software engineer at the San Francisco District Attorney's Office. I build automation tools that legal teams actually adopt.

Currently shipping internal tooling for case management, discovery production, evidence handling, and document generation — using Claude Code, Power Automate Desktop, Python, Playwright, and custom Chrome extensions. 15+ workflows in production.

---

## About these repositories

Most repositories are private because the work product touches sensitive case data, criminal history records, and government case management systems. Privacy-by-default is a hard requirement, not a preference.

Public artifacts and architecture documentation forthcoming. Demos and design docs for current private projects available on request.

---

## Selected work

**eProsecutor Task Intelligence Dashboard** — Chrome Extension · Claude Code · Multi-Factor Algorithm  
Chrome extension that transforms the unreadable eProsecutor assignment inbox (the office case management system) into an intelligent, prioritized task dashboard. Multi-factor prioritization across hundreds of assignments. Saves 30–45 minutes daily. *(private)*

**Legal Records AI Translation Tool** — Python · FastAPI · Ollama · LLaMA 3.1 8B · SQLite  
Locally-hosted, privacy-preserving application that translates criminal history records into structured, attorney-readable reports. Ephemeral RAM architecture with zero PII persistence, no external API calls. Hand-built SQLite penal code reference for accurate charge classification. *(private; architecture documentation forthcoming)*

**In-Custody Packet Builder** — Python · PowerShell · Power Automate Desktop · Claude Code · OCR  
Automated assembly of multi-document in-custody legal packets. OCR-driven include/exclude logic, court-ordered document combination, single master PDF triggered by court number input. Saves 8–10 minutes per packet across dozens of daily filings. *(private)*

**Bates Media Discovery Suite** — Power Automate Desktop · Python · DOS · Word  
End-to-end discovery media workflow: ingests files from physical media (CD, USB, drive), creates labeled folders on archival drive and SharePoint, uploads files, generates a formatted discovery receipt and transmittal email. Saves 7–9 minutes per discovery event.

**Case Service Request Automation (OrderMug / OrderRap)** — Python · Playwright · Claude Code  
Automated routine investigator service requests within eProsecutor — mugshots, RAP sheets, evidence orders. Batch processing of up to a dozen requests from a single court-number input.

**Paralegal Toolkit — Chrome Extension Suite** — JavaScript · Chrome Extension API · Python · Claude Code  
Suite of browser-based tools for paralegal workflows without Adobe Acrobat dependencies. PDF Bates Numbering: live on Chrome Web Store. RedactPDF and CleanMetadata: in active development.

## Stack

Python · JavaScript · Claude / Claude Code / Claude Projects · Power Automate Desktop · Playwright · Chrome Extension API · Ollama · FastAPI · SQLite
