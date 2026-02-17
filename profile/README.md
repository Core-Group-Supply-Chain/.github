## Welcome to Core Group Supply Chain

## Table of Contents
- [Repository Structure](#repository-structure)
- [Branch Strategy](#branch-strategy)

## General Repository Structure

```
Core-Group-Supply-Chain/
├── project-name/
│   ├── src/
│   ├── tests/
│   ├── docs/
│   ├── .github/
│   │   ├── workflows/
│   ├── README.md
│   └── CHANGELOG.md
│   └── requirements.txt or pyproject.toml

```
#### The README.md
- Project Title & Description: What does this actually do?
- Prerequisites: What version of Python? What OS? (e.g., "Python 3.10+").
- Installation: Clear, step-by-step commands (e.g., poetry install or pip install -r requirements.txt).

#### Dependency document
- requirements.txt or pyproject.toml
- Ensures the environment is identical across machines.

### Repository Naming Convention
- Use lowercase with hyphens: `project-name`
- Be descriptive and concise

## Branch Strategy

### Main Branches
- **`main`** - Production-ready code, protected branch
- **`develop`** - Integration branch for features, protected branch

### Branch Rules
1. Always branch from `develop` for new features
2. Hotfixes branch from `main` and merge to both `main` and `develop`
3. Delete branches after merging

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
