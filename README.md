# 🛠 Developer Onboarding Guide

Welcome to the team! 🎉  
We're excited to have you join us at **[Agency Name]**. This document outlines our coding and collaboration practices to help you get up to speed quickly.

---

## 📦 General Principles

- **Write code that you’re proud of** — prioritize readability, maintainability, and performance.
- **Think in systems** — code should be modular and scalable.
- **Leave things better than you found them** — small improvements are encouraged.

---

## 💻 Coding Guidelines

- **Languages & Tools**: Follow the tech stack and conventions defined per project.
- **Formatting**: Use Prettier and ESLint with the shared config.
- **Naming**: Be descriptive and consistent. Use `camelCase`, `PascalCase`, or `snake_case` as appropriate.
- **Comments**: Keep them minimal and useful. Use `// TODO: your-name` for future improvements.
- **Security**: Never commit secrets, API keys, or credentials. Use `.env` and ensure it's in `.gitignore`.

---

## 🧬 Git Best Practices

- **Use feature branches**  
  Format: `feature/your-name/short-description`

- **Commit Often, Meaningfully**  
  One logical change per commit. Use:
    - feat: add login validation
    - fix: correct dashboard loading error
    - chore: update dependencies


- **Rebase Before Merging**  
Clean your history with `git rebase -i` and squash fixups.

- **Pull Request Checklist**:
- [ ] Code is linted and tested
- [ ] PR title and body are descriptive
- [ ] Relevant issue or task is linked
- [ ] PR is under ~300 lines if possible

---

## 🔍 Code Review Process

- **As a Reviewer**:
- Be kind, constructive, and specific
- Ask clarifying questions
- Spot edge cases, missed validations, and performance issues

- **As a Submitter**:
- Don’t take feedback personally
- Ask questions if unclear
- Justify your decisions when needed

---

## 🧠 Knowledge Sharing

- Document anything valuable you learn — in Notion, project README, or internal wiki
- Use reusable utilities/components wherever applicable
- Ask in public channels so others benefit from the discussion

---

## 🔊 Communication Guidelines

- Post regular updates (daily/weekly depending on the project)
- Don’t block silently — ask early
- Use threads in Slack, tag responsibly
- Respect working hours and time zones

---

## ✅ Onboarding Checklist

- [ ] Setup your dev environment (see project README)
- [ ] Get access to GitHub, Slack, Notion, etc.
- [ ] Clone a project and create a test PR
- [ ] Read a few current PRs to understand expectations
- [ ] Say hi in the Slack group! 😊

---

Welcome again, and let’s build something great together! 🚀
