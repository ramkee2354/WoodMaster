# WoodMaster

GitHub-ready first clean build.

## Architecture
- Frontend: single-page HTML/CSS/JavaScript
- Backend: Supabase PostgreSQL + Auth + Realtime-ready schema
- Hosting: independent; can be connected to Cloudflare Pages, GitHub Pages-compatible static hosting, or another static host.

## Current scope
- Authentication
- Dashboard
- Loads
- New Load
- Masters read-only
- New Load creates the network weighment and load together.
- No separate Network Receipt module.
- No Network Receipt Number is required.

## New Load workflow
Network weighbridge slip received -> New Load -> Date, Vehicle, Gross, Tare, PO, E-way Bill, Freight, Advance -> Create Load.

## Important
This is the first clean application baseline. Document generation, OCR, ITC Weighment, Final Freight, AMC, receipt reconciliation, material invoicing, role permissions, audit hardening and backups are intentionally subsequent modules.
