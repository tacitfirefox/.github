# .github Repository

This repository contains community health files, configuration, and shared templates for all repositories in this organization.

## Purpose

The `.github` repository is a special repository recognized by GitHub that stores **default community files** and **organization-wide configuration**.  
These files are automatically used by other repositories in the organization if they don’t have their own copies.

## Contents

| File / Directory | Purpose |
| ---------------- | ------- |
| **CODE_OF_CONDUCT.md** | Sets the expected behavior for all contributors and community members. |
| **CONTRIBUTING.md** | Provides guidelines for contributing to repositories. |
| **FUNDING.yml** | Lists ways to financially support the project or organization. |
| **ISSUE_TEMPLATE/** | Contains templates for creating new GitHub issues. |
| **PULL_REQUEST_TEMPLATE/** | Contains templates for creating pull requests. |
| **SECURITY.md** | Describes security policies, including how to report vulnerabilities. |
| **SUPPORT.md** | Explains where and how to get help with the project. |
| **workflows/** | Contains GitHub Actions workflows for automation. |
| **dependabot.yml** | Configures Dependabot to keep dependencies up to date. |

## How GitHub Uses This Repository

- Files in `.github/` of this repository are **inherited** by other repositories in the same organization.
- If a repository contains its own file (e.g., `CONTRIBUTING.md`), that local file takes priority.
- Templates from this repository appear in the UI when creating issues or pull requests.

## Adding or Updating Templates

1. Create or modify the template file in this repository.
2. Commit and push changes to the default branch.
3. GitHub automatically applies the updates to all repositories that do not override the file.

## Best Practices

- Keep templates **generic** so they can be applied to all projects.
- Use **placeholders** (e.g., `[PROJECT_NAME]`) where project-specific values might differ.
- Keep all Markdown files formatted for readability and accessibility.

## References

- [GitHub Docs: Creating a default community health file](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [GitHub Docs: .github repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-the-github-repository)

## Notes

This file was generated using Chat-GPT 5.

---
© [YEAR] [ORGANIZATION NAME]. Licensed under [LICENSE].
