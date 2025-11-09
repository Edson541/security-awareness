# Security Awareness Starter Kit

## Contents
- `SECURITY_AWARENESS.md`   concise security awareness guide for users
- `phishing_examples.md` — real-world style examples of phishing red flags
- `scripts/password_checker.py` — small local script to evaluate password strength
- `CONTRIBUTING.md` — how to improve this repo

## How to view
1. Clone repository:
2. Read the docs:
3. Run the password checker (needs Python 3):

## Author
Your Name — explain this is a student mini-project for class.
# Security Awareness — Quick Guide

## 1. Password hygiene
- Use passphrases of at least 12 characters, numbers and symbols.
- Avoid reusing passwords across sites.
- Use a reputable password manager.

## 2. Phishing and social engineering
- Check sender email addresses closely.
- Don’t click links from unknown or unexpected emails. Hover to preview links.
- Verify urgent requests by phone or separate channel.

## 3. Device & network safety
- Keep OS and apps updated.
- Use automatic updates where possible.
- Avoid public Wi-Fi for sensitive transactions; use VPN if necessary.

## 4. Data handling
- Encrypt sensitive files before sharing.
- Use least privilege: only give access necessary for the task.

## 5. Reporting and response
- Report suspected phishing to IT/security immediately.
- Preserve the original message for investigation and avoid forwarding it to everyone.

## Short checklist for daily use
- [ ] Password manager enabled
- [ ] MFA enabled on important accounts
- [ ] Suspicious emails reported
# Phishing Examples

## Example 1: Credential-phishing email
**Red flags:** mismatched sender domain, URL shortener, urgent tone, incorrect greetings.

## Example 2: Invoice scam
**Red flags:** unexpected invoice, attachment with macro-enabled document, different payee details.

## How to verify:
1. Confirm with the sender by phone or in person.
2. Check the link by hovering; do not click.
3. If attachment is suspicious, open on a sandboxed machine or ask IT.
#!/usr/bin/env python3
"""
Simple local password strength checker (educational).
It performs basic checks only — do NOT use for production password validation.
"""
import
# Contributing
- Fork the repo, make changes in a feature branch, and open a PR.
- Suggested improvements: add localization, add a quiz, add screenshots for examples.

