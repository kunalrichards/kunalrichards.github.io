# Security Policy

This repository hosts a **static personal portfolio** (`kunalrichards.github.io`) — HTML, CSS, and vanilla JavaScript served by GitHub Pages. It has no backend, no database, and no user accounts.

## Security posture

- **Content Security Policy** is enforced via `<meta http-equiv="Content-Security-Policy">` on every page, restricting script, style, image, connect, frame, and form-action sources.
- Additional headers: `X-Content-Type-Options: nosniff` and `Referrer-Policy: strict-origin-when-cross-origin`.
- All outbound `target="_blank"` links use `rel="noopener noreferrer"`.
- User-supplied input (the contact form) is escaped before any DOM insertion; no `eval`/`Function` on untrusted data.
- The contact form posts only to allow-listed providers (Web3Forms / FormSubmit); the Web3Forms key is a public submission key by design, not a secret.
- No secrets, tokens, or credentials are committed to this repository.

## Reporting a vulnerability

If you find a security issue (e.g., an XSS vector, a mixed-content or CSP gap, or an exposed asset), please report it privately:

- **Email:** kunalrichards4@gmail.com
- Include the affected URL, a description, and reproduction steps.

Please do **not** open a public issue for security reports. I aim to acknowledge reports within a few days.

## Scope

In scope: pages served from `https://kunalrichards.github.io/` and this repository's contents.
Out of scope: third-party services linked from the site (LinkedIn, GitHub, form providers) and any denial-of-service testing.
