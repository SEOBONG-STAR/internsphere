# Contributing

Thanks for helping improve InternSphere.

## Local preview

Run `python -m http.server 5500` from the repository root and open `http://localhost:5500`.

## Guidelines

- Keep page navigation and shared visual patterns consistent.
- Use semantic HTML, associated form labels, keyboard-accessible controls, and visible focus states.
- Test pages at mobile and desktop widths.
- Do not add real user data, credentials, API tokens, or private certificate files.
- Keep demo-only behavior clearly labelled.

## Before proposing production functionality

Discuss the API contract and authorization model first. The current repository is a static front-end prototype; client-side checks are not a security boundary.