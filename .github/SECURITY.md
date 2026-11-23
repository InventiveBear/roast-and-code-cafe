# Security Policy

## Supported Versions
Only the latest version deployed on the `main` branch is actively maintained and monitored.

| Version | Supported          |
| ------- | ------------------ |
| `main`  | :white_check_mark: |

## Automated Security Controls
This repository enforces automated DevSecOps controls via GitHub Actions:
- **Secret Scanning:** Gitleaks scans commits to prevent accidental credential exposure.
- **Static Analysis (SAST):** GitHub CodeQL scans JavaScript and HTML assets for DOM XSS and client-side vulnerabilities.
- **Configuration Auditing:** Trivy scans workflow definitions and repository configurations.
- **Dependency Hygiene:** Dependabot monitors GitHub Actions versions weekly.

## Reporting a Vulnerability
If you discover a security vulnerability in this project, please open a **Private Vulnerability Report** via the repository's **Security** tab rather than opening a public issue.