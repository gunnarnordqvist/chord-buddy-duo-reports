# Chord Buddy Duo - Test Reports

Automated CI/CD test reports for the Chord Buddy Duo project.

## Latest Report
- **Date**: 2025-09-17
- **Time**: 11:51:46
- **Branch**: main
- **Commit**: e6a7280b646d69d97dda178b3e3588c8265b727a
- **Run ID**: 17796626326
- **Path**: [`reports/2025/09/17/run-17796626326`](reports/2025/09/17/run-17796626326/)

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
