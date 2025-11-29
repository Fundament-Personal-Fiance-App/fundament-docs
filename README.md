📚 Fundament Docs

This repository contains all documentation, planning, and internal knowledge for Fundament — the personal finance app designed to help youth build strong financial foundations through budgeting, credit education, and investing.

The purpose of this repo is to organize product planning, architecture, design, workflows, and team onboarding.

⸻

🧭 Project Roadmap

Phase 0 — Foundation (You are here)
	•	Create GitHub organization ✔
	•	Create repos ✔
	•	Add READMEs ✔
	•	Architecture draft ⬜
	•	Design system ⬜
	•	Supabase project setup ⬜

Phase 1 — App & Backend Setup
	•	Expo project scaffolding
	•	Supabase auth
	•	Navigation structure
	•	Base UI components
	•	First AI function: Expense categorizer

Phase 2 — Personal Finance Engine
	•	Expense & income tracking
	•	Budget creation
	•	Categories
	•	Analytics + charts
	•	AI Budget Coach (v1)

Phase 3 — Credit & Savings Module
	•	Credit card comparison
	•	Savings account comparison
	•	Credit score learning
	•	AI “best product for me”

Phase 4 — Investment Simulator
	•	Paper trading
	•	Portfolio dashboard
	•	Market data integration
	•	AI investment tutor

⸻

🧱 Architecture Overview

┌──────────────────────────────────────────────────────┐
│                     Fundament                         │
├──────────────────────────┬────────────────────────────┤
│      Mobile App          │        Backend              │
│   (Expo / React Native)  │     (Supabase Postgres)     │
├──────────────────────────┴────────────────────────────┤
│                 AI Engine (Edge Functions + OpenAI)   │
└──────────────────────────────────────────────────────┘

Components:
	•	Frontend: Expo + TypeScript
	•	Backend: Supabase (DB + Auth + Storage)
	•	AI: OpenAI (budgeting, insights, explanations)
	•	RLS: Per-user secure data access
	•	Edge Functions: Secure AI + logic layer

⸻

🎨 Design System (to be created)

Located in /design/:
	•	Color palette
	•	Typography
	•	Layout grid
	•	Iconography
	•	UI components
	•	Example screens

Will be used across mobile & web.

⸻

🧑‍💻 Development Workflow

Branch naming:

feature/...
fix/...
docs/...

Pull Request flow:
	1.	Create branch
	2.	Commit your changes
	3.	Open PR
	4.	Review and merge

Rules:
	•	No direct commits to main except README updates
	•	Backend migrations must be versioned
	•	All AI prompts must be stored in /ai/ folder

⸻

📘 Documentation Structure

docs/
  ├─ product/
  │   ├─ roadmap.md
  │   ├─ user-personas.md
  │   └─ feature-specs/
  ├─ architecture/
  │   ├─ system-diagram.png
  │   ├─ db-schema.md
  │   └─ api-design.md
  ├─ design/
  │   ├─ color-system.md
  │   ├─ typography.md
  │   └─ components/
  ├─ backend/
  │   ├─ rls-policies.md
  │   ├─ migrations/
  │   └─ edge-functions.md
  └─ ai/
      ├─ prompts/
      ├─ budget-coach.md
      ├─ categorizer.md
      └─ insight-engine.md


⸻

🤝 Contributing
	•	For internal team use
	•	Follow branching & PR guidelines
	•	All documentation must be clearly versioned

⸻

📄 License

Private documentation — not for public use.
Copyright © Fundament.
