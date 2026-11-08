# Security Policy

This policy covers this repository. My other repositories follow the same process unless they include their own `SECURITY.md`.

## Supported Versions

Only the latest code on the default branch receives security fixes. Older commits, branches and forks are not supported.

## Reporting a Vulnerability

Please report security vulnerabilities privately. **Do not** open a public issue.

- **Preferred:** on the affected repository, open the **Security** tab and click **Report a vulnerability** (GitHub [private vulnerability reporting](https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/report-privately)). This option appears only where private reporting is enabled.
- **Otherwise:** email **souravlai7@gmail.com**.

Please include:

- a description of the issue and where it is (repository, file, URL or endpoint)
- steps to reproduce, or a proof of concept
- the potential impact

Do not disclose the vulnerability publicly until it has been fixed.

## What to Expect

- **Acknowledgement:** usually within 3 days
- **Assessment:** usually within 7 days of acknowledgement
- **Fix:** timing depends on severity; critical issues are prioritized
- **Credit:** you will be credited in the fix or advisory if you want to be

## Security Practices

- Dependencies are kept up to date, with Dependabot where it is configured
- Secrets and credentials are never committed to repositories
- Code follows secure coding practices, including input validation and parameterized database queries
