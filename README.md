# bootable_macos_recovery.sh

## Security scanning

Run scripts/security-scan-local.sh for local Semgrep Community Edition and applicable Trivy scans. Public GitHub Actions workflows run these scans on changes and weekly, alongside any existing CodeQL workflow. See docs/security-scanning.md for offline setup and updates. Run scripts/install-security-hooks.sh once to enable the staged Semgrep pre-commit hook.
