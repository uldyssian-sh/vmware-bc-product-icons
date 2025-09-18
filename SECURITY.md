# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Security Considerations

### Icon Collection Security
- **Static Assets**: This repository contains only static PNG icon files
- **No Executable Code**: No runtime security vulnerabilities in static assets
- **Transparent PNGs**: All icons use transparent backgrounds (no embedded scripts)
- **File Integrity**: ZIP archive integrity verified in CI/CD pipeline

### Repository Security
- **Dependabot**: Automated dependency updates enabled
- **Branch Protection**: Main branch protected with required status checks
- **Signed Commits**: GPG verification recommended for contributors
- **Access Control**: Repository access limited to authorized contributors

## Reporting Security Issues

### For Repository Issues
If you discover a security vulnerability in this repository:

1. **DO NOT** create a public GitHub issue
2. Email: Create a private security advisory via GitHub
3. Include: Detailed description of the vulnerability
4. Response: We will respond within 48 hours

### For Icon Content Issues
If you find inappropriate or malicious content in icons:

1. Create a GitHub issue with `security` label
2. Specify the affected icon file(s)
3. Describe the security concern
4. We will investigate and respond within 24 hours

## Security Best Practices

### For Users
- Verify ZIP file integrity before extraction
- Scan extracted files with antivirus software
- Use icons only from official releases
- Report suspicious content immediately

### For Contributors
- Sign commits with GPG keys
- Follow secure development practices
- Validate icon sources and authenticity
- Remove metadata from uploaded icons

## Compliance

This repository follows:
- GitHub Security Best Practices
- Open Source Security Foundation (OpenSSF) guidelines
- Supply Chain Security standards
- Free Tier optimization for automated security scanning

## Contact

For security-related questions:
- GitHub Security Advisories (preferred)
- Repository Issues (for non-sensitive matters)
- Email: 25517637+uldyssian-sh@users.noreply.github.com

---

**Last Updated**: December 2024