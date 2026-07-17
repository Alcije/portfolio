# Security notes

This portfolio is a static website and does not collect form data.

## Current safeguards

- No public email address or contact form.
- No external JavaScript, font, icon or image dependency.
- External links use `rel="noopener noreferrer"`.
- The included `_headers` file provides a restrictive Content Security Policy and common security headers on compatible hosts such as Netlify.
- JavaScript does not insert user-controlled HTML.

## Before adding a contact form

Use server-side validation, strict length limits, rate limiting, anti-spam protection and a privacy-conscious form processor. Never place private API keys in client-side code.

## Reporting a problem

Open an issue through the public GitHub profile linked from the website.
