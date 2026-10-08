# TruthLens AI — Professional Offline Hackathon Demo

**Problem Statement:** PS 9 — Identifying and Verifying Misinformation on the Internet  
**Event:** Prompt 2 Product — CSI AITR × MLH — 8 October 2026

## What is included

A professional, responsive, multi-page vanilla HTML/CSS/JavaScript application:

- Premium dark AI SaaS interface
- Login + signup + demo authentication
- Password visibility + strength meter
- Dashboard with metrics and recent activity
- Claim verification workspace
- Example misinformation claims
- Animated AI analysis flow
- Confidence score and verdict dashboard
- Evidence / Context / Source Quality tabs
- Local browser history
- Search, filter and sorting
- About page and verification pipeline
- Profile/settings page
- Dark/light theme
- Responsive mobile navigation
- Hover/glow/transition effects
- localStorage persistence
- Fully offline; no CDN, API key or server required

## Demo credentials

Email: `demo@truthlens.ai`  
Password: `Demo@123`

## Run

1. Extract the ZIP.
2. Open `index.html` in Chrome or Edge.
3. Click **Get Started** or Login.
4. Use the demo credentials above.
5. Try **Verify** and click an example claim.

No npm, Node.js, Live Server or internet is required.

## Pages

- `index.html` — Landing page
- `login.html` — Login
- `signup.html` — Registration
- `dashboard.html` — User dashboard
- `verify.html` — Verification workspace
- `result.html` — Analysis + result
- `history.html` — Verification history
- `about.html` — Product explanation
- `settings.html` — Profile/settings

## Important demo limitation

This is an offline prototype. It does **not** perform real-time internet searches or claim that it has verified live sources. The local JavaScript engine provides deterministic demo results so the complete product flow can be demonstrated without internet.

## Production upgrade

For a real deployment:
1. Add a backend/authentication service.
2. Connect an LLM for claim decomposition and explanation.
3. Connect a trusted search/retrieval layer.
4. Rank and cross-check primary/credible sources.
5. Store verification reports server-side.
6. Add rate limits, abuse prevention and audit logs.
7. Add source citations to every factual verification.

## Folder structure

```text
TruthLensAI/
├── index.html
├── login.html
├── signup.html
├── dashboard.html
├── verify.html
├── result.html
├── history.html
├── about.html
├── settings.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── data.js
│   └── app.js
└── assets/
    └── README.txt
```
