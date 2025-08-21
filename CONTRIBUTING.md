# Contributing Guide

Thank you for your interest in contributing! 🎉  
This document will guide you through the setup and contribution process.

---

## 🛠 Development Setup

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/notebook.git
cd notebook
``` 

### 2. Set up Python virtual environment
```bash
python -m venv venv
source venv/Scripts/activate   # Windows
# or
source venv/bin/activate       # macOS/Linux
``` 

### 3. Install dependencies
```bash
npm install --legacy-peer-deps
npm install -g lerna yarn
``` 

### 4. Build the project
```bash
npm run build
``` 

### 5. Run Jupyter Notebook (for development)
```bash
jupyter notebook --NotebookApp.allow_origin='*' --debug
``` 

### 🧪 Running Tests
```bash
npm test
``` 
### 🔍 Lint Your Code
```bash
npm run lint
``` 


### Auto-fix common issues:

```bash
npm run lint:fix
``` 

💡 Contribution Guidelines

Use feature branches (never commit directly to `main`).

Write clear commit messages (follow Conventional Commits).

Keep PRs small and focused.

Ensure all tests pass before submitting a PR.

Update documentation when needed.


## 📜 Code of Conduct

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions.

