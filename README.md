# Danny_Barren_CV
My updated resume

# Daniel Lee Barren

**Independent Custom AI/ML Development and Software Engineering**  
Columbus, Ohio · Palm Beach, Florida · Remote  

[github.com/DannyBarren](https://github.com/DannyBarren) · [dannybarren.com](https://dannybarren.com) · [linkedin.com/in/danny-barren](https://linkedin.com/in/danny-barren)

Open to full-time and contract · remote or hybrid · FL / Midwest on-site OK

---

## Professional Summary

Independent developer specializing in custom AI/ML systems, data engineering pipelines, and production software. Built and managed large-scale relational databases (7M+ records), end-to-end automation pipelines, CRM architectures, and applied machine learning solutions across political operations and financial services. At JPMorgan Chase, automated multi-hour workflows into minutes using Python, Alteryx, and ML semantic extraction. Independently designs and ships agentic systems (CrewAI, LangGraph), local-first RAG pipelines, stacked classification engines, and full-stack applications (FastAPI, Streamlit). Caltech-certified in AI & ML Programming. CompTIA Security+. Secret clearance.

---

## Technical Skills

### Data Engineering & Automation
- Python ETL/ELT pipelines (Pandas, source-to-target validation)
- Complex SQL, relational database design and management (7M+ records)
- Microsoft Dynamics 365, Access/VBA automation
- Alteryx, Tableau, ServiceNow, SAP
- Geomapping & spatiotemporal data processing
- Data brokering platforms, CRM architecture

### Machine Learning & AI
- Stacked classification engines (rules → memory → TF-IDF → Logistic Regression / SetFit)
- Semantic extraction and document analysis
- scikit-learn, TensorFlow/Keras, 3D CNNs, Faster R-CNN
- Predictive modeling, applied ML for process automation
- GAM modeling (statistical support)

### Agentic AI & Software Engineering
- CrewAI, LangChain, LangGraph multi-agent systems
- Local-first RAG (ChromaDB), tool-calling agents with cost/runtime guardrails
- FastAPI, Streamlit, Flask, hybrid NFC architectures
- Production UIs with human review loops, auditability, and offline-capable design
- WeasyPrint PDF generation, Deepgram STT, Docker deploys

### Languages & Tools
Advanced Python (Pandas, NumPy, Pydantic), SQL, VBA, Excel, Tableau, PowerPoint, APIs, Fireside CRM, Mailchimp

---

## Professional Experience

### Independent Custom AI/ML Development and Software Engineering
**May 2026 – Present · Remote · Columbus, OH / Palm Beach, FL**

- Design and deliver custom AI/ML systems, data pipelines, and production software for clients, including agentic orchestration (CrewAI/LangGraph), classification engines, RAG knowledge systems, and full-stack operational applications.
- Built production tools such as Code_Down_ML (stacked GL classification with review loops and memory), report automation systems (JobDoc/GenerSwift: narrated walkthroughs → structured PDFs via STT + LLM), and local-first agentic operators.
- Architect client-owned, offline-capable systems that remove SaaS lock-in, with emphasis on auditability, cost controls, human-in-the-loop review, and measurable workflow compression.

### Business Analyst — Data Engineering & Process Automation
**JPMorgan Chase · Columbus, OH · November 2022 – May 2026**  
*CIB Finance & Business Management (Jun 2025 – May 2026) · Client Service Analyst (Nov 2022 – Jun 2025)*

- Automated end-to-end data pipelines covering sourcing, preprocessing/engineering, KPI calculation, and visualization to managers, reducing a 20-hour manual process to under 10 minutes using Python, Alteryx, Tableau, PowerPoint, and APIs.
- Applied ML semantic extraction with Python to automatically analyze and query large volumes of contracts for specific terms, delivering structured, actionable results to managers.
- Managed and automated an Access database (VBA, SQL, Python) containing hundreds of thousands of contractors and tens of thousands of contracts, enabling scalable querying, reporting, and data integrity.
- Designed and automated multi-day analytics and invoice PDF extraction pipelines in Python (Pandas) and Alteryx, cutting end-to-end processing from 15+ hours to under 1 hour. Built structured ETL against Ariba, SAP, Concur, and GSS with source-to-target validation and reusable data-quality logic.

### Director of Grassroots Initiatives
**Troy Balderson for Congress · 2020**

- Managed the full voter and contact database plus a volunteer base of hundreds, using SQL, Python, Microsoft Dynamics 365, Access, Excel, VBA, Fireside CRM, Mailchimp, and data brokering platforms to support district-wide operations.
- Built custom geomapping and spatiotemporal data processing programs that provided managers with real-time visualizations of voter distributions and grassroots strategy, directly informing campaign decisions and resource allocation.
- Directed all district-wide grassroots initiatives and analytics-driven email and social outreach that increased voter engagement and contributed to a 14-point electoral victory.

### Data & CRM Systems Specialist
**Ohio Senate Majority Caucus Communications Office · 2016 – 2018**

- Designed, built, and managed CRM systems and relational databases using Microsoft Dynamics 365, Access, Excel, and complex SQL queries for a database exceeding 7 million records.
- Wrote complex SQL queries to extract and analyze data supporting Senate initiatives; automated data engineering pipelines with Access and VBA to streamline reporting, constituent workflows, and operational data flows.
- Owned end-to-end database architecture, data integrity, pipeline automation, and CRM operations for caucus communications and Senate majority needs.

---

## Selected Projects

### PoleDrop — Full-Stack Operational System for Elite Pole Vault Rental & Meet Administration (2026)
Re-engineered an 87-file SwiftUI + SwiftData + Firebase iOS app into a production FastAPI + SQLAlchemy web application on Railway/Neon Postgres. Imported live operational data (26 athletes, 271 poles, reservations, locations, financials). Designed hybrid NFC architecture (Capacitor/Xcode for iOS Core NFC, Web NFC for Android, PC/SC USB for desk) with exact tag compatibility. Diagnosed and remediated N+1 queries and connection bottlenecks for real-time meet/kiosk use. Built domain pricing/fees (JSON overrides), Square integration, full reservation lifecycle, exporters, audit logs, and the structured data foundation for ML-driven pole recommendations. *(Private client project)*

### [Code_Down_ML](https://github.com/DannyBarren/Code_Down_ML) — Stacked GL / Transaction Classification Engine
Production stacked classifier for general ledger and transaction coding: keyword rules → learned memory → TF-IDF / semantic embeddings → Logistic Regression (SetFit optional). Every automated fill carries a confidence score and plain-language rationale; uncertain items go to a human review queue. Existing codes are never overwritten. Spreadsheet-first with auditability, collision handling, and throughout-the-month ingest. Deployed as a live Streamlit/Railway application used by accountants.

### [Report Automation (JobDoc / GenerSwift)](https://github.com/DannyBarren/report_automation)
AI-guided report generation system that turns narrated job-site walkthroughs into structured, professional PDF reports. Uses Deepgram speech-to-text with timestamped “Mark this” cue detection, CrewAI/LLM reasoning against JSON templates, and WeasyPrint for PDF export. Mobile-first, white-label ready, with media acceleration and human approval gates. Designed for trades, inspectors, and compliance workflows.

### [LA Crime Prediction Model](https://github.com/DannyBarren/LA_Crime_Prediction)
Multimodal 3D CNN (TensorFlow/Keras) forecasting weekly violent-crime clusters across a 60×75 Los Angeles grid using crime incident data (2020–August 2025) plus weather features. Achieved MAE ≈ 0.18 with side-by-side predicted-vs-actual heatmap visualization for operational planning.

### [Primus](https://github.com/DannyBarren/primus) — Local-First Agentic Operator
Local-first agentic system that lives on the user’s device for private, offline-capable AI operations. Designed as a client-owned operator for research, document processing, and workflow automation without cloud dependency or vendor lock-in. Fast facts stay on-device; hard leftover work can call a capped frontier model with approval gates.

### Additional Public Work
- **[NightForge-LeadForge](https://github.com/DannyBarren/NightForge-LeadForge)**: Cost-capped CrewAI + Streamlit overnight lead system for US trades SMBs. Public data only. Human review on every row.
- **[PrivaGen-Anonymizer](https://github.com/DannyBarren/PrivaGen-Anonymizer)**: GPU-first image anonymizer with face/text detection, EXIF strip, per-file JSON audit, and automatic CPU fallback.
- **[WordPressGenius](https://github.com/DannyBarren/WordPressGenius)**: LangGraph operator for WordPress / WooCommerce with draft-first approval gates and JSON backups.
- **[AgenticAIResearchTeam](https://github.com/DannyBarren/AgenticAIResearchTeam)**: CrewAI + Flask + local ChromaDB system for document-grounded market research and PDF deliverables.

---

## Research Contributions

Provided statistical and analytical support (GAM modeling of microbial abundance data) for Rosing, T., et al. *Characterizing seawater microbiomes near reefs in the Gulf Coast*. University of Miami Rosenstiel School of Marine, Atmosphere, and Earth Science. Manuscript in preparation.

---

## Education, Certifications & Military

- **Caltech** — Artificial Intelligence and Machine Learning Programming Certification, October 2025
- **CompTIA Security+** — March 2026
- **Wittenberg University** — B.A., Summa Cum Laude, 2020 · Triple major: Russian, Religious Studies, Political Science / International Studies · College Football
- **Ohio Army National Guard** — Enlisted Infantryman · October 2020 – October 5, 2026 · E-5 · Secret Clearance · Airborne · Bradley Gunner

---

*Last updated: October 2026*
