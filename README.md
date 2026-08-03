# 🚀 GitHub Actions CI Workflow

A simple GitHub Actions workflow that runs automatically on every push and pull request to the `main` branch.

## ✨ Features

- ✅ Trigger on `push` to `main`
- ✅ Trigger on `pull_request` to `main`
- ✅ Manual workflow execution (`workflow_dispatch`)
- ✅ Checks out the repository
- ✅ Runs sample shell commands

## 📁 Project Structure

```text
.
└── .github/
    └── workflows/
        └── ci.yml
```

## 🚀 How It Works

```text
Push / Pull Request
        │
        ▼
GitHub Actions Runner
        │
        ▼
Checkout Repository
        │
        ▼
Run Workflow Steps
        │
        ▼
Workflow Complete ✅
```

## 📄 License

This project is licensed under the MIT License.
