# Security Policy

## Supported Versions

| Version | Supported |
|---|---|
| 2.x (current) | Yes |
| 1.x | Security patches only |

## Reporting a Vulnerability

We take the security of Tech Passport very seriously. If you've found a security vulnerability, please **do not** open a public GitHub issue.

### How to Report

Please report security vulnerabilities by:
1. Visiting [techpassportapp.com](https://techpassportapp.com) and using the contact form
2. Using the subject line: **[SECURITY] Brief description**

### What to Include
- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment
- Any suggested fixes (optional)

### What Happens Next
- You'll receive acknowledgment within **48 hours**
- We'll investigate and keep you informed of progress
- Once resolved, we'll credit you in our changelog (if desired)
- We aim to resolve critical vulnerabilities within **7 days**

## Security Measures

Tech Passport implements the following security practices:
- All data transmitted over HTTPS/TLS
- Supabase Row Level Security (RLS) for data isolation
- Stripe handles all payment processing (we never store card data)
- Regular dependency updates via Dependabot
- Environment variables for all secrets (never committed to code)
- Authentication via Supabase Auth with JWT tokens

## Responsible Disclosure

We support responsible disclosure. Please give us reasonable time to address issues before any public disclosure.

Thank you for helping keep Tech Passport and our users safe. 🔒
