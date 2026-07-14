# Contributing to FinCore

First of all, thank you for considering contributing to FinCore.

Whether you're fixing a typo, improving documentation, reporting bugs, proposing new ideas, or implementing major features, your contributions are appreciated.

Our goal is to build a world-class open-source financial infrastructure framework that developers and organizations can trust in production.

---

# Our Philosophy

Before writing any code, please read:

- [Project Philosophy](PROJECT_PHILOSOPHY.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Security Policy](SECURITY.md)

FinCore values:

- Quality over quantity
- Simplicity over unnecessary complexity
- Security by default
- Performance by design
- Backward compatibility whenever possible
- Clear documentation
- Long-term maintainability

---

# Ways to Contribute

You can contribute by:

- Reporting bugs
- Improving documentation
- Fixing issues
- Adding tests
- Improving performance
- Reviewing pull requests
- Proposing new modules
- Improving developer experience
- Enhancing security
- Creating examples
- Writing tutorials

Not every contribution needs to involve writing code.

---

# Before You Start

Before beginning work on a feature:

1. Search existing Issues.
2. Search existing Pull Requests.
3. Open a discussion if the feature is large.
4. Wait for feedback before implementing major architectural changes.

This helps avoid duplicated effort.

---

# Development Workflow

We follow a GitHub Flow inspired workflow.

```
main
│
├── develop
│
├── feature/...
├── bugfix/...
├── hotfix/...
└── release/...
```

Never commit directly to `main`.

All contributions must go through Pull Requests.

---

# Branch Naming

Use descriptive branch names.

Examples:

```
feature/ledger-posting-engine

feature/multi-currency

bugfix/jwt-validation

bugfix/null-pointer

hotfix/security-patch

release/v1.2.0
```

---

# Coding Standards

Please follow the project's coding standards.

General guidelines:

- Keep methods small.
- Prefer composition over inheritance.
- Write readable code.
- Avoid unnecessary abstractions.
- Avoid premature optimization.
- Remove dead code.
- Document public APIs.

---

# Java Standards

- Use Java 25+
- Follow standard Java naming conventions
- Prefer immutable objects
- Use records where appropriate
- Use sealed classes when beneficial
- Favor constructor injection
- Avoid field injection

---

# Spring Standards

- Constructor injection only
- No circular dependencies
- Modular architecture
- Stateless services whenever possible
- Configuration externalized
- Secure defaults

---

# Documentation

If your Pull Request introduces:

- a new module
- a public API
- configuration changes
- architecture changes

please update the relevant documentation.

Documentation is considered part of the feature.

---

# Testing Requirements

Every Pull Request should include appropriate tests.

Examples:

- Unit tests
- Integration tests
- Architecture tests
- Security tests
- Regression tests

New features should not reduce existing test coverage.

---

# Commit Messages

Use meaningful commit messages.

Examples:

```
feat(ledger): add posting engine

fix(auth): validate expired refresh tokens

docs(readme): update installation guide

test(core): improve journal validation tests

refactor(cache): simplify eviction logic
```

---

# Pull Request Checklist

Before submitting a Pull Request, ensure that:

- [ ] Code builds successfully
- [ ] Tests pass
- [ ] Documentation is updated
- [ ] No unnecessary files are included
- [ ] No secrets or credentials are committed
- [ ] Commit messages follow project conventions

---

# Code Review

All Pull Requests will be reviewed for:

- Correctness
- Security
- Maintainability
- Performance
- Documentation
- Test coverage
- Architectural consistency

Review feedback is intended to improve the project, not criticize contributors.

---

# Reporting Bugs

Please include:

- Operating System
- Java version
- Framework version
- Steps to reproduce
- Expected behavior
- Actual behavior
- Stack traces (if available)

The more detail you provide, the faster we can investigate.

---

# Feature Requests

When proposing a feature, explain:

- The problem
- Why it matters
- Proposed solution
- Alternatives considered
- Potential impact

Features should align with the project's philosophy and long-term vision.

---

# Security Issues

Please **do not** open public issues for security vulnerabilities.

Instead, follow the instructions in the project's `SECURITY.md`.

Responsible disclosure helps protect everyone.

---

# Contributor License Agreement (CLA)

Contributors may be asked to sign the project's Contributor License Agreement (CLA) before significant contributions can be merged.

This ensures the project can continue to evolve under its open-source license while protecting both contributors and maintainers.

---

# Licensing

By contributing to FinCore, you agree that your contributions will be licensed under the same license as the project.

---

# Recognition

Every contributor matters.

Whether you submit one documentation fix or hundreds of commits, your contribution helps make FinCore better for everyone.

Thank you for helping build the future of open financial infrastructure.
