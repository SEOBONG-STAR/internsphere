# InternSphere — Internship Management Portal

A multi-page web prototype for organizing an intern's journey across internship opportunities, tasks, learning resources, messages, time logs, feedback, profiles, and certificates.

## Current implementation

The repository is a static HTML/CSS/JavaScript front-end with separate pages. It demonstrates the user experience and page navigation; it does not currently provide a verified production backend or persistent multi-user data service.

## Pages

- `index.html` — welcome / entry page
- `login.html` — login interface
- `internship.html` — internship area
- `dashboard.html` — dashboard
- `task.html` — task tracking
- `learning.html` — learning area
- `messages.html` — messaging interface
- `timelog.html` — time logging
- `feedback.html` — feedback
- `profile.html` — profile
- `certificate.html` — certificate interface

## Run locally

No build step is required. Open `index.html` in a browser, or serve the folder with a local static server:

```bash
python -m http.server 5500
```

Then visit http://localhost:5500.

## Production-readiness notes

This is a front-end prototype. The login page currently navigates to the app without authenticating against a server. Do not treat it as secure authentication or store real user information in the browser. A production version needs a backend API, database, authorization checks, validated file handling for certificates, and server-side audit records.

## Recommended next steps

1. Consolidate shared navigation, styles, and reusable components.
2. Add responsive and accessibility checks across every page.
3. Define API contracts for users, internships, tasks, messages, and time logs.
4. Add a backend with role-based access control for interns and mentors.
5. Add automated browser tests for critical workflows.

## License

No license is currently specified. Contact the repository owner before reuse or redistribution.