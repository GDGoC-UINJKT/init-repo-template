# 🚀 init-repo-template

A professional and opinionated GitHub repository template to improve **consistency**, **collaboration**, and long-term maintainability for open-source or private projects.

> 📦 Ready-to-clone setup for teams who care about clean Git history and a clear collaboration flow.

Related article:
[https://dev.to/oskhar/commitizen-making-git-commits-the-right-way-g70](https://dev.to/oskhar/commitizen-making-git-commits-the-right-way-g70)

## Why this template?

This template helps you avoid:

- inconsistent commit messages
- unclear contribution rules
- repetitive repo setup across projects

It’s designed to be **reusable**, **team-friendly**, and **tool-agnostic** (not tied to Node.js projects).

## What’s included ✨

- `.czrc` for Commitizen-based interactive commits
- Conventional Commits & semantic versioning support
- Clear collaboration rules in `collaboration_guide.md`
- GitHub-ready structure (`.github`, docs-friendly layout)

## Getting started

### 1. Clone the template

```bash
git clone https://github.com/your-username/init-repo-template.git your-project-name
cd your-project-name
```

### 2. Read the collaboration guide

Before committing anything, read:

- `collaboration_guide.md`

It explains commit rules, branching, PR flow, and review etiquette.

### 3. Initialize your repository

```bash
git init
git remote add origin <your-new-repo-url>
npm install -g commitizen cz-git
```

> 💡 `.czrc` is already included — you can use `git cz` immediately.

## Commit workflow 🧠

This template uses **Commitizen** to keep commit messages consistent and meaningful.

To commit:

```bash
git add .
git cz
```

Follow the interactive prompt and let the tool guide you.

## Collaboration rules 🤝

- Do not commit directly to `main` (except initial setup)
- Always follow the commit convention
- Open pull requests with clear intent and scope

All details are documented in `collaboration_guide.md`.

## Suitable for

- Open-source repositories
- Internal company projects
- Monorepo bootstrapping
- Teams learning proper Git practices

## License

MIT — free to use, modify, and adapt.

## Tip 🧩

Clone this template and make your first commit with:

```bash
git cz
```

You’ll immediately notice a cleaner, more structured workflow.
