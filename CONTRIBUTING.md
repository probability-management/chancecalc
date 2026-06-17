# Contributing to ChanceCalc

Thank you for your interest in contributing to ChanceCalc!

ChanceCalc is an Excel add-in for modeling uncertainty using Monte Carlo simulation and Probability Management methods. Contributions of all sizes are welcome, including bug fixes, documentation improvements, examples, testing, and new features.

## Ways to Contribute

You can help by:

* Reporting bugs
* Improving documentation
* Adding or improving example models
* Fixing VBA code issues
* Improving build or release processes
* Suggesting new features
* Reviewing pull requests

## Before You Start

Before beginning significant work, please:

1. Search existing Issues and Pull Requests.
2. Open an Issue describing the proposed change.
3. Wait for feedback if the change affects architecture, user workflows, or file formats.
    
Early discussion helps avoid duplicated effort and reduces review time.

## Reporting Bugs

When reporting a bug, please include:

* Operating system
* Excel version
* ChanceCalc version
* Steps to reproduce
* Expected behavior
* Actual behavior
* Screenshots (if applicable)
* Sample workbook (if sharing is possible)

A minimal reproducible example is extremely helpful.

## Suggesting Enhancements

Feature requests should explain:

* The problem being solved
* Why the current behavior is insufficient
* Proposed solution
* Alternative approaches considered

Where possible, include screenshots, mockups, or example workflows.

## Development Guidelines

### Branches

Create feature branches from the active development branch:

```
feature/short-description
bugfix/short-description
docs/short-description
```

Examples:
```
feature/add-correlation-support
bugfix/fix-percentile-chart
docs/update-installation-guide
```

### Coding Standards

Please keep code:

* Readable and well-commented
* Consistent with existing VBA style
* Focused on a single purpose
* Backward-compatible whenever possible

General recommendations:

* Use meaningful variable names.
* Avoid duplicated logic.
* Keep procedures reasonably small.
* Add comments when business logic or probability calculations are not obvious.

## Testing

Before submitting a pull request:

* Verify the add-in loads correctly in Excel.
* Verify existing example workbooks continue to work.
* Test any modified functionality manually.
* Confirm no obvious VBA compile errors exist.
* Update examples or documentation when behavior changes.

If your change affects calculations, include a description of how correctness was verified.

## Documentation Contributions

Documentation improvements are highly valued.

When updating documentation:

* Use clear, concise language.
* Include screenshots where helpful.
* Update related pages if behavior changes.
* Keep terminology consistent with Probability Management concepts.

## Example Contributions

Example workbooks should:

* Demonstrate a specific feature or workflow.
* Be easy to understand.
* Include explanatory notes where appropriate.
* Avoid unnecessary complexity.

## Pull Request Process

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test thoroughly.
5. Update documentation if needed.
6. Submit a Pull Request.

Please include:

* A clear summary of the change
* Related Issue number (if applicable)
* Testing performed
* Screenshots for UI changes

Small, focused pull requests are preferred over large multi-purpose submissions.

## Pull Request Review

Reviewers may request:

* Additional testing
* Documentation updates
* Refactoring for clarity
* Changes to maintain compatibility

Constructive discussion is encouraged. The goal is to improve the project while maintaining reliability for existing users.

## Compatibility

Because ChanceCalc is used within Excel workbooks that may be shared widely, contributors should avoid changes that:

* Break existing workbook behavior
* Change output formats without justification
* Introduce unnecessary dependencies

If a breaking change is unavoidable, clearly document it in the pull request.

## Community Expectations

Please be respectful and professional in all interactions.

We welcome contributors of all experience levels and appreciate your time and effort in helping improve ChanceCalc.

## Questions?

If you're unsure whether an idea is appropriate or how to implement it, open an Issue and start a discussion before writing code.
Thank you for contributing to ChanceCalc!
