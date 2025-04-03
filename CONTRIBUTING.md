# Contributing to letterboxd-viewer

This repository is a fork of [michaellambgelo/letterboxd-viewer](https://github.com/michaellambgelo/letterboxd-viewer) with the goal of extending its functionality while maintaining compatibility for upstream contributions.

## Branch Strategy

This repository maintains two primary branches:

- `main`: Contains our enhanced version with additional features aimed at broader user adoption
- `last-four-watched`: Maintains compatibility with the original repository for upstream contributions

## How to Contribute

### For the Enhanced Web App (main branch)

1. Fork this repository
2. Create a feature branch from `main`
3. Implement your changes
4. Submit a pull request to merge into our `main` branch

### For Upstream Contributions

1. Fork this repository
2. Create a feature branch from `last-four-watched`
3. Implement your changes
4. Submit a pull request to merge into our `last-four-watched` branch
5. After review, we'll submit these changes to the original repository

## Development Workflow

When adding features:
- Features specific to our enhanced version should be implemented in branches from `main`
- Bug fixes or features that could benefit the original project should be implemented in branches from `last-four-watched`
- Critical fixes may be implemented in `last-four-watched` and then merged into `main`

## Code Standards

Please adhere to the project's existing code style and include appropriate tests for your changes.

## Questions?

If you have questions about which branch to target or how to structure your contributions, please open an issue for discussion.
