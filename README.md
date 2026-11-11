# Code Review

A focused code review skill based on Sentry engineering practices.

## Review areas

- Correctness, runtime errors, and edge cases.
- Performance issues such as N+1 queries and unbounded operations.
- Security vulnerabilities, including injection and access-control gaps.
- Side effects and backwards compatibility.
- Test coverage and long-term architectural impact.

## Review approach

Use this skill when reviewing pull requests or examining code changes. Understand the intended behavior and project conventions first, inspect the relevant diff and surrounding code, and prioritize actionable findings over stylistic preferences.

Feedback should explain the affected behavior, why it matters, and how to address it. Distinguish confirmed defects from questions or optional improvements. The goal is risk reduction and maintainability, not blocking changes over personal style.
