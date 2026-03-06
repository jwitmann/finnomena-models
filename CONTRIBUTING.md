# Contributing to finnomena-models

Thank you for your interest in contributing!

## Overview

This is a data type package that supports [finnomena-go](https://github.com/jwitmann/finnomena-go). Changes here should be coordinated with that project.

## When to Contribute

This package typically only needs updates when:
- The Finnomena API adds new fields
- New endpoints are added
- Type corrections are needed

## How to Contribute

### Reporting Issues

If you find issues with the data types:
- Open an issue describing the problem
- Reference the relevant Finnomena API documentation
- Provide example API responses if possible

### Pull Requests

1. Fork the repository
2. Make changes with clear commits
3. Ensure types match the actual API responses
4. Update any related documentation
5. Submit a PR with detailed description

## Type Changes

When modifying types:
- Maintain backward compatibility when possible
- Use `omitempty` for optional fields
- Add JSON tags that match the API field names
- Document any breaking changes

## Questions?

Open an issue for discussion.

Thank you!
