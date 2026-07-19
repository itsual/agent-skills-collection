---
name: xlsx
description: >
  Create well-structured, usable Excel spreadsheets (.xlsx) with clear data layout, formulas, formatting, and analysis-ready tables.
  Use when the user asks for a spreadsheet, Excel file, tracker, model, dashboard data, or .xlsx. Prefer clean data tables over purely visual formatting.
---

# XLSX – Spreadsheet Production

## Overview

Produce spreadsheets that are easy to understand, maintain, and analyze. Separate raw data from presentation, use formulas correctly, and make the structure obvious to the next person (or agent) who opens the file.

## When to Use

- User requests an Excel file, spreadsheet, tracker, financial model, data table, or .xlsx
- Data needs calculation, filtering, or structured analysis
- Deliverable must be usable in Excel / Google Sheets / LibreOffice Calc

## Core Principles

- One clear purpose per sheet when possible
- Put raw data in clean tabular form (no merged cells in data regions)
- Use formulas instead of hard-coded calculated values
- Separate inputs, calculations, and outputs
- Apply number formats, headers, and freeze panes thoughtfully
- Make assumptions and units visible
- Avoid unnecessary colors and decorations that hinder analysis

## Recommended Practices

- Header row with clear column names
- Consistent data types per column
- Use tables (ListObjects) where helpful
- Named ranges for key inputs
- Clear separation of inputs (often highlighted) vs. results
- Include a short “Notes” or “Assumptions” area when the model is non-trivial

## Verification

- [ ] Formulas calculate correctly and are not overwritten with values
- [ ] Data is in a clean, filterable/tabular layout
- [ ] Units, currency, and percentages are formatted properly
- [ ] Key assumptions are visible
- [ ] File opens without errors in major spreadsheet applications
- [ ] File is saved as .xlsx

## Common Pitfalls

- Merged cells in the middle of data ranges
- Hard-coded values that should be formulas
- Hidden logic that is difficult to audit
- Over-formatting that makes the sheet fragile
