# SAR Nexus v3 — AI-Powered Compliance Intelligence

## Quick Start (Windows)

### Frontend only (recommended for demo)
```powershell
cd sarfinal\frontend
npm install
npm start
```
Open http://localhost:3000 — no backend needed, uses in-memory data.

### Full stack
```powershell
# Window 1 - Backend
cd sarfinal\backend && npm install && Copy-Item .env.example .env && npm run dev

# Window 2 - Frontend  
cd sarfinal\frontend && npm install && npm start
```

## Demo Accounts
| Email | Password | Role | Can do |
|-------|----------|------|--------|
| analyst@sar.io | demo123 | Analyst | View, Add transactions, Create SARs |
| officer@sar.io | demo123 | Officer | Approve, Reject, File on-chain, Send warnings |
| legal@sar.io   | demo123 | Legal   | Read-only, Audit log |
| admin@sar.io   | demo123 | Admin   | Everything |
