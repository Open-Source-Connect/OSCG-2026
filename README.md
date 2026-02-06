# Open Source Connect Global (OSCG) ’26

![OSCG Banner](https://img.shields.io/badge/OSCG-2026-blueviolet?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

Welcome to the official **OSCG’26 Contributor Guidelines**. This repository is the central hub for our community-driven initiative designed to help you master open source by working on real-world projects.

---

## Table of Contents
- [Introduction](#introduction)
- [The OSCG Model](#understanding-the-oscg-contribution-model)
- [Discovering Projects](#discovering-projects)
- [Project Details](#project-details-page-explained)
- [Contribution Workflow](#contribution-workflow-detailed)
- [Quality Standards](#contribution-quality-standards)
- [Communication](#communication-guidelines)
- [Code of Conduct](#code-of-conduct)
- [Stay Connected](#stay-connected-with-oscg)

---

## Introduction

**Open Source Connect Global (OSCG)** is more than just a collaboration platform; it’s a global initiative to bridge the gap between learning and doing. We provide a structured environment where contributors, mentors, and project admins collaborate to build impactful software.

### Our Goals:
- **Fairness:** Create a transparent and consistent contribution process for everyone.
- **Quality:** Maintain high engineering standards across all OSCG projects.
- **Collaboration:** Foster respectful and effective mentorship and peer-to-peer learning.

---

## Understanding the OSCG Contribution Model

> **Note:** OSCG is NOT a hackathon. It is a journey.

We prioritize **sustainable contribution** over speed. We do not use "artificial difficulty" tags because real-world problems don't come with them. Instead, we evaluate work based on:
- **Clarity:** How well did you explain your changes?
- **Correctness:** Does the code work and follow best practices?
- **Usefulness:** Does it actually solve a project need?
- **Collaboration:** How did you handle feedback and discussion?

---

## Discovering Projects

All official projects are curated and listed on our centralized directory:

**Explore Projects:** [https://www.osconnect.org/projects](https://www.osconnect.org/projects)

### The Project Matrix (Common Stacks)
| Category | Tech Stack | Sample Projects |
| :--- | :--- | :--- |
| **Web Dev** | Frontend (React, Next.js), Backend (Node, Go) | Landing Pages, Dashboards |
| **Mobile** | Flutter, React Native | Community Apps, Utilities |
| **DevOps** | Docker, K8s, GitHub Actions | CI/CD Pipelines, Tooling |
| **AI/ML** | Python, TensorFlow, PyTorch | Data Analysis, Model Integration |

---

## Project Details Page Explained

When you click **View Details** on a project, you are entering its specific ecosystem. Pay close attention to:
- **GitHub Link:** The primary source code.
- **Live Demo:** See the project in action.
- **Admin Profile:** Know who is leading the project.
- **Expectations:** Every project has unique goals—read them carefully.

### Professionalism First:
- **Do NOT** message admins on LinkedIn for technical support.
- **Do NOT** ask "Can I work on this?" via DMs.
- **DO** use GitHub Issues and Discussions. LinkedIn is for professional networking (e.g., adding to your network *after* a successful contribution).

---

## Contribution Workflow (Detailed)

Follow these steps to ensure your PR is professional and merge-ready.

### Step 1: Deep Review
- Read the project `README.md` and `CONTRIBUTING.md`.
- Look at the Folder Structure and existing `PRs` to see the "vibe" of the code.

### Step 2: Fork the Repository
Click the **Fork** button on the top right. This creates your "sandbox" where you can safely experiment.

### Step 3: Clone Locally
```bash
git clone https://github.com/<your-username>/<project-name>.git
cd <project-name>
```

### Step 4: Sync with Upstream (Recommended)
Add the original repo as a remote to keep your code updated.
```bash
git remote add upstream https://github.com/original-owner/project-name.git
git fetch upstream
```

### Step 5: Feature Branching (Mandatory)
Never work on `main`. Create a descriptive branch.
- `feat/add-login-validation`
- `fix/header-overlap-mobile`
- `docs/update-install-guide`
```bash
git checkout -b feature/short-descriptive-name
```

### Step 6: Targeted Changes
- Keep PRs small. If you're fixing a bug, don't also "fix the spacing" in an unrelated file.
- Follow existing linting and styling rules.

### Step 7: Local Testing
Verify your changes. Run the test suite if available:
```bash
npm test  # or the equivalent for your stack
```

### Step 8: Meaningful Commits
```bash
git commit -m "feat: implement API validation for user signup"
```
*Explain what changed and why.*

### Step 9: Push & Pull Request
```bash
git push origin feature/short-descriptive-name
```
Open the PR on GitHub. Fill out the PR template accurately. Reference any issues it fixes using `Closes #123`.

---

## Contribution Quality Standards

### What We Love
- Clearly explained bug fixes.
- Performance optimizations with benchmarking.
- Comprehensive documentation updates.
- Modular, reusable code.

### What We Reject
- **Spam PRs:** Changing "a" to "the" in comments without reason.
- **Plagiarism:** Immediate removal for copied code.
- **Messy PRs:** Mixing five unrelated features into one PR.
- **Auto-generated code:** AI-written code without human oversight/refinement.

---

## Communication Guidelines

| Channel | Best For |
| :--- | :--- |
| **GitHub Issues** | Reporting bugs, proposing features, technical questions. |
| **PR Comments** | Code reviews, requested changes, implementation details. |
| **Discussions** | Open-ended brainstorming, community help. |

### Etiquette:
- Be patient. Maintainers are volunteers.
- Avoid tagging individuals repeatedly (@username).
- Provide context (OS version, logs, screenshots).

---

## Code of Conduct

All participants must adhere to the highest standards of professional conduct.

### Zero Tolerance for:
- Harassment or discrimination of any kind.
- Toxic, aggressive, or dismissive language.
- Manipulation of metrics (e.g., fake stars or PRs).
- Misrepresenting work that isn't yours.

---

## Support & Help

Reached a dead end? We are here to help.

**Official Support:** [hello@osconnect.org](mailto:hello@osconnect.org)

**Please include in your email:**
- Your GitHub Username
- Project Name & Link
- A clear description of the issue (with screenshots if possible).

---

## Final Reminder
Open source is about **impact** and **ownership**. When you contribute to OSCG, you aren't just a "user"—you are a part of the team. Take pride in your work, be helpful to others, and let's build something great together.

---

## Stay Connected with OSCG

| Platform | Channel |
| :--- | :--- |
| **Website** | [osconnect.org](https://osconnect.org/) |
| **LinkedIn** | [Open Source Connect](https://www.linkedin.com/company/open-source-connect) |
| **Instagram** | [@osconnect.official](https://www.instagram.com/osconnect.official/) |
| **GitHub** | [Open-Source-Connect](https://github.com/open-source-connect) |
| **YouTube** | [OSC YouTube](https://www.youtube.com/@open-source-connect) |

---
*Built by the Open Source Connect Global Community.*
