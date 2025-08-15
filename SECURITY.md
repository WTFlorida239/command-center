# Security Policy

The security of the WTF SEO Command Center is a top priority. We appreciate the efforts of security researchers and the community to help us keep our project safe.

---

## Supported Versions

As this is a web application, only the most recent version is considered supported. Please ensure you are reporting vulnerabilities against the latest code in the `main` branch.

---

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

If you discover a security vulnerability, we kindly ask you to send a detailed report to us privately. Please email the report to: **`brendan@example.com`** (🔴 **Important**: Replace this with your actual contact email).

To help us triage and resolve the issue faster, your report should include:

* A clear description of the vulnerability and its potential impact.
* Step-by-step instructions to reproduce the issue.
* Any relevant proof-of-concept code, screenshots, or videos that demonstrate the vulnerability.

### A Note on API Keys

This project integrates with third-party APIs like **OpenAI and Google Gemini**. It is crucial to **never commit your API keys or other secrets** to the repository. These keys should be managed securely using a local `.env` file, which is explicitly ignored by Git in the `.gitignore` file.

---

## Our Commitment

When you report a vulnerability, we will make every effort to:

1.  Acknowledge the receipt of your report within **48 hours**.
2.  Provide an initial assessment and a planned timeline for a fix within **7 days**.
3.  Keep you updated on our progress as we work on a patch.
4.  Notify you when the vulnerability has been resolved.

We thank you for helping to keep this project and its users safe.

---
&copy; 2025 Brendan
