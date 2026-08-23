# Maintainers

This file lists the maintainers and area reviewers of the Ion project. See
[GOVERNANCE.md](GOVERNANCE.md) for what these roles mean and
[.github/CODEOWNERS](.github/CODEOWNERS) for the authoritative review routing.

## Maintainers

Maintainers own technical direction, the release process, and the specification.

| Maintainer | Affiliation | Areas |
|---|---|---|
| Sidiora Labs Core Team | Sidiora Labs | Runtime, security, specification, releases |

## Area reviewers

| Area | Path | Reviewers |
|---|---|---|
| Runtime & agent loop | `internal/agent/`, `internal/tools/` | Sidiora Labs Core Team |
| Security | `internal/security/` | Sidiora Labs Core Team |
| Session & memory | `internal/session/`, `internal/memory/` | Sidiora Labs Core Team |
| Control plane & protocol | `internal/controlplane/`, `ui/shared/` | Sidiora Labs Core Team |
| Web & terminal operators | `ui/web/`, `ui/tui/` | Sidiora Labs Core Team |
| HNSW sidecar | `hnsw-service/` | Sidiora Labs Core Team |
| Deployment & packaging | `deploy/`, `docker/`, `packaging/` | Sidiora Labs Core Team |

## Contact

- Security reports: see [SECURITY.md](SECURITY.md)
- Conduct reports: conduct@sidioralabs.com
- General questions: [GitHub Discussions](https://github.com/Sidiora-Labs/ion-agent/discussions)
