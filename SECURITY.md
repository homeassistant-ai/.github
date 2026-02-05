# Security Policy

## Supported Versions

Security updates are provided for the latest stable release of each project in this organization.

| Project | Supported Version |
| ------- | ----------------- |
| ha-mcp  | Latest stable release |
| skills  | Latest version |

For version-specific support, check each project's documentation.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, report them through GitHub's private vulnerability reporting system:

1. Navigate to the affected repository's Security tab
2. Click **"Report a vulnerability"**
3. Fill out the vulnerability report form with:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if you have one)

### What to expect:

- **Initial response:** Within 48 hours
- **Assessment:** We'll evaluate severity and impact
- **Fix timeline:** Typically 24-48 hours for critical issues, longer for lower-severity issues
- **Disclosure:** We'll coordinate public disclosure after a fix is available

### Scope

Security issues we're interested in:
- Authentication/authorization bypasses
- Code injection vulnerabilities
- Information disclosure (tokens, credentials, personal data)
- Denial of service attacks
- Dependencies with known CVEs

### Out of Scope

- Issues in third-party dependencies (report to the dependency maintainers)
- Social engineering attacks
- Physical security issues

## Security Best Practices

When using our projects:

### ha-mcp
- **Protect your Home Assistant token** - treat it like a password
- Use environment variables or secure vaults for credentials
- Don't commit `.env` files to version control
- Use HTTPS for Home Assistant URLs when possible
- Keep ha-mcp updated to get security patches

### skills
- Review skill code before trusting it to modify your system
- Be cautious with skills that have broad permissions
- Report suspicious skill behavior immediately

## Coordinated Disclosure

We follow responsible disclosure practices:
- We'll acknowledge your report privately
- We'll work with you to understand and fix the issue
- We'll give you credit in the security advisory (if you want it)
- We'll coordinate public disclosure timing with you

Thank you for helping keep Home Assistant AI projects secure! 🔒
