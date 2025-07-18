# Succinct Gaming Verification Site

This is the standalone Twitter verification website for the Succinct Gaming Hub project.

## Features
- Users enter their Twitter username to verify their identity.
- Checks user existence and stats via the public Succinct Stats API.
- Generates a 6-digit verification code for Succinct Gaming Hub registration.
- Responsive, modern UI with inline CSS and JavaScript.
- No backend required — deploy as a static site (Vercel recommended).

## Deployment
- Deploy this folder directly to [Vercel](https://vercel.com/) or any static hosting provider.
- All routes are served by `index.html` (see `vercel.json`).
- Security headers are set in `vercel.json`.

## Configuration
- To update the backend API endpoint, edit the JavaScript section in `index.html` (look for `apiBaseUrl`).
- Update the return URL if your main site changes.

## Custom Domain
- After deploying, add your custom domain in your Vercel project settings.

## Development
- No build tools needed. Just edit `index.html` and deploy.

## License
MIT (or your preferred license)
