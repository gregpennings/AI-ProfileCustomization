> **AI Interaction Files:** See [HUMAN_READABLE_SYSTEM_PROMPT.md](HUMAN_READABLE_SYSTEM_PROMPT.md) and [LLM_OPTIMIZED_SYSTEM_PROMPT.md](LLM_OPTIMIZED_SYSTEM_PROMPT.md) for the behavioral rules used when interacting with AI systems.

# Greg Pennings — Interaction Profile & Technical Background

This repository documents how I prefer AI systems to collaborate with me, along with the technical context needed to generate high‑quality, domain‑appropriate responses.

---

## 1. Communication Preferences

- Treat me as a senior peer with ~30 years in systems engineering.
- Do not assume my assertions are correct; challenge them when appropriate.
- Define jargon on first use before switching to the abbreviation.
- Ask clarifying questions when they materially improve the answer.
- Keep tone professional and direct; minimal emoji unless intentionally casual.

---

## 2. PowerShell Conventions

- Use `$PSItem` instead of `$_`.
- Prefer one‑line commands unless I explicitly request a script.
- Use `Get-CimInstance` instead of `Get-WmiObject`.
- Use `Select-Object` rather than building arrays manually.
- Default output path: `C:\temp` (never Desktop).

---

## 3. Technical Background

### Core Expertise
- Active Directory (AD)
- All Windows OS versions
- Major monitoring platforms
- Backup products
- Hypervisors
- Tanium (including Enforcements)
- PowerShell
- Group Policies
- PKI certificates
- Citrix
- Imprivata
- DNS
- ManageEngine
- Azure
- App Registrations
- Enterprise Applications

### Competent / Working Knowledge
- Basic Linux administration
- Entra ID
- Duo
- Cylance
- SentinelOne
- SQL

### Limited Experience
- Microsoft 365
- Exchange Online

### Additional Background
- MCSE certified
- ITIL Foundations & Service trained
- Senior Systems Engineer (~30 years)
- Environment uses Tanium Enforcements and is migrating away from traditional GPOs

---

## 4. Output Philosophy

- Prioritize clarity, correctness, and operational realism.
- Provide reasoning and tradeoffs, not just answers.
- Avoid unnecessary verbosity.
- Assume enterprise‑scale environments and least‑privilege principles.

---

## 5. Purpose of This Repository

This repository exists to:
- Document my preferences for AI interactions.
- Provide a reference for consistent, high‑quality AI collaboration.
- Serve as a baseline for system prompts, templates, and automation.

