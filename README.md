# .github

This repository contains community health files and organization-wide defaults for the [homeassistant-ai](https://github.com/homeassistant-ai) organization.

## Purpose

GitHub automatically applies the files in this repository to all repositories in the organization that don't have their own version. This provides consistent policies and guidelines across all projects.

## Files

- **[CONTRIBUTING.md](CONTRIBUTING.md)** - General contribution guidelines for all projects
- **[SECURITY.md](SECURITY.md)** - Security vulnerability reporting policy
- **[profile/README.md](profile/README.md)** - Organization profile displayed on our GitHub page

## Repository-Specific Files

Individual repositories may override these defaults with their own versions. For example:
- **ha-mcp** has a detailed CONTRIBUTING.md with setup instructions and tool development guidelines
- **skills** has specific quality standards and testing requirements

## What's NOT Here

We intentionally do not include:
- **Issue templates** - These are repository-specific and stay in individual repos
- **Pull request templates** - Each project has unique PR requirements
- **Workflow files** - CI/CD configurations are project-specific

## For Project Maintainers

To override a default file in your repository, simply add your own version of the file at the repository root. GitHub will use the repository-specific version instead of the organization default.

## Learn More

- [GitHub Community Health Files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Organization Profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)