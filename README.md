# Chord Buddy Duo - Test Reports

Automated CI/CD test reports for the Chord Buddy Duo project.

## Latest Report
- **Date**: 2025-09-17
- **Time**: 11:32:42
- **Branch**: main
- **Commit**: 4371f8bed248398cdac3b0b13574bdd603c746c3
- **Run ID**: 17796181999
- **Path**: [`reports/2025/09/17/run-17796181999`](reports/2025/09/17/run-17796181999/)

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
