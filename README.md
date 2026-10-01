# FraudShield AI

Hackathon-ready static prototype for the problem statement:

**AI Financial Fraud Investigation Agent**

The prototype follows the requested agent flow:

Transaction → Anomaly → Behaviour → Pattern → Investigation → Risk → Report

## Included pages

- `index.html` - Home / landing page
- `register.html` - Demo registration
- `login.html` - Demo login
- `dashboard.html` - Security dashboard
- `transactions.html` - Suspicious transaction list
- `investigation.html` - Seven-agent investigation simulation
- `report.html` - Evidence-backed investigation report
- `profile.html` - Demo investigator profile

## How to run

No Node.js, database, API key or build tool is required.

1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Click Get Started and create a demo account.
4. Login.
5. Open Dashboard → Investigation.

For a local server, you can also run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Important

This is a **prototype with simulated data**. It does not connect to a real bank/payment system and should not be presented as a production fraud detector.

Passwords are stored in browser `localStorage` only for the demo. Do not use this authentication approach for a real application.

## Hackathon demo flow

Home → Register → Login → Dashboard → Transactions → Investigate TXN-10482 → Run AI Investigation → Evidence → Report.

## Error check performed

- All HTML files use the same CSS/JS paths.
- All referenced pages exist.
- JavaScript syntax was checked with Node.js when available.
- HTML tag balance and local asset references were checked by a local validation script.
