# EnvGuard

[![Live Demo](https://img.shields.io/badge/Live_Demo-envguard.surge.sh-brightgreen?style=for-the-badge)](https://envguard.surge.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

> Scan your code for leaked secrets before you commit. Free, no upload, works offline.

**Try it now:** [envguard.surge.sh](https://envguard.surge.sh)

## What it detects

- **AWS** keys, secret access keys
- **GitHub** tokens (ghp_, gho_, ghu_, ghs_, ghr_)
- **GitLab** tokens
- **Google** API keys, OAuth tokens, Firebase keys
- **Stripe** secret & publishable keys
- **Slack** tokens & webhooks
- **Twilio** account SIDs & auth tokens
- **Private keys** (RSA, SSH, PGP, EC)
- **Database URLs** (Postgres, MySQL, MongoDB, Redis)
- **Passwords** in variables
- **JWTs** and auth headers
- **SendGrid, Mailgun, npm, Docker, Heroku** tokens
- **.env** variable assignments

## How it works

Paste code or drag a file. Results appear instantly. Click a finding to jump to that line.

All scanning is 100% client-side using regex. Zero network requests.

## Tech

Single HTML file. Zero dependencies. Pure JavaScript regex engine.

- 35+ detection rules with severity levels (critical/high/medium/low)
- Click-to-jump to source line
- Drag & drop file support
- Auto-scan on paste
- Keyboard shortcut (Ctrl+Enter)

## Why?

Developers accidentally commit secrets constantly. GitGuardian and truffleHog are great but require installation. EnvGuard lets you do a quick check in your browser before every commit.

## License

MIT
