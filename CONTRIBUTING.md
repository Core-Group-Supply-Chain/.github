# Contributing Guide

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR-USERNAME/repo-name.git`
3. Create a branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Stage: 'git add <filename/s>'
7. Commit: `git commit -m "feat: add new feature"`
8. Push: `git push origin feature/your-feature-name`
9. Open a Pull Request

## Development Setup
```bash
# Clone the repository
git clone https://github.com/org-name/repo-name.git
cd repo-name

# Install dependencies
poetry install #npm install or yarn install, pip install -r requirements.txt, etc.

# Run tests directly using poetry and pytest
poetry run pytest
poetry run python -m pytest
poetry run python -m unittest

```

## Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code formatting
- `refactor:` Code restructuring
- `test:` Adding tests
- `chore:` Maintenance tasks
