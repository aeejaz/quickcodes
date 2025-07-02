# Contributing to QuickCodes

Thank you for your interest in contributing to **QuickCodes**! We welcome contributions from everyone, whether you're fixing bugs, adding new code snippets, improving documentation, or suggesting features. This guide outlines the steps to contribute effectively.

**TL;DR**: Fork the repo, clone it, create a branch (`add/your-snippet` or `fix/issue-description`), make your changes, commit with clear messages, and submit a Pull Request (PR) to the `main` branch.

---

## Contributor's Guide

We value feedback, bug reports, and pull requests. If you’re new to contributing or need help, don’t hesitate to ask! Check out [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github) for a great starting point.

---

## Getting Started

### Forking the Project

1. **Fork the Repository**:
   - Go to the [QuickCodes repository](https://github.com/aeejaz/quickcodes).
   - Click the **Fork** button in the top-right corner to create a copy under your GitHub account (`https://github.com/aeejaz/quickcodes`).

2. **Clone Your Fork**:
   - Open a terminal in your project directory.
   - Clone your fork:
     ```bash
     git clone https://github.com/aeejaz/quickcodes.git
     ```
     Replace `aeejaz` with your GitHub username.

3. **Set Up Upstream**:
   - Navigate to the cloned directory:
     ```bash
     cd quickcodes
     ```
   - Add the original repository as an upstream remote:
     ```bash
     git remote add upstream https://github.com/aeejaz/quickcodes.git
     ```

---

## Keeping Your Fork Updated

To ensure your fork is current with the main repository:

1. **Switch to the `main` Branch**:
   ```bash
   git checkout main
   ```
   Verify with `git status` that you're on `main` and your working directory is clean.

2. **Pull Upstream Changes**:
   ```bash
   git pull --rebase upstream main
   ```
   This syncs your fork with the latest changes from the main repository.

3. **Push to Your Fork**:
   ```bash
   git push origin main
   ```

---

## Making Changes

1. **Create a New Branch**:
   - Use a descriptive branch name, e.g., `add/your-snippet-name` or `fix/bug-description`:
     ```bash
     git checkout -b add/your-snippet-name
     ```

2. **Add Your Contribution**:
   - Add your code snippet, tool, or fix to the appropriate directory.
   - Ensure snippets are organized alphabetically or follow the project’s structure (check the `README.md` or project docs).
   - Update any relevant documentation (e.g., `README.md`) if needed.

3. **Stage and Commit Changes**:
   - Check your changes:
     ```bash
     git status
     ```
   - Stage files:
     ```bash
     git add .
     ```
     Or stage specific files: `git add path/to/file`.
   - Commit with a clear, present-tense message:
     ```bash
     git commit -m "Add snippet for [snippet-description]"
     ```
     Example: `git commit -m "Add regex validator for email addresses"`.
     See [How to Write Better Git Commit Messages](https://chris.beams.io/posts/git-commit/) for tips.

4. **Push to Your Fork**:
   ```bash
   git push origin add/your-snippet-name
   ```

---

## Creating a Pull Request

1. **Open a Pull Request**:
   - Go to your fork on GitHub (`https://github.com/aeejaz/quickcodes`).
   - Click **Compare & pull request** on the branch you pushed.
   - Set the **base repository** to `aeejaz/quickcodes` and **base branch** to `main`.

2. **Write a Descriptive PR**:
   - **Title**: Summarize your changes (e.g., `Add snippet for email validation`).
   - **Description**: Explain what you added or fixed, why it’s useful, and any relevant details. Reference issues if applicable (e.g., `Fixes #123`).
   - **Checklist** (optional): Confirm you’ve followed guidelines (e.g., tested changes, updated docs).

3. **Submit the PR**:
   - Ensure your PR is against the `main` branch of the original repository.
   - Await feedback from maintainers. Be responsive to requests for changes.

---

## Important Guidelines

- **Always Work on a Branch**: Never edit directly on the `main` branch of your fork. This keeps your fork clean and allows easy recovery if a PR is rejected.
- **Keep Commits Focused**: Make small, logical commits for easier review. Use `git commit --amend` to update a previous commit if needed.
- **Follow Project Structure**: Add snippets alphabetically or as per the project’s conventions. Check existing files for examples.
- **Test Your Changes**: Ensure your code works and doesn’t break existing functionality. Include tests if the project uses them.
- **Be Respectful**: Follow the [Code of Conduct](CODE_OF_CONDUCT.md) (if available) and engage constructively with the community.

---

## If Your PR Needs Changes

If maintainers request changes:
1. Make updates on the same branch locally.
2. Commit and push changes:
   ```bash
   git commit -m "Address feedback: [change-description]"
   git push origin add/your-snippet-name
   ```
3. The PR will update automatically with your new commits.

---

## After Your PR is Accepted

- **Celebrate**: Your contribution is now part of QuickCodes!
- **Clean Up**: Delete your branch to keep your fork tidy:
  - Locally: `git branch -D add/your-snippet-name`
  - On GitHub: Use the “Delete branch” button on the PR page.

---

## Alternative Contribution Methods

If you’re not comfortable with Git, you can:
- **Edit via GitHub Interface**: Make changes directly in your fork on GitHub and create a PR from the web interface. Note: This is less flexible for complex changes.
- **Open an Issue**: Suggest new snippets, report bugs, or propose features via the [Issues](https://github.com/aeejaz/quickcodes/issues) tab.

---

## Need Help?

- **Ask Questions**: Open an issue or join the community (if available, e.g., Discord or Discussions).
- **Resources**:
  - [GitHub’s Guide to Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
  - [Understanding Git Branches](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)

We’re excited to see your contributions to QuickCodes! 🚀

---
