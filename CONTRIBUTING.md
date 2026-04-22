# Contributing to GitHub Profile Trophy 🏆

First off, thank you for considering contributing to **GitHub Profile Trophy**! It's people like you who make this tool better for everyone. This project is maintained with passion by **Rachit Kakkad**.

By participating in this project, you agree to abide by its terms and maintain a respectful environment.

---

## 🗺️ Roadmap to Contributing

### 1. Reporting Bugs 🐛
If you find a bug, please search existing issues to see if it has already been reported. If not, open a new issue and include:
*   A clear and descriptive title.
*   Steps to reproduce the problem.
*   Expected vs. actual behavior.
*   Screenshots if applicable.

### 2. Suggesting Enhancements ✨
Have an idea for a new trophy or theme? We'd love to hear it!
*   Check if the feature has already been suggested.
*   Explain why this enhancement would be useful to most users.

### 3. Your First Code Contribution 💻
Unsure where to begin? Look for `good first issue` labels.

---

## 🛠️ Development Setup

This project is built with **Deno**. Follow these steps to get your local environment ready:

### Prerequisites
*   [Deno](https://deno.land/) (v1.36.1 or higher)
*   A GitHub Personal Access Token (with `repo` scope)

### Step-by-Step Setup
1.  **Fork and Clone:**
    ```bash
    git clone https://github.com/Rachit-Kakkad1/github-profile-trophy.git
    cd github-profile-trophy
    ```
2.  **Environment Variables:**
    Create a `.env` file in the root directory:
    ```properties
    GITHUB_TOKEN1=your_token_here
    ```
3.  **Run the Server:**
    ```bash
    deno task start
    ```
    Visit `http://localhost:8080/?username=Rachit-Kakkad1` to see it in action!

---

## 📜 Style Guidelines

To keep the codebase clean and consistent, please follow these rules before submitting a Pull Request:

### 1. Formatting & Linting
We use Deno's built-in tools. Ensure your code is polished:
```bash
deno task format  # Format your code
deno task lint    # Check for linting errors
```

### 2. Testing
Never skip testing! Add tests for new features and ensure existing ones pass:
```bash
deno task test
```

### 3. Commit Messages
*   Use the present tense ("Add feature" not "Added feature").
*   Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
*   Limit the first line to 72 characters or less.

---

## 🚀 The Pull Request Process

1.  Create a new branch for your feature or fix: `git checkout -b feature/amazing-feature`.
2.  Commit your changes with clear messages.
3.  Push to your fork and submit a Pull Request.
4.  Wait for review! **Rachit Kakkad** reviews all PRs to ensure they meet project standards.

---

## ⚖️ License
By contributing, you agree that your contributions will be licensed under the project's **MIT License**.

---

<div align="center">
  <p>Thank you for building the future of GitHub profiles with us!</p>
  <b>Maintained by <a href="https://github.com/Rachit-Kakkad1">Rachit Kakkad</a></b>
</div>
