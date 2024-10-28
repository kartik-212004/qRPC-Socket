# Contributing to qRPC-Socket

First off, thank you for considering contributing to qRPC-Socket! It's people like you that make qRPC-Socket such a great tool. This document provides guidelines and steps for contributing.

## Code of Conduct

By participating in this project, you are expected to uphold our Code of Conduct (to be created). Please report unacceptable behavior to the project maintainers.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues list as you might find that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* Use a clear and descriptive title
* Describe the exact steps which reproduce the problem
* Provide specific examples to demonstrate the steps
* Describe the behavior you observed after following the steps
* Explain which behavior you expected to see instead and why
* Include details about your configuration and environment

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* A clear and descriptive title
* A detailed description of the proposed enhancement
* Examples of how this enhancement would be used
* Any relevant external documentation or references

### Your First Code Contribution

Unsure where to begin contributing to qRPC-Socket? You can start by looking through the 'good-first-issue' and 'help-wanted' issues.

#### Setting Up Your Development Environment

1. Install Rust and Cargo (latest stable version)
2. Install git
3. Install your preferred IDE (we recommend VS Code with rust-analyzer)

#### Local Development Process

1. Fork the Repository:
   ```bash
   # Using GitHub CLI
   gh repo fork anthropic/qRPC-Socket
   
   # Or fork via GitHub web interface
   ```

2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR-USERNAME/qRPC-Socket
   cd qRPC-Socket
   ```

3. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. Set up the development environment:
   ```bash
   cargo build
   cargo test
   ```

### Pull Request Process

1. Update the README.md with details of changes to the interface, if applicable.
2. Update the documentation with details of any new functionality.
3. The PR should work for all supported Rust versions.
4. Follow the PR template when creating your pull request.

#### Pull Request Checklist

Before submitting your PR, make sure you can check off these items:

- [ ] Tests for the changes have been added
- [ ] Documentation has been updated
- [ ] Code follows the project's coding style
- [ ] Commits are properly formatted and have clear messages
- [ ] CI checks pass

### Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

Example:
```
feat(socket): implement custom handshake protocol

- Add WebSocket handshake mechanism
- Implement error handling for connection failures
- Add tests for handshake process

Fixes #123
```

### Branch Naming Convention

* Feature branches: `feature/description`
* Bug fix branches: `fix/description`
* Documentation branches: `docs/description`
* Performance improvement branches: `perf/description`

### Code Style

* Follow Rust style guidelines
* Use `rustfmt` for code formatting
* Run `clippy` for additional linting
* Add comments for complex logic
* Write clear and concise function and variable names

### Testing Guidelines

* Write unit tests for new functionality
* Ensure all tests pass before submitting PR
* Include integration tests when adding new features
* Use meaningful test names that describe the behavior being tested

### Documentation

* Update relevant documentation for any changes
* Include inline documentation for public APIs
* Add examples for new features
* Update the changelog if applicable

## Development Workflow

1. **Select an Issue**: Pick an open issue to work on (or create one)
2. **Create a Branch**: Create a new branch for your work
3. **Develop**: Make your changes, following our coding standards
4. **Test**: Run the test suite and add new tests as needed
5. **Document**: Update documentation as required
6. **Submit**: Create a pull request with your changes

## Getting Help

* Join our community discussions
* Check the project wiki
* Create an issue for questions
* Reach out to maintainers

## Recognition

Contributors will be recognized in our README.md and CONTRIBUTORS.md files.

Thank you for contributing to qRPC-Socket!
