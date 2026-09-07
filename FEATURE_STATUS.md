# Feature status — Product, projects & engineering operations

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 190 pages |
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
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 2 | 0 | Native records/view |
| Contacts & parties | records | 1 | 0 | Native records/view |
| Tasks | records | 3 | 0 | Native records/view |
| Calendar | records | 1 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 1 | 0 | Native records/view |
| Activity & audit trail | audit | 3 | 0 | Native records/view |
| Provider connections | integration | 2 | 0 | Provider request records only |
| PR Flow | records | 1 | 0 | Native records/view |
| Quality | records | 1 | 0 | Native records/view |
| AI Usage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Spend | records | 1 | 0 | Native records/view |
| Repository | records | 1 | 0 | Native records/view |
| Pull Request | records | 1 | 0 | Native records/view |
| Review Cycle | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Defect | records | 1 | 0 | Native records/view |
| Agent Session | records | 1 | 0 | Native records/view |
| Token Usage | records | 1 | 0 | Native records/view |
| Cycle Time Metric | records | 1 | 0 | Native records/view |
| Spend Report | records | 1 | 0 | Native records/view |
| Agent Anomaly | records | 1 | 0 | Native records/view |
| Engineer | records | 1 | 0 | Native records/view |
| Quality Gate | records | 1 | 0 | Native records/view |
| Spend Alert | records | 1 | 0 | Native records/view |
| Draft: Flow Briefing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Agent Usage Auditor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: AI ROI Comparator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discovery | records | 1 | 0 | Native records/view |
| Definition | records | 1 | 0 | Native records/view |
| Build | records | 1 | 0 | Native records/view |
| Ship | records | 1 | 0 | Native records/view |
| Product Area | records | 1 | 0 | Native records/view |
| Customer Problem | records | 1 | 0 | Native records/view |
| Opportunity | records | 1 | 0 | Native records/view |
| Specification | records | 1 | 0 | Native records/view |
| Prototype | records | 1 | 0 | Native records/view |
| Test Plan | records | 1 | 0 | Native records/view |
| PR Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approval Gate | records | 1 | 0 | Native records/view |
| Feedback Signal | records | 1 | 0 | Native records/view |
| Release Candidate | records | 1 | 0 | Native records/view |
| Metric Movement | records | 1 | 0 | Native records/view |
| Design Review | integration | 1 | 0 | Provider request records only |
| Draft: Problem Clustering | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: Spec Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft: PR Drafter | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bookmarks | records | 2 | 0 | Native records/view |
| File Organizer | records | 2 | 0 | Native records/view |
| Password Auditor | records | 2 | 0 | Native records/view |
| Digital Detox | records | 1 | 0 | Native records/view |
| Focus Timer | records | 2 | 0 | Native records/view |
| Habits | records | 1 | 0 | Native records/view |
| Goals | records | 1 | 0 | Native records/view |
| Engineering Velocity | records | 1 | 0 | Native records/view |
| Digital Detox Coach | records | 1 | 0 | Native records/view |
| Run | records | 1 | 0 | Native records/view |
| Feedback | records | 2 | 0 | Native records/view |
| Admin | records | 1 | 0 | Native records/view |
| Weekly digest | records | 1 | 0 | Native records/view |
| Usage stats | records | 1 | 0 | Native records/view |
| Cross insights | records | 1 | 0 | Native records/view |
| Goal progress predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Usage anomaly detect | records | 1 | 0 | Native records/view |
| Focus boost recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product Roadmap | records | 2 | 0 | Native records/view |
| User Stories | records | 2 | 0 | Native records/view |
| Sprint Planning | records | 4 | 0 | Native records/view |
| Stakeholders | records | 2 | 0 | Native records/view |
| Market Research | records | 2 | 0 | Native records/view |
| Competitive Analysis | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Product Metrics | records | 2 | 0 | Native records/view |
| Releases | records | 2 | 0 | Native records/view |
| A/B Tests | records | 2 | 0 | Native records/view |
| Requirements | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Risk Assessment | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Team Capacity | records | 2 | 0 | Native records/view |
| OKR Tracking | records | 2 | 0 | Native records/view |
| AI History | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Product Health | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Velocity Chart | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Competitor Tool | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Sprint Planner AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Release Notes AI | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Stakeholder Update | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Roadmap Gantt | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sprint Kanban | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| OKR Tree | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| PM Chat Agent | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sentiment Analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Metric Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Feature Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product Development Studio | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agentic PM orchestration | records | 1 | 0 | Native records/view |
| Continuous customer insight synthesis | records | 1 | 0 | Native records/view |
| Roadmap impact simulator | records | 1 | 0 | Native records/view |
| Stakeholder storytelling | records | 1 | 0 | Native records/view |
| Competitive threat detection | records | 1 | 0 | Native records/view |
| Feedback without `/sentiment | records | 1 | 0 | Native records/view |
| Metrics without `/metric | records | 1 | 0 | Native records/view |
| Features without `/feature | records | 1 | 0 | Native records/view |
| No frontend (backend | records | 1 | 0 | Native records/view |
| Limited integration with analytics platforms (Mixpanel, Amplitude) | integration | 1 | 0 | Provider request records only |
| No native Jira/Linear sync | records | 1 | 0 | Native records/view |
| No native Slack integration for updates | integration | 1 | 0 | Provider request records only |
| Limited user research tools (survey integration) | integration | 1 | 0 | Provider request records only |
| No file upload for research artifacts | records | 1 | 0 | Native records/view |
| Feature Prioritization | records | 1 | 0 | Native records/view |
| Stakeholder Management | records | 1 | 0 | Native records/view |
| Product Metrics & KPIs | records | 1 | 0 | Native records/view |
| Customer Feedback | records | 1 | 0 | Native records/view |
| Release Management | records | 1 | 0 | Native records/view |
| A/B Test Planning | records | 1 | 0 | Native records/view |
| Product Requirements | records | 1 | 0 | Native records/view |
| Product management copilot v2 work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product management copilot v3 work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Today's Standups | records | 1 | 0 | Native records/view |
| Team Members | records | 2 | 0 | Native records/view |
| Milestones | records | 1 | 0 | Native records/view |
| Time Logs | records | 1 | 0 | Native records/view |
| Retrospectives | records | 1 | 0 | Native records/view |
| Kanban | records | 1 | 0 | Native records/view |
| Project health | records | 1 | 0 | Native records/view |
| Standup summary | records | 1 | 0 | Native records/view |
| Estimate timeline | records | 1 | 0 | Native records/view |
| Smart assign | records | 1 | 0 | Native records/view |
| agentic sprint planner | records | 1 | 0 | Native records/view |
| realtime burndown streaming | records | 1 | 0 | Native records/view |
| crossteam resource optimization | records | 1 | 0 | Native records/view |
| meeting recording transcription | records | 1 | 0 | Native records/view |
| sentimentdriven sprint review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai timeline estimation under velocitydepe | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai autoassignment by skills and workload | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai meeting transcript summarization to ta | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ai burnoutsentiment detection across stan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| public webhook system or outbound integra | integration | 1 | 0 | Provider request records only |
| native jiragithublinearslack connectors | integration | 1 | 0 | Provider request records only |
| formal rbac matrix granular permission ro | records | 1 | 0 | Native records/view |
| fileupload route attachments rely on docu | records | 1 | 0 | Native records/view |
| ssooauth provider hookups | records | 1 | 0 | Native records/view |
| Workflows | records | 1 | 0 | Native records/view |
| Captured Steps | records | 1 | 0 | Native records/view |
| Replay Runs | records | 1 | 0 | Native records/view |
| Selector Library | records | 1 | 0 | Native records/view |
| Healing Events | records | 1 | 0 | Native records/view |
| Exceptions | records | 1 | 0 | Native records/view |
| AI · Analyze Capture | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Generate Replay Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Self-Heal Failed Step | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Intent Classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Parameter Suggester | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Branch Detector | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Exception Resolver | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Workflow Merger | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Workflow library | records | 1 | 0 | Native records/view |
| Demo to sop | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Action classifier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Automation script gen | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| filler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Narrate step | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dedup workflows | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Continuous improvement | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recordings | records | 1 | 0 | Native records/view |
| Permissions | records | 1 | 0 | Native records/view |
| Redaction | records | 1 | 0 | Native records/view |
| Marketplace | records | 1 | 0 | Native records/view |
| Role dashboard | records | 1 | 0 | Native records/view |
| Dynamic software interfaces work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Users | records | 1 | 0 | Native records/view |
| Labels | records | 1 | 0 | Native records/view |
| Issues | records | 1 | 0 | Native records/view |
| Issue labels | records | 1 | 0 | Native records/view |
| Comments | records | 1 | 0 | Native records/view |
| Incumbents | records | 1 | 0 | Native records/view |
| Challengers | records | 1 | 0 | Native records/view |
| Pricing models | records | 1 | 0 | Native records/view |
| Displacement cases | records | 1 | 0 | Native records/view |
| Switching costs | records | 1 | 0 | Native records/view |
| Moats | records | 1 | 0 | Native records/view |
| Gap features | records | 1 | 0 | Native records/view |
| Agent knowledge documents | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent questions & citations | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Agent evaluation records | records | 1 | 0 | Native records/view |
| Agent tool execution requests | integration | 1 | 0 | Provider request records only |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 190 feature pages were visited in the browser; 188 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 57 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

57 original AI entries are now grouped into **7 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

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
