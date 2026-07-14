← [Back to README](README.md)

---

# Security Policy

Thank you for helping keep FINCore secure.

The security of FINCore is a top priority. We appreciate responsible security research and encourage the responsible disclosure of vulnerabilities.

---

# Supported Versions

Only the following versions receive security updates.

| Version | Supported |
|----------|-----------|
| Main Development Branch | ✅ Yes |
| Latest Stable Release | ✅ Yes |
| Older Releases | ❌ No |

---

# Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub Issues.**

Instead, report vulnerabilities privately so we can investigate and coordinate a responsible disclosure.

Please include as much information as possible:

- Description of the vulnerability
- Steps to reproduce
- A proof of concept (if available)
- Impact assessment
- Affected version(s)
- Suggested mitigation (optional)

---

# Responsible Disclosure Process

After receiving a report, we will:

1. Acknowledge receipt within **72 hours**.
2. Investigate and validate the issue.
3. Work with the reporter if additional information is needed.
4. Develop and test a fix.
5. Publish a security advisory once the fix is available.
6. Credit the reporter (if desired).

---

# Scope

Examples of issues that should be reported include:

- Authentication bypass
- Authorization flaws
- Privilege escalation
- JWT vulnerabilities
- OAuth/OpenID Connect weaknesses
- Cryptographic weaknesses
- Remote Code Execution (RCE)
- SQL Injection
- NoSQL Injection
- Command Injection
- Server-Side Request Forgery (SSRF)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- XML External Entity (XXE)
- Insecure Deserialization
- Path Traversal
- Information disclosure
- Rate limiting bypass
- Session management flaws
- Multi-tenant isolation issues
- Denial of Service vulnerabilities
- Supply-chain vulnerabilities
- Dependency vulnerabilities

---

# Out of Scope

The following are generally considered out of scope:

- Vulnerabilities in unsupported versions
- Missing security headers without exploitable impact
- Best-practice recommendations without a demonstrable security risk
- Self-XSS
- Clickjacking on non-sensitive pages
- Social engineering attacks
- Denial-of-service tests against public infrastructure
- Automated vulnerability scanner output without validation
- Issues requiring physical access to infrastructure

---

# Security Best Practices

FINCore follows secure software development principles including:

- Secure-by-default configuration
- Principle of least privilege
- Defense in depth
- Zero Trust architecture
- Encryption in transit (TLS)
- Encryption at rest
- Strong authentication
- Multi-factor authentication support
- Secure secret management
- Dependency vulnerability scanning
- Continuous security testing
- Static code analysis
- Container image scanning
- Signed releases where applicable
- Comprehensive audit logging

---

# Supported Security Standards

FINCore aims to align with industry best practices including:

- OWASP Top 10
- OWASP ASVS
- OWASP API Security Top 10
- CWE
- CVE
- CVSS
- NIST Secure Software Development Framework (SSDF)

---

# Security Updates

Security fixes are released as quickly as possible after validation.

Critical vulnerabilities may be addressed with emergency releases outside the normal release schedule.

---

# Security Advisories

Security advisories will be published through GitHub Security Advisories whenever appropriate.

---

# Hall of Thanks

We appreciate responsible security researchers who help improve FINCore.

Contributors who responsibly disclose vulnerabilities may be acknowledged in future releases (with their permission).

---

# Contact

Until a dedicated security contact is established, security concerns should be submitted through GitHub's **Private Vulnerability Reporting** feature.

A dedicated security email (e.g., `security@fincore.dev`) may be introduced in a future release.

---

Thank you for helping make FINCore safer for everyone.
