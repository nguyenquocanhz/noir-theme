---
name: noir-workflow-guidelines
description: Workspace-specific guidelines for Noir Theme development, including git metadata and commit conventions.
---

# Noir Theme Development & Workflow Guidelines

This document contains rules and instructions for coding assistants working on the Noir Theme project in this workspace.

## 👥 Git Configuration
Always configure and commit using these developer details:
- **Git Name:** `nguyenquocanhz`
- **Git Email:** `cuibapvh4@gmail.com`

Before making commits, check if git local configuration is set. If not, run:
```bash
git config --local user.name "nguyenquocanhz"
git config --local user.email "cuibapvh4@gmail.com"
```

## 📝 Commit Conventions (Commitlint)
Commits in this repository must strictly follow Conventional Commits (commitlint) standards.

### Format
`<type>(<scope>): <description>` (scope is optional)

### Common Types:
- `feat`: A new feature (e.g., adding a new theme color variant)
- `fix`: A bug fix
- `docs`: Documentation changes only (e.g., updating README or LICENSE)
- `style`: Changes that do not affect the meaning of the code (formatting, white-space, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools and libraries (e.g., package.json updates)

### Examples:
- `feat: rename theme to noir`
- `docs: add gplv3 license`
- `chore: update package.json repository url`

## ⚖️ Project License
- This project is licensed under the GNU General Public License v3.0 (GPL-3.0). All source files and contributions must comply with GPL-3.0.
