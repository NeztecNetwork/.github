# .github

This directory contains GitHub-specific configuration files, templates, and workflows for the NeztecNetwork repository.

## Contents

### Issue Templates
Templates that help maintain consistency and clarity when creating new issues:
- **Feature Request**: Template for proposing new features
- **Bug Report**: Template for reporting bugs
- **Documentation**: Template for documentation improvements

### Pull Request Templates
Guidelines and templates for submitting pull requests to ensure quality and consistency.

### GitHub Workflows
Automated CI/CD workflows that run on specific events:
- **Tests**: Automated testing on push and pull requests
- **Build**: Build verification workflows
- **Deploy**: Deployment automation
- **Code Quality**: Linting and code analysis checks

### Configuration Files
- **CODEOWNERS**: Defines code ownership and required reviewers
- **dependabot.yml**: Automated dependency update configuration

## Purpose

This directory is used to:
1. **Standardize Communication**: Issue and PR templates ensure clear, consistent communication
2. **Automate Workflows**: GitHub Actions workflows automate testing, building, and deployment
3. **Enforce Quality**: Code review assignments and automated checks maintain code quality
4. **Security**: Dependency management and vulnerability scanning

## How to Use

### Creating an Issue
When creating a new issue, GitHub will automatically offer relevant templates based on the issue type.

### Creating a Pull Request
When opening a PR, the template will guide contributors through the submission process.

### Running Workflows
Workflows automatically trigger on:
- Push to main/develop branches
- Pull requests
- Scheduled times
- Manual dispatch (if configured)

## Contributing

When modifying templates or workflows:
1. Keep templates clear and concise
2. Update CODEOWNERS if team structure changes
3. Test workflow changes in a feature branch
4. Document any new workflows in this README

## Resources

- [GitHub Documentation](https://docs.github.com/en/github/building-a-strong-community)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [NeztecNetwork Main Repository](../README.md)