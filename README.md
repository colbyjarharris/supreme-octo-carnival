# supreme-octo-carnival
🎯 A full-stack Product Owner case study demonstrating backlog management, user stories, agile sprint planning, automated QA testing, and CI/CD using GitHub Actions. Built to showcase real-world product delivery and QA leadership in an agile environment.


# Agile Product Case Study — PO + QA Portfolio

This repository demonstrates **end-to-end Product Ownership** with real artifacts:
- Product vision → personas → roadmap
- Epics → user stories with acceptance criteria
- Backlog → sprint plan → release notes
- QA strategy → automated tests (Cypress/UI, Postman/API)
- CI pipeline via **GitHub Actions**

> Use this project to showcase how you turn insights into outcomes, align teams, and ship quality.

---

## 🔭 Product Vision

**Problem**: Small retail teams struggle to track product training, demos, and promotions across multiple stores and partners.

**Solution**: A lightweight **Field Sales Assistant** web app that helps reps and managers:
- Track store visits and display compliance (VMD/POP/Golden Zones)
- Log promotions, attach photos, and capture store feedback
- See a prioritized backlog and roadmap aligned to business outcomes

**North Star Metric**: +15% lift in weekly sell-through per store within 60 days.

---

## 👤 Personas

1. **Field Sales Rep (FSR)** — needs fast logging and offline capture to document store visits and promotions.
2. **Store Manager** — wants visibility on planogram compliance and top promo opportunities.
3. **Regional Lead** — needs roll-up analytics, dependency tracking, and training coverage.

---

## 🗺️ Roadmap (MVP → V1)

**MVP (0–6 weeks)**
- Visit logging (store, date, SKUs, notes, photo URL)
- Promotion catalog (active/expired, bundles)
- Compliance checklist (VMD/POP/Display/Golden Zone)
- Basic dashboard + CSV export

**V1 (6–12 weeks)**
- Offline-first capture + sync
- Photo uploads with annotations
- Store insights (trends, gaps) & coaching tips
- Role-based access (Rep / Manager / Lead)

> Prioritization Framework: RICE + OKRs

---

## 📦 Repository Layout

```
/docs
  user_stories.md         # Epics, stories, acceptance criteria
  sprint_1_notes.md       # Sprint plan, estimates, retro, release notes
/tests
  cypress_sample.spec.js  # UI test (example)
  postman_collection.json # API tests (example)
.github/workflows
  ci.yml                  # CI pipeline to run tests
README.md
```

---

## 🧪 Running Tests (local)

UI (Cypress):
```bash
npm install
npx cypress run
```

API (Postman via Newman):
```bash
npm install -g newman
newman run tests/postman_collection.json
```

---

## 🤝 Collaboration Model

- **Issues**: Create stories/bugs. Use labels: `epic`, `story`, `bug`, `enhancement`, `ux`, `tech-debt`.
- **Projects**: Sprint board: `Todo → In Progress → In Review → Done`.
- **PRs**: Link issues, include screenshot/video for UX; add test evidence.
- **Definition of Done**: Dev complete + tests passing + UAT signoff + docs/notes updated.

---

## 📣 How to Use for Interviews

- Open **Issues** and **Projects** to show live backlog.
- Walk through `/docs/user_stories.md` → `/docs/sprint_1_notes.md`.
- Run tests locally to demonstrate CI mindset.
- Share trade-offs, constraints, and metrics.

---

© 2025 agile-product-case-study
