# Northwind Technical Health Review

Static site. Two pages:

- `/` — Northwind Supply Co.: Technical Health Review (client-facing)
- `/inbound-queue` — Inbound Queue Decision Matrix (internal)

## Deploy

    npx vercel login
    npx vercel --prod

Accept the defaults when prompted (scope: heidiw's projects, project name: northwind-technical-health-review, no framework, root directory `./`).
