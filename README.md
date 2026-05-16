# 🛡️ PhishGuard — Phishing Email Detector

> An interactive browser-based tool that analyzes emails for social engineering and phishing attack patterns.

![Cybersecurity](https://img.shields.io/badge/topic-cybersecurity-green?style=flat-square)
![HTML CSS JS](https://img.shields.io/badge/built%20with-HTML%20%7C%20CSS%20%7C%20JS-blue?style=flat-square)
![No dependencies](https://img.shields.io/badge/dependencies-none-lightgrey?style=flat-square)

---

## What it does

PhishGuard lets you paste any suspicious email and instantly analyzes it for phishing indicators. It detects:

- **Domain spoofing** — fake sender addresses that mimic trusted brands
- **Urgency tactics** — pressure language designed to rush victims into acting
- **Credential harvesting** — requests for personal info, passwords, or money
- **Fear and secrecy tactics** — threats of account closure or instructions not to tell anyone
- **Suspicious URLs** — links pointing to fake login pages

Each threat is explained in plain language so users understand *why* something is dangerous, not just *that* it is.

---

## Why I built this

Social engineering is one of the most common and effective attack vectors in cybersecurity — and one of the least understood by everyday users. Most people can't identify a phishing email until it's too late.

PhishGuard makes threat education interactive and accessible. Instead of reading a list of rules, users can load real-world attack scenarios and see exactly what patterns attackers use and why they work psychologically.

---

## How to run it

No installation or server needed. Just open the file:

```bash
git clone https://github.com/YOUR_USERNAME/phishguard.git
cd phishguard
open index.html   # or double-click it in your file explorer
```

Works entirely in the browser — no backend, no dependencies.

---

## Attack scenarios included

| Scenario | Attack type |
|----------|-------------|
| 🏦 Bank alert | Domain spoofing + urgency |
| 🎰 Prize scam | Credential harvesting + advance fee fraud |
| 👔 CEO fraud | Business email compromise (BEC) |
| ✅ Legitimate email | Baseline (no threats) |

---

## Detection logic

The tool scores emails across four threat dimensions:

| Indicator | What it detects | Weight |
|-----------|----------------|--------|
| Urgency tactics | Time-pressure language | 25% |
| Domain spoofing | Fake or lookalike sender domains | 35% |
| Credential harvesting | Requests for info or money | 25% |
| Fear tactics | Threats, secrecy instructions | 15% |

A combined threat score above 50% triggers a phishing verdict.

---

## What I learned

- How social engineering exploits psychological vulnerabilities (urgency, fear, authority)
- The anatomy of phishing emails: domain tricks, URL obfuscation, pressure language
- How defenders think: building detection heuristics based on attacker behavior patterns
- Why cybersecurity awareness training is as important as technical controls

---

## Project context

Built as part of my application to the **INSA Cybersecurity Summer Camp** (Ethiopia). This project demonstrates practical interest in defensive cybersecurity and security awareness.

---

## Author

**Issam Anis**  
Aspiring cybersecurity professional | Ethiopia  
Issamanisb@gmail.com
