# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2026-03-08

### Added

- Language scopes: ruby, go, javascript, rust
- Workflow scopes: security, changelog, release
- Explicit test cases for all new scopes

### Fixed

- Scope validation now matches all scopes documented in DEVELOPMENT.md

## [1.0.0] - 2026-02-20

### Added

- Conventional commit message validation hook for pre-commit v3+
- DevRail-specific types: feat, fix, docs, chore, ci, refactor, test
- DevRail-specific scopes: python, terraform, bash, ansible, ruby, go, javascript, container, ci, makefile, standards
- Clear, actionable error messages on commit rejection
- Merge and revert commit pass-through
- Comprehensive test suite covering all type/scope combinations
- DevRail standard project files (.devrail.yml, .editorconfig, Makefile, agent instructions)
