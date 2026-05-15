# The Navigator Demo

**Navigator Twin v2.8.2 Stable Demo — Agency Navigation Build**

This repository hosts a stable demonstration build of **The Navigator**, a local-first AI-supported reflection and agency-navigation app. The demo is designed for reviewers, collaborators, instructors, potential users, and early conversations about the larger Navigator / AMC / PBC project.

## What this demo includes

- Digital Twin conversation
- Twin Journal
- Document Capsules
- Field Scans
- Field Map Dashboard
- Context Assembly
- Agency-Preserving Move Cards
- Cross-Field Move Comparison
- Current Move selection
- Current Move Deliberation Plan
- TXT / JSON export
- JSON import / restore
- Fictional demo data mode
- Help, glossary, release notes, and PWA readiness notes

## Start here

1. Open the app.
2. Click **Load Fictional Demo** on the Home workspace if you want to see the full workflow quickly.
3. Visit **Field Map** to inspect Field Scans and Context Assembly.
4. Visit **Moves** to inspect Move Cards, Cross-Field Move Comparison, and Current Move Deliberation.
5. Visit **Twin** and ask the Twin what it sees in the demo case.
6. Visit **Memory** to inspect Journal entries, Document Capsules, and backup controls.

## Privacy posture

Navigator is designed as a **local-first** app. Conversation, Journal entries, Document Capsules, Field Scans, Context Assembly, Move Cards, comparison state, and Current Move Plans are stored in the browser unless the user exports or restores them.

Backend AI calls occur only when the user asks the Twin to interpret, summarize, deliberate, create a capsule, or generate an AI-assisted response. Those requests require sending selected prompt context to the configured backend service for processing. Users should avoid uploading highly sensitive material unless they understand that selected content may be sent for AI processing.

Document uploads create reviewable capsules; the app saves only the capsule the user approves, not the raw uploaded document text.

## What this demo does not do

- It does not diagnose, treat, grade, command, or replace professional advice.
- It does not decide who the user is or what the user must do.
- It does not include a service worker or PWA caching yet.
- It does not provide automatic cross-device sync.
- It does not claim that external AI processing is fully private unless a future private/local model deployment is used.

## Development status

This is a stable demonstration release, not the active experimental branch. Future development may include PWA conversion, Navigator Private API endpoints, PRF-22 import, Applications / Coaches modules, and timeline/simulation layers.
