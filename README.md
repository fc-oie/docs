# Fullerton College OIE Reports Repository  
**Repository:** `docs`  

## 📌 Purpose  
This repository serves as the public archive of institutional-research reports produced by OIE. Reports are organized by **topic**, then **year**, then by output format (e.g., HTML).  
This structure enables external stakeholders (faculty, staff, students, community) to easily locate and download key findings and analyses.

## 📁 Organization  

Note: If you have a better way of organization, please let me know.

The folder structure follows this convention:  

```
├─ RealCollegeCA/
│   ├─ 2023/
│   │   ├─ Report.html
│   │   ├─ Report.pdf
│   └─ 2025/
│       ├─ Report.html
│       └─ Report.pdf
└─ StudentSuccess/
    └─ 2024/
        ├─ Report.html
        └─ Report.pdf
```

Files named "report.html", "report.pdf", or "report.docx" will be automatically indexed. No other files will be indexed.

- **Topic**: e.g., RealCollegeCA, StudentSuccess, EnrollmentTrends  
- **Year**:  e.g., 2023, 2024, 2025  
- Files inside each year folder represent final outputs of that year’s report (primarily `Report.html`, optionally `.pdf`, etc.)

## 🌐 Access  
The repository is configured for GitHub Pages. The main site URL is:  
`https://fc-oie.github.io/docs/`  
From there you can navigate by topic and year to view or download reports.

## 📄 File Types  
Typically you will find:  
- `Report.html` — interactive or static HTML version  
- Optionally, `Report.pdf` or `Report.docx` for offline viewing  
- Supporting assets (images, CSS) are included in the same folder when needed  

## 🧩 How to Contribute  
If you:  
- develop a new report  
- update an existing report  
please follow the institutional internal workflow, then commit to the appropriate topic/year folder.  
Ensure the report is named consistently (`Report.html`), and confirm the file renders correctly in the browser.

## 🧼 Clean Up / Maintenance  
- Older drafts, working files, and raw data are not included in this public repository — only final deliverables are archived here.  
- The repository uses a `.gitignore` configured to track only source R Markdown files, final output (HTML, PDF, DOCX), and exclude raw data, caches, and temp files.

---

*Last updated: 2025-11-05*
