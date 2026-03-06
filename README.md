Intelli-Credit — AI Credit Appraisal Engine

A fully client-side, single-file AI-powered Credit Appraisal Memorandum (CAM) generator for banking and credit analysis.

---

## Features

- **Drag & Drop Dataset Ingestion** — Upload CSV, Excel (.xlsx/.xls), or JSON financial datasets instantly
- **Auto Field Mapping** — Automatically detects Revenue, EBITDA, PAT, Debt, Equity, DSCR, CIBIL, Litigation, and more
- **AI Credit Scoring** — Five Cs framework (Character, Capacity, Capital, Collateral, Conditions) with a composite score out of 100
- **Dynamic CAM Generation** — Full Credit Appraisal Memorandum with 8 structured sections
- **PDF Export** — Professional, print-ready PDF with cover page, financial tables, risk flags, and covenants
- **Document Vault** — Upload and manage multiple datasets; switch between them without page reload
- **Risk Flag Analysis** — Contextual, banker-quality risk explanations with severity levels and covenant recommendations
- **AI Insight Summary** — Narrative credit assessment with Financial Strength, Risk Indicators, and Overall Credit Risk
- **Primary Insights** — Add field observations (site visits, management interviews) that adjust the credit score
- **Research Agent** — Sector and promoter intelligence feed

---

## CAM Report Structure

1. Executive Summary
2. Borrower Profile
3. Five Cs Assessment
4. Financial Summary & Key Ratios
5. Risk Flags & Mitigants
6. Primary Insights & Field Observations
7. AI Insight Summary
8. Recommendation & Covenants

---

## Supported Dataset Formats

| Format | Extension |
|--------|-----------|
| CSV | `.csv` |
| Excel | `.xlsx`, `.xls` |
| JSON | `.json` |

Datasets should contain financial columns such as revenue, EBITDA, PAT, debt, equity, DSCR, CIBIL score, litigation exposure, etc. The engine auto-maps column names using keyword matching.

---

## Usage

1. **Open** `index.html` in a browser
2. **Go to Data Ingestor** — drag and drop your financial dataset
3. **Review** the auto-mapped fields and adjust if needed
4. **Go to CAM Generator** — fill in loan details, then click **Generate Preview**
5. **Download PDF** for the complete Credit Appraisal Memorandum

---

## Tech Stack

| Library | Purpose |
|---------|---------|
| [jsPDF](https://github.com/parallax/jsPDF) | PDF generation |
| [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) | Table rendering in PDF |
| [PapaParse](https://www.papaparse.com/) | CSV parsing |
| [SheetJS (XLSX)](https://sheetjs.com/) | Excel parsing |

All libraries are loaded from CDN. The entire application is a **single HTML file** with no build step.

---

## Screenshots
<img width="1903" height="906" alt="CAM dashboard - Copy" src="https://github.com/user-attachments/assets/3165c15a-e556-4a5a-af20-953e28ce0aae" />

<img width="1898" height="912" alt="Data Ingestor" src="https://github.com/user-attachments/assets/b58e8141-4529-407d-a412-925e6d896caa" />

<img width="1905" height="905" alt="Research Agent" src="https://github.com/user-attachments/assets/a1357836-5c27-4cfa-80b4-edab0673d1e9" />

<img width="1911" height="917" alt="Primary Insights" src="https://github.com/user-attachments/assets/e7ec3f14-17c5-4cd8-89ba-222e7c64d1d7" />

<img width="1909" height="914" alt="Document Vault" src="https://github.com/user-attachments/assets/e10587e1-cfea-404b-871f-01591e16349f" />

<img width="1913" height="904" alt="Cam generator" src="https://github.com/user-attachments/assets/7c9b5263-03c6-416e-8a6f-f2e5222da7fe" />

<img width="1909" height="909" alt="Case History" src="https://github.com/user-attachments/assets/ce0ac553-d77f-4075-b02e-901830878533" />


> Upload a dataset → instant AI credit score → professional CAM PDF

---


