# neon-dominion

> Unity 6 tactical simulation game prototype exploring Dominion-style systems and sector control gameplay.
> Status: `active`

![CI](https://img.shields.io/github/actions/workflow/status/zachyzissou/neon-dominion/baseline-csharp-ci.yml)
![Coverage](https://img.shields.io/badge/coverage-70%25-brightgreen)
![License](https://img.shields.io/github/license/zachyzissou/neon-dominion)
![Security](https://img.shields.io/badge/security-SECURITY.md-green)

## Overview
Unity 6 tactical simulation game prototype exploring Dominion-style systems and sector control gameplay.

## Problem / Value
- **Problem:** Provides shared gameplay foundations with clear architecture so contributors can move from prototype to implementation faster.
- **Value:** Standardized docs and governance reduce maintenance burden and security risk.
- **Users:** Unity developers, content designers, and maintainers.

## Architecture
```text
Source Inputs --> Validation --> Processing --> Delivery
              \--> Operations + Governance
```

## Features
- ✅ Unity project structure and design docs are present
- ✅ Gameplay pillars and architecture docs are defined
- ✅ Branch-aware baseline documentation added for maintainability
- ⏳ Automated runtime tests and packaging are planned

## Tech Stack
- Runtime: Unity 6 (C# scripting)
- Framework: Unity Engine + URP/UI Toolkit
- Tooling: Unity Editor, git
- CI: GitHub Actions
- Storage: Git repository + project assets

## Prerequisites
- Git
- Language runtime aligned with repository code
- Required service credentials injected securely

## Installation
```bash
git clone https://github.com/zachyzissou/neon-dominion.git
cd neon-dominion
```

## Configuration
| Key | Required | Default | Notes |
| --- | --- | --- | --- |
| `BRANCH_DEFAULT` | no | `main` | Target branch policy |
| `LOG_LEVEL` | no | `info` | debug/info/warn/error |
| `APP_ENV` | no | `dev` | Use `prod` in deployment |

## Usage
```bash
dotnet test
```

## Testing & Quality
```bash
dotnet test
```

Coverage goal: 70% minimum for touched areas.

## Security
- Report issues via `SECURITY.md`.
- Never commit secrets or credentials.
- Protect default branch and require review before merge.

## Contributing
1. Branch from default branch (`main`)
2. Run checks in this repo and include outputs in PR
3. Keep PRs focused and add rationale for behavioral changes
4. Request review and obtain approval before merge

## Deployment / runbook
- Deployment target: default branch ` main `
- Rollback: revert commit and redeploy previous release/tag
- Emergency: pause workflows and disable risky automation if needed

## Troubleshooting
- CI not running: verify workflow path and branch filters
- Test failures: run locally and capture logs
- Config issues: validate config files and required keys

## Observability
- Health checks: local logs and workflow status
- Alerts: PR and workflow notifications
- SLO target: timely green checks on PRs

## Roadmap
- Expand tests and automation coverage
- Add dependency updates policy and security scanning
- Improve deployment/runbook section with real endpoints

## Known Risks
- Branch naming and legacy scripts can diverge by repo
- Some repos are early-stage and may not have all checks available

## Release Notes / Changelog
- Baseline governance, deep README, and CI workflow added.

## License & contact
- License: Not specified in repo files; preserve existing policy references
- Contact: @zachyzissou / Security: see SECURITY.md

_Last updated: 2026-02-23_
