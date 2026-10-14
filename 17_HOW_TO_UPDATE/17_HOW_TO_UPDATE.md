# How to Update — POS

**Project:** `POS`
**Category:** SUPERMARKETS
**Domain:** supermarkets
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
POS --version
POS check-update
```

### Applying Updates
```bash
pip install --upgrade POS
```

### Rolling Back
```bash
pip install POS==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
