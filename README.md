# Chord Buddy Duo - Test Reports

Automated CI/CD test reports for the Chord Buddy Duo project.

## Latest Report
- **Date**: 2025-09-17
- **Time**: 12:18:57
- **Branch**: main
- **Commit**: dbcab4fae83389cb89fa3699028104a80eabd12b
- **Run ID**: 17797300635
- **Path**: [`reports/2025/09/17/run-17797300635`](reports/2025/09/17/run-17797300635/)

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
