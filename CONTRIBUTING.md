# Contributing to The Skull Network

First off — thanks for wanting to contribute 💀 Whether it's a bug fix, a new feature, a doc improvement, or a whole new project idea, this guide covers how contributions work across all repos in the **TheSkullNetwork** organization.

## Table of Contents

- [Before You Start](#before-you-start)
- [How to Contribute](#how-to-contribute)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Code Style](#code-style)
- [Reporting Bugs](#reporting-bugs)
- [Proposing New Projects or Major Features](#proposing-new-projects-or-major-features)
- [Code of Conduct](#code-of-conduct)
- [Ethical Use Reminder](#ethical-use-reminder)
- [Licensing](#licensing)
- [Repo-Specific Notes](#repo-specific-notes)

## Before You Start

- Check existing issues and open PRs in the repo to avoid duplicate work.
- For small fixes (typos, minor bugs), feel free to jump straight to a PR.
- For anything bigger — a new feature, a new tool, or a new repo idea — open an issue first, or drop a message in **#contributor-discussions** (`#⫸╽ꜱᴛᴀꜰꜰ-ᴅɪꜱᴄᴜꜱꜱɪᴏɴꜱ` on Discord) so we can align before you put in the work.

## How to Contribute

1. **Fork** the repository you want to contribute to.
2. **Clone** your fork locally:
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
3. **Create a branch** for your change:
   ```
   git checkout -b fix/short-description
   ```
   Use a prefix that describes the change: `fix/`, `feature/`, `docs/`, `refactor/`.
4. **Make your changes**, following the code style and structure already used in the repo.
5. **Test your changes** where applicable — don't submit code you haven't run.
6. **Commit** with a clear message:
   ```
   git commit -m "fix: correct timeout handling in scraper"
   ```
7. **Push** to your fork and **open a Pull Request** against the repo's default branch.

## Pull Request Guidelines

- Keep PRs focused — one fix or feature per PR is easier to review than a bundle of unrelated changes.
- Describe **what** changed and **why** in the PR description. Link any related issue.
- Include before/after behavior, screenshots, or sample output if it helps reviewers.
- Be responsive to review comments — we aim to review PRs promptly and will keep you updated on status.
- Make sure your branch is up to date with the target branch before requesting a final review.

## Code Style

- Match the existing style/conventions of the repo you're contributing to (naming, formatting, structure).
- Keep functions and scripts readable — comments are welcome, especially for anything security- or OSINT-related where intent matters.
- Avoid introducing unnecessary dependencies. If a new dependency is genuinely needed, explain why in the PR.

## Reporting Bugs

Use GitHub Issues for **non-security** bugs. Include:
- Repo and version/commit
- Steps to reproduce
- Expected vs actual behavior
- Environment details (OS, language version, etc.) if relevant

**Found a security vulnerability?** Do not open a public issue — see [SECURITY.md](https://github.com/TheSkullNetwork/.github/blob/main/SECURITY.md) for private reporting instructions.

## Proposing New Projects or Major Features

Got an idea for a new tool or a major addition to an existing one? We'd rather hear about it early:

- Post the idea in **##⫸╽ᴅɪꜱᴄᴜꜱꜱɪᴏɴꜱ** on [Discord](https://discord.gg/7tSPQjtkhz), or
- Open a Discussion in the relevant repo

This helps avoid duplicated effort and makes sure the idea fits the direction of the project/org before significant work goes into it.

## Code of Conduct

Be respectful, be constructive, and remember there's a person on the other end of every issue and PR. We're here to build and learn together — offensive security research and tooling is welcome, but harassment, malicious intent toward real targets, or abuse of shared tools is not.

## Ethical Use Reminder

Several of our projects touch OSINT, recon, and security tooling. Contributors and users are expected to use and build these tools **legally and ethically** — for authorized research, learning, and defensive purposes. Contributions that primarily serve malicious or illegal use cases will not be accepted.

## Licensing

By submitting a contribution (code, docs, or otherwise), you agree that it will be licensed under the same license as the repository you're contributing to. Check the repo's `LICENSE` file if you're unsure which license applies.

## Repo-Specific Notes

This file covers the org-wide default. If a specific repository has additional setup steps, testing requirements, or stricter rules (e.g. signed commits), that repo will include its own `CONTRIBUTING.md`, which takes precedence over this one for that repo only.

---

*Operating securely. Coding efficiently.* — The Skull Network 💀
