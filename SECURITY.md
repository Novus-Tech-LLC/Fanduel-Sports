# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take the security of Crypto Fantasy League seriously. If you believe you have found a security vulnerability, please report it to us as described below.

### Please do NOT:

- Open a public GitHub issue
- Discuss the vulnerability publicly
- Share the vulnerability with others until it has been resolved

### Please DO:

1. **Email us directly** at the security contact (if available) or use the contact information in the README
2. **Provide details** including:
   - Type of vulnerability
   - Location of the affected code
   - Potential impact
   - Steps to reproduce (if applicable)
   - Suggested fix (if you have one)

### What to Expect

- We will acknowledge receipt of your report within 48 hours
- We will provide an initial assessment within 7 days
- We will keep you informed of our progress
- We will notify you when the vulnerability has been resolved

### Disclosure Policy

- We will credit you for the discovery (unless you prefer to remain anonymous)
- We will work with you to coordinate public disclosure after the fix is released
- We aim to resolve critical vulnerabilities within 30 days

## Security Best Practices

When using this application:

1. **Keep dependencies updated** - Regularly update npm packages
2. **Use environment variables** - Never commit sensitive data
3. **Validate inputs** - All user inputs should be validated
4. **Use HTTPS** - Always use HTTPS in production
5. **Review code** - Review code changes before deploying

## Known Security Considerations

- **Environment Variables**: Ensure `.env` files are never committed to version control
- **API Keys**: Store API keys securely and rotate them regularly
- **Farcaster Integration**: Follow Farcaster's security best practices
- **Crypto Transactions**: Implement proper validation and error handling for crypto operations

## Security Updates

Security updates will be released as patches to the current version. We recommend:

- Keeping your dependencies up to date
- Monitoring this repository for security advisories
- Subscribing to release notifications

Thank you for helping keep Crypto Fantasy League and its users safe!

