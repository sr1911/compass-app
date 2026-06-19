# 🧭 Compass
### Always know where you are and what's next.

**Compass** is an AI companion for international F-1 students in the US — helping them navigate visa compliance from arrival to OPT activation, and matching them to jobs they can legally take.

Built by **Shazia Rahman** — International student, SCU MBA graduate, AI/GPU systems engineer, and founder.

---

## Live Demo

| App | Link |
|-----|------|
| 🎓 Student App | [Open app](https://sr1911.github.io/compass-app/compass_demo_v2.html) |
| 🏢 Employer Dashboard | [Open dashboard](https://sr1911.github.io/compass-app/compass_employer_dashboard.html) |

> **Note:** This is a frontend HTML/CSS/JavaScript prototype demonstrating the full product vision — UI, user journey, and feature set. Pre-loaded responses simulate AI behavior. Backend and live AI integration are the next build phase.

---

## The Problem

1.1 million international students in the US are navigating a system that was never designed to be understood.

- **1 in 8** OPT applications denied — often for fixable paperwork errors
- **800+** students per DSO advisor nationally — overwhelmed and unavailable at midnight
- Most students get the wrong answer from Reddit. Some lose their status because of it.

> *"I built Compass because I needed it. And I know I am not the only one."*
> — Shazia Rahman, International Student & SCU MBA Graduate

---

## The Product

Compass is two things in one:

### 🗺 Navigate — Visa Compliance Companion
- Timeline-aware AI that knows your I-20 end date, OPT filing window, CPT eligibility, and every deadline
- Proactively tells you what to do **this week** — before you even think to ask
- Answers questions specific to your visa type, your program, your exact situation
- Tracks unemployment days, CPT usage, EAD status, and employer reporting requirements

### 💼 Career — Jobs You Can Actually Take
- Filters jobs by E-Verify enrollment, CPT/OPT eligibility, degree field match, and H-1B sponsorship history
- Each job card answers: Can I legally take this? Does it match my degree? Should I apply now or wait?
- Covers full-time OPT roles, CPT internships, on-campus jobs, and self-employment on OPT

> *"LinkedIn shows you 10,000 jobs. Compass shows you the 14 you can actually take."*

---

## Tech Stack

**Prototype** — Frontend only
- HTML, CSS, vanilla JavaScript
- No backend or framework
- Pre-loaded responses simulating AI behavior
- Single file — runs in any browser with no installation

**Production roadmap**
- Backend: Node.js or Python FastAPI
- AI layer: Gemini API or Claude API
- Database: Supabase / PostgreSQL
- Auth: Firebase Auth
- Job data: Indeed API, LinkedIn API, Handshake
- Deployment: Google Cloud Run via Google AI Studio

---

## The Vision — Two-Sided Platform

**Students** use Compass free → find a job → accept an offer → **employer gets auto-onboarded** to the compliance dashboard → employer pays $2K–10K/month for real-time workforce authorization tracking.

The student relationship is the acquisition engine. The employer dashboard is the revenue engine. Nobody else is building this from the student side first.

---

## Business Model

| Tier | Price | Who |
|------|-------|-----|
| Free | $0 | Students — basic OPT navigation |
| Pro | $19/month | Students — full timeline, career matching, alerts |
| Business | $2K–10K/month | Employers — workforce compliance dashboard |

---

## Market

- **1.1M** international students in the US
- **220K** new F-1 arrivals every year
- **418K** students currently on OPT
- 1% penetration at Pro tier = **$528K ARR**

---

## File Structure

```
compass-app/
├── compass_demo_v2.html          # Student-facing app (Navigate + Career tabs)
├── compass_employer_dashboard.html  # Employer compliance dashboard
└── README.md                     # This file
```

---

## What's Next

- [ ] Live Gemini API integration for real-time AI responses
- [ ] User authentication and persistent timeline tracking
- [ ] USCIS processing time API integration
- [ ] Job board API connections (Indeed, LinkedIn, Handshake)
- [ ] Employer dashboard with HRIS integrations
- [ ] Mobile app (React Native)
- [ ] Publish to Google AI Studio

---

## About

**Shazia Rahman** — International student, SCU MBA graduate, GPU/AI systems engineer (NVIDIA, AMD), and founder. Built Compass because she lived this problem. Building it for the 1.1 million students who need it too.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shazia%20Rahman-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/shazia-rahman-empathetic-curious-business-leader)

---

*Compass — helping international students navigate the system that brought them here, and build the career that lets them stay.*
