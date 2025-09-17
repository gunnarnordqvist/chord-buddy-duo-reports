# Chord Buddy Duo - Test Reports

Automated CI/CD test reports for the Chord Buddy Duo project.

## Latest Report
- **Date**: 2025-09-17
- **Time**: 12:30:17
- **Branch**: main
- **Commit**: 64e7c8accf9a2730815808f95dfebbcb52690d23
- **Run ID**: 17797582175
- **Path**: [`reports/2025/09/17/run-17797582175`](reports/2025/09/17/run-17797582175/)

## Report Structure
```
reports/
├── YYYY/MM/DD/run-<run_id>/
│   ├── summary.md              # Human-readable summary
│   ├── ci-report.json          # Machine-readable CI results  
│   ├── lint-results.json       # ESLint results
│   ├── coverage-lcov.info      # Coverage data (LCOV format)
│   ├── coverage-summary.json   # Coverage summary
│   └── coverage/               # Full coverage reports
└── latest -> YYYY/MM/DD/run-<latest_run_id>  # Symlink to latest
```

## Quick Access
- [Latest Report](reports/latest/)
- [All Reports](reports/)

---
*Reports are automatically generated and pushed after each CI/CD run.*
