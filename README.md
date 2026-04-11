# GitHub Learning Workshop

A hands-on web application project designed to teach GitHub features from beginner to advanced levels. This repository serves as a learning laboratory where you'll progressively master Git and GitHub through practical exercises.

## What You'll Learn

This project is structured in **progressive phases** to build your GitHub expertise:

### Phase 0: Foundation Setup ✅
- Repository creation and initialization
- Git configuration (user.name, user.email)
- Understanding `.gitignore`, `LICENSE`, and `README.md`
- Basic Git workflow (init, add, commit, push, pull)
- Viewing history with `git log` and `git diff`

### Phase 1: Core Collaboration ✅
- Branching strategies and naming conventions
- Pull Requests (PRs) and code review workflow
- Issues, milestones, and labels
- GitHub Projects (Kanban boards)
- PR and issue templates

### Phase 2: GitHub Automation
- GitHub Actions (CI/CD pipelines)
- Automated testing and linting
- Deployment to GitHub Pages
- Branch protection rules
- Dependabot for dependencies

### Phase 3: Advanced Git Workflows
- Interactive rebase `git rebase -i`
- Rebasing vs merging
- Git hooks with Husky
- Conventional commits with Commitlint
- Conflict resolution strategies
- Git reflog for recovery

### Phase 4: Expert GitHub Features
- GitHub REST & GraphQL API
- Security features (vulnerability alerts, Dependabot)
- GitHub Packages (npm, Docker)
- Repository templates
- GitHub Codespaces
- GitHub Copilot integration

## Project Structure

```
github-learning-workshop/
├── .github/
│   ├── workflows/          # GitHub Actions CI/CD
│   └── ISSUE_TEMPLATE/     # Issue templates
├── src/                    # Application source code
├── public/                 # Static assets
├── docs/                   # Additional documentation
├── .gitignore             # Git ignore patterns
├── LICENSE                # MIT License
├── README.md              # This file
└── package.json           # Node.js configuration
```

## Prerequisites

Before starting, ensure you have:

- **Git** installed on your machine
  ```bash
  git --version
  ```
- **GitHub account** (sign up at https://github.com)
- **Code editor** (VS Code recommended)
- **Node.js** (v16 or higher) - for running the web app
  ```bash
  node --version
  ```

## Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/christiantan47/github-learning-workshop.git
cd github-learning-workshop
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run locally

```bash
npm run dev
```

### 4. Open in browser

Navigate to `http://localhost:3000`

## Roadmap

- [x] Phase 0: Foundation Setup
- [ ] Phase 1: Core Collaboration
- [ ] Phase 2: GitHub Automation
- [ ] Phase 3: Advanced Workflows
- [ ] Phase 4: Expert Features

See [Issues](https://github.com/christiantan47/github-learning-workshop/issues) for detailed tasks in each phase.

## Contributing

This is a learning project! Contributions, issues, and feature requests are welcome. See [CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines.

## License

This project is [MIT licensed](LICENSE).

## Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub Documentation](https://docs.github.com)
- [GitHub Learning Lab](https://lab.github.com)
- [Learn Git Branching](https://learngitbranching.js.org)

---

**Happy Learning!** 🚀

Made with ❤️ for GitHub learners