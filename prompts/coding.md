# Coding Prompts

> Domain: Codex, Code Generation, Debugging, Architecture

---

## Codex Parallel Agent Run
```
Create isolated worktree agents for:
- Feature 1: [description]
- Feature 2: [description]
- Feature 3: [description]

Return diffs for review before committing.
Target branch: [branch name].
Use TypeScript/Python [choose one].
```

## Bug Fix with Root Cause
```
Debug this code. Do not just patch the symptom.
Identify root cause, explain the mechanism,
then provide the fix with inline comments.

[paste code]
```

## Architecture Review
```
Review this architecture for:
- Scalability bottlenecks
- Security gaps
- Over-engineering
- Missing abstractions

Return findings as: Issue | Severity (High/Med/Low) | Recommended Fix

[paste architecture diagram or description]
```

## API Integration Template
```
Write a [language] function to integrate with [API name].
Requirements:
- Auth method: [API key / OAuth / Bearer]
- Endpoint: [URL]
- Handle: rate limits, retries (max 3), error logging
- Return: typed response object
```

## Code Explanation (Intermediate)
```
Explain this code at an intermediate level.
Cover: what it does, how it works mechanistically,
where it could break, and how to extend it.

[paste code]
```

## Refactor for Readability
```
Refactor this code for readability and maintainability.
Do not change behavior. Add docstrings.
Flag any logic that seems fragile.

[paste code]
```
