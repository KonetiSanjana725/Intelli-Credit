<img width="1909" height="909" alt="image" src="https://github.com/user-attachments/assets/1d16ff49-c247-4d09-8837-34f332f0c63e" /># Intelli-Credit — AI Credit Appraisal Engine

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



> Upload a dataset → instant AI credit score → professional CAM PDF

---

## Disclaimer

Intelli-Credit is a decision-support tool. All credit decisions must be reviewed and approved by authorised credit officers in accordance with applicable banking regulations. The AI-generated output does not constitute a sanctioned credit decision.

---

