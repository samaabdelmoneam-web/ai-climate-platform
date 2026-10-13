# EcoBalance AI — starter MVP

## Run locally
Open `index.html` in a modern browser. No build step is needed.

## Included
- Responsive bilingual English/Arabic UI with RTL support
- Light/dark theme toggle
- Hover/focus help tips on calculator fields
- Energy savings, avoided emissions, and simple payback calculator
- CSV export and browser Print / Save as PDF
- Simulated IoT readings clearly labeled as simulated
- Rule-based demo assistant (not a real LLM connection)
- Conceptual campus map and roadmap sections

## Important prototype limits
This is a frontend prototype only. It does NOT include user accounts, a secure multi-tenant database, real MQTT devices, a production AI model, verified campus locations, or audited emissions factors. Data entered in the calculator is processed in the browser and is not saved to an institutional account. Do not use the illustrative default values as official results.

## Recommended next implementation phase
1. Create a backend and database with tenant isolation (e.g. PostgreSQL + Supabase or a custom API).
2. Add authentication, organization roles, and access-control tests.
3. Validate calculation formulas, tariff rules, and official emissions factors.
4. Add report templates with institutional logos and data provenance.
5. Add secure MQTT ingestion and real device provisioning.
6. Connect the AI assistant through a backend proxy with strict organization-level data permissions.
7. Add forecasting only after enough clean historical readings are collected.

The included hero image is a generated visual mockup, not a screenshot of a live system.


## Professional bilingual explainer and creator portrait
- Added the provided creator portrait to the creator section.
- Replaced the short explainer with a slower, silent bilingual caption video (English + Arabic), about 38 seconds, with gentle motion and a creator end card.
- Video poster: `assets/ecobalance-video-poster.png`.
