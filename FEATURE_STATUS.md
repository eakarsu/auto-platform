# Feature status — Automotive sales, repair & inspections

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 146 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 5 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 1 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 0 | 0 | Native records/view |
| Reports & analytics | report | 5 | 0 | Native records/view |
| Activity & audit trail | audit | 1 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| OEM policy and rate library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| VIN and warranty eligibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Repair-order ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Labor operation validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Technician time reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parts reimbursement calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Diagnostic-time recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sublet and towing recovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall and campaign claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim edit and documentation control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rejected claim classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OEM appeal package | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Claim response and resubmission | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Remittance reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dealer recovery analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Appointments | records | 1 | 0 | Native records/view |
| Damage Assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OEM Parts Pricing | records | 2 | 0 | Native records/view |
| Inventory | records | 3 | 0 | Native records/view |
| Insurance Claims | records | 1 | 0 | Native records/view |
| Repair Timelines | records | 1 | 0 | Native records/view |
| Cost Estimates | records | 1 | 0 | Native records/view |
| Work Orders | records | 1 | 0 | Native records/view |
| Technicians | records | 1 | 0 | Native records/view |
| Suppliers | records | 2 | 0 | Native records/view |
| Photo Gallery | records | 1 | 0 | Native records/view |
| Vehicles | records | 4 | 0 | Native records/view |
| Supplements | records | 1 | 0 | Native records/view |
| Trade ins | records | 1 | 0 | Native records/view |
| Trade in confidence | records | 1 | 0 | Native records/view |
| Fni | records | 1 | 0 | Native records/view |
| Leads | records | 1 | 0 | Native records/view |
| Deals | records | 1 | 0 | Native records/view |
| Service | records | 1 | 0 | Native records/view |
| Inspections | records | 2 | 0 | Native records/view |
| Test drives | records | 1 | 0 | Native records/view |
| Followups | records | 1 | 0 | Native records/view |
| Campaigns | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Staff | records | 1 | 0 | Native records/view |
| Commissions | records | 1 | 0 | Native records/view |
| Studio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 2 | 0 | Provider request records only |
| Weather Demand Forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Chemical Dosing Optimization | records | 1 | 0 | Native records/view |
| Equipment Maintenance Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart Staffing Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Membership Churn Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Revenue Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer Sentiment Analysis | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Energy Usage Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location Management | records | 1 | 0 | Native records/view |
| Equipment Inventory | records | 1 | 0 | Native records/view |
| Employee Management | records | 1 | 0 | Native records/view |
| Chemical Inventory | records | 1 | 0 | Native records/view |
| Service Packages | records | 1 | 0 | Native records/view |
| History | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Maintenance Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall Impact | records | 1 | 0 | Native records/view |
| Agentic vehicle health monitoring | records | 1 | 0 | Native records/view |
| Computer vision damage assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recall proactive management | records | 1 | 0 | Native records/view |
| Smart maintenance scheduling | records | 1 | 0 | Native records/view |
| Parts compatibility optimization | records | 1 | 0 | Native records/view |
| Maintenance without `/maintenance | records | 1 | 0 | Native records/view |
| Recalls without `/recall | records | 1 | 0 | Native records/view |
| Services without `/service | records | 1 | 0 | Native records/view |
| No real vehicle API integration (BMW ConnectedDrive, Tesla API, OBD2) | integration | 1 | 0 | Provider request records only |
| No parts ordering (integration with retailers) | integration | 1 | 0 | Provider request records only |
| No integration with mechanics/service shops | integration | 1 | 0 | Provider request records only |
| No appointment booking/scheduling module | records | 1 | 0 | Native records/view |
| No notifications module (grep 0) | records | 1 | 0 | Native records/view |
| No audit logging (grep 0) | records | 1 | 0 | Native records/view |
| No webhooks for recall/safety alerts | integration | 1 | 0 | Provider request records only |
| No mobile app despite consumer | records | 1 | 0 | Native records/view |
| Owner Manuals | records | 2 | 0 | Native records/view |
| Tech Specs | records | 2 | 0 | Native records/view |
| Troubleshooting | records | 2 | 0 | Native records/view |
| Maintenance | records | 4 | 0 | AI question-and-answer workspace; records available as context |
| Warning Lights | records | 2 | 0 | Native records/view |
| Safety Features | records | 2 | 0 | Native records/view |
| FAQ | records | 2 | 0 | Native records/view |
| Tutorials | records | 2 | 0 | Native records/view |
| Recall Notices | records | 2 | 0 | Native records/view |
| Parts Catalog | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Service Centers | records | 2 | 0 | Native records/view |
| Warranty Info | records | 2 | 0 | Native records/view |
| General Chat | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Diagnostics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Warning Explainer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| State Compliance | records | 1 | 0 | Native records/view |
| Condition Scoring | records | 1 | 0 | Native records/view |
| Market Valuation | records | 1 | 0 | Native records/view |
| Damage Detection | records | 1 | 0 | Native records/view |
| Vehicle History | records | 1 | 0 | Native records/view |
| Recall Alerts | records | 1 | 0 | Native records/view |
| Insurance Estimates | records | 1 | 0 | Native records/view |
| Fleet Summary | records | 1 | 0 | Native records/view |
| VIN Decoder | records | 1 | 0 | Native records/view |
| Vision Damage | records | 1 | 0 | Native records/view |
| Certificates | records | 1 | 0 | Native records/view |
| AI Predictive Maint. | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Insurance Est. | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Recall Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NHTSA Recall Lookup | records | 1 | 0 | Native records/view |
| Parts Price Monitor | records | 1 | 0 | Native records/view |
| ADAS Calibration | records | 1 | 0 | Native records/view |
| Maintenance Schedule | records | 1 | 0 | Native records/view |
| vision based damage assessment from photos with repair cost | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive maintenance flagging vehicles by age mileage condition | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| parts price monitoring with bulk order timing recommendations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| repair shop network with quality ratings | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| insurance claim automation generating filings from damage photos | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| vin decoder integration for auto populated vehicle profiles | integration | 1 | 0 | Provider request records only |
| critical no ai for damage assessment from photos | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| predictive maintenance ml | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| insurance estimate generation ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| fraud detection on inspection data | records | 1 | 0 | Native records/view |
| integration with oem recall databases only manual | integration | 1 | 0 | Provider request records only |
| parts supplier integration | integration | 1 | 0 | Provider request records only |
| third party repair shop network | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| insurance claim integration direct insurer api | integration | 1 | 0 | Provider request records only |
| webhooks notifications for recall events | integration | 1 | 0 | Provider request records only |
| customer self service portal | records | 1 | 0 | Native records/view |
| Tickets | records | 1 | 0 | Native records/view |
| Orders | records | 1 | 0 | Native records/view |
| Quotes | records | 1 | 0 | Native records/view |
| Warranty Claims | records | 1 | 0 | Native records/view |
| Point of Sale | records | 1 | 0 | Native records/view |
| Repair SLA Monitor | records | 1 | 0 | Native records/view |
| AI Tools | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settings | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 146 feature pages were visited in the browser; 144 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 49 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

49 original AI entries are now grouped into **8 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
